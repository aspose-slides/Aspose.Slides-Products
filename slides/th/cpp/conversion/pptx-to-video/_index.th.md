---
title: แปลง PPTX เป็นวิดีโอใน C++
url: /th/cpp/conversion/pptx-to-video/
keywords: แปลง PPTX เป็นวิดีโอ, PPTX เป็นวิดีโอ, PowerPoint เป็นวิดีโอ, PPTX เป็น MP4, C++ API, C++ Library
description: แปลง PPTX เป็นวิดีโอใน C++ ใช้ API ของไลบรารี C++ เพื่อแปลง PowerPoint เป็นวิดีโอ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPTX เป็นวิดีโอใน C++" h2="C++ API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง PowerPoint เป็นวิดีโอโดยใช้โค้ด C++" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PowerPoint เป็นวิดีโอโดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ อันทรงพลังที่ใช้สร้าง แก้ไข และจัดการงานนำเสนอ และยังแปลงงานนำเสนอ PowerPoint เป็นเอกสารและวิดีโออื่นๆ . ในกรณีนี้ ในการแปลง PowerPoint เป็นวิดีโอ คุณต้องใช้ **Aspose.Slides** ควบคู่ไปกับ **ffmpeg**

นี่เป็นวิธีการทำงานของกระบวนการแปลง PPTX เป็นวิดีโอ: Aspose.Slides ใช้เพื่อสร้างชุดของเฟรม (จากสไลด์การนำเสนอ) จากนั้นใช้ FFMpegCore (ffmpeg) เพื่อสร้างวิดีโอตามเฟรม

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPTX เป็นวิดีโอ" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aspose.Slides สำหรับ C+** โดยทำตามคำแนะนำ[ที่นี่](https://docs.aspose.com/slides/cpp/installation/) ดาวน์โหลด **ffmpeg** [ที่นี่](https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มเส้นทางไปยัง `ffmpeg.exe` ไปยังตัวแปรสภาพแวดล้อม 'PATH'
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
คัดลอก วาง แล้วเรียกใช้โค้ด C++ PowerPoint เป็นวิดีโอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็นวิดีโอใน C++" %}}
ใช้รหัส C++ นี้เพื่อแปลง PPTX เป็นวิดีโอ:

{{% blocks/products/pf/agp/code-block title="โค้ด C++ สำหรับแปลง PowerPoint เป็นวิดีโอ" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PowerPoint เป็นไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}