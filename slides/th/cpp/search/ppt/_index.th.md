---
title: ค้นหาข้อความในไฟล์การนำเสนอ PPT โดยใช้ C++
url: /th/cpp/search/ppt/
keywords: คำค้นหาใน PPT ค้นหาและแทนที่ข้อความใน PPT ข้อความค้นหา PPT
description: ซอร์สโค้ด C++ เพื่อค้นหาข้อความในงานนำเสนอ PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ค้นหาข้อความ PPT โดยใช้ C++" h2="สร้างแอป C++ ของคุณเองเพื่อค้นหาและแทนที่ข้อความในไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์ เรียนรู้วิธีค้นหาทางเข้าทั้งหมดของคำหรือวลีในเอกสารนำเสนอ ค้นหาข้อความด้วยการจับคู่ข้อมูลที่ตรงทั้งหมดและการจับคู่นิพจน์ทั่วไป" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="ค้นหาและแทนที่ข้อความ PPT งานนำเสนอผ่าน C++" %}}
การค้นหาเอกสารพื้นฐานและแทนที่ข้อความในเนื้อหา ความคิดเห็น บันทึกสไลด์ หรือข้อมูลเมตาด้วย API ของ Aspose.Slides for C++ สามารถทำได้ด้วยโค้ดเพียงไม่กี่บรรทัด ใช้การจับคู่นิพจน์ทั่วไป จับคู่ตัวพิมพ์เล็กและตัวพิมพ์เพื่อค้นหาข้อความในงานนำเสนอ ค้นหาข้อความในชื่อเรื่อง เนื้อหา ส่วนท้ายหรือส่วนหัว
{{% blocks/products/pf/agp/code-block title="ค้นหาข้อความ PPT งานนำเสนอโดยใช้ C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.ppt", SaveFormat::Ppt);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีค้นหาข้อความใน PPT ผ่าน C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการค้นหาไฟล์ข้อความ PPT" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPT ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ใช้เมธอด [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) เพื่อค้นหาและแทนที่ข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ PPT ค้นหาการสาธิตสด" sectionDescription="ค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาในเอกสาร PPT ทันที" >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการค้นหาอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C++ คุณยังสามารถค้นหาข้อความในรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}