---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PPT เป็นวิดีโอใน C++
url: /th/cpp/conversion/ppt-to-video/
keywords: แปลง PPT เป็นวิดีโอ, PPT เป็นวิดีโอ, PowerPoint เป็นวิดีโอ, PPT เป็น MP4, C++ API, C++ Library
description: แปลง PPT เป็นวิดีโอใน C++ ใช้ API ของไลบรารี C++ เพื่อแปลง PowerPoint เป็นวิดีโอ
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PPT เป็นวิดีโอใน C++" h2="C++ API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง PowerPoint เป็นวิดีโอโดยใช้โค้ด C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PowerPoint เป็นวิดีโอใน C++" variant="code" %}}

ใช้รหัส C++ นี้เพื่อแปลง PPT เป็นวิดีโอ:

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ด C++ สำหรับแปลง PowerPoint เป็นวิดีโอ" >}}
```c++

void OnFrameTick(System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args)
{
    System::String fileName = System::String::Format(u"frame_{0}.png", sender->get_FrameIndex());
    args->GetFrame()->Save(fileName);
}

void Run()
{
    auto presentation = System::MakeObject<Presentation>();
    auto slide = presentation->get_Slide(0);

    // Adds a smile shape and then animates it
    System::SharedPtr<IAutoShape> smile = slide->get_Shapes()->AddAutoShape(ShapeType::SmileyFace, 110.0f, 20.0f, 500.0f, 500.0f);
    auto sequence = slide->get_Timeline()->get_MainSequence();
    System::SharedPtr<IEffect> effectIn = sequence->AddEffect(smile, EffectType::Fly, EffectSubtype::TopLeft, EffectTriggerType::AfterPrevious);
    System::SharedPtr<IEffect> effectOut = sequence->AddEffect(smile, EffectType::Fly, EffectSubtype::BottomRight, EffectTriggerType::AfterPrevious);
    effectIn->get_Timing()->set_Duration(2.0f);
    effectOut->set_PresetClassType(EffectPresetClassType::Exit);

    const int32_t fps = 33;

    auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation);
    auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, fps);
    player->FrameTick += OnFrameTick;
    animationsGenerator->Run(presentation->get_Slides());

    const System::String ffmpegParameters = System::String::Format(
        u"-loglevel {0} -framerate {1} -i {2} -y -c:v {3} -pix_fmt {4} {5}",
        u"warning", m_fps, "frame_%d.png", u"libx264", u"yuv420p", "video.mp4");
    auto ffmpegProcess = System::Diagnostics::Process::Start(u"ffmpeg", ffmpegParameters);
    ffmpegProcess->WaitForExit();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PowerPoint เป็นวิดีโอโดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ อันทรงพลังที่ใช้สร้าง แก้ไข และจัดการงานนำเสนอ และยังแปลงงานนำเสนอ PowerPoint เป็นเอกสารและวิดีโออื่นๆ . ในกรณีนี้ ในการแปลง PowerPoint เป็นวิดีโอ คุณต้องใช้ **Aspose.Slides** ควบคู่ไปกับ **ffmpeg**

นี่เป็นวิธีการทำงานของกระบวนการแปลง PPT เป็นวิดีโอ: Aspose.Slides ใช้เพื่อสร้างชุดของเฟรม (จากสไลด์การนำเสนอ) จากนั้นใช้ FFMpegCore (ffmpeg) เพื่อสร้างวิดีโอตามเฟรม

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PPT เป็นวิดีโอ" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง **Aspose.Slides สำหรับ C+** โดยทำตามคำแนะนำ[ที่นี่](https://docs.aspose.com/slides/cpp/installation/) ดาวน์โหลด **ffmpeg** [ที่นี่](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มเส้นทางไปยัง `ffmpeg.exe` ไปยังตัวแปรสภาพแวดล้อม 'PATH'{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}คัดลอก วาง แล้วเรียกใช้โค้ด C++ PowerPoint เป็นวิดีโอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PowerPoint เป็นไฟล์ในรูปแบบอื่นๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
