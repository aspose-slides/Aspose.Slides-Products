---
title: การแปลงงานนำเสนอ Microsoft PowerPoint เป็นรูปแบบต่างๆ โดยใช้ C++
url: /th/cpp/conversion/
description: แปลง Microsoft PowerPoint Slides เป็นไฟล์หลายไฟล์ รวมถึงรูปแบบ HTML, PDF และรูปภาพภายในแอปพลิเคชันที่ใช้ C++
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> การแปลงงานนำเสนอ PowerPoint ผ่าน C++" h2="โค้ดตัวอย่าง C++ สำหรับสถานการณ์การแปลงต่างๆ เพื่อแปลงสไลด์เป็นรูปภาพ, HTML, PDF และรูปแบบอื่นๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}

กระบวนการแปลงรูปแบบ Microsoft<sup>®</sup> PowerPoint นั้นง่ายและสะดวกสำหรับกระบวนการอัตโนมัติโดยใช้ไลบรารี C++ PowerPoint นักพัฒนาสามารถปรับปรุงซอร์สโค้ดที่เกี่ยวข้องและรวมเข้ากับแอปพลิเคชันของตนได้ 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="การแปลงระหว่างรูปแบบ Microsoft PowerPoint" %}}
การแปลงระหว่างเอกสาร Microsoft<sup>®</sup> PowerPoint รวมถึง PPT, PPTX โดยทางโปรแกรมเป็นเพียงโค้ดสองบรรทัด โหลดไฟล์โดยใช้ [คลาสการนำเสนอ](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) และเรียก [วิธีการบันทึก](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) มีไฟล์เอาต์พุตและ SaveFormat.OutputFormats เป็นพารามิเตอร์

{{% blocks/products/pf/feature-page-code h3="รหัสการแปลง C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ PowerPoint เป็น PDF" %}}

การแปลง Microsoft<sup>®</sup> PowerPoint เป็น PDF เป็นสถานการณ์ทั่วไปเนื่องจากการแชร์เอกสาร PDF จำนวนมาก โปรแกรมเมอร์สามารถทำให้เป็นอัตโนมัติและตั้งค่าการแปลงไฟล์ PDF ที่เกี่ยวข้องโดยใช้ [คลาส PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) การตั้งค่าเฉพาะบางอย่าง เช่น ระดับการบีบอัดข้อความ คุณภาพ JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861) ระดับการปฏิบัติตามข้อกำหนดของ PDF [การปฏิบัติตามข้อกำหนด] (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f) การแปลงสไลด์ที่ซ่อนอยู่ [ShowHiddenSlides](https://apireference.aspose.com/classslides/cpp/ /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23) สไลด์ที่เลือกและสร้างการล็อก [รหัสผ่าน](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab4195306dbba7) ไฟล์ PDF ป้องกัน .

{{% blocks/products/pf/feature-page-code h3="รหัสการแปลง C++ PowerPoint เป็น PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="บันทึกสไลด์ Microsoft PowerPoint เป็นรูปภาพ" %}}
เมื่อใดก็ตามที่มีกรณีในการแสดงเนื้อหาการนำเสนอบนเว็บ ก็จำเป็นต้องแสดงไฟล์เป็น HTML หรือรูปภาพ JPG, TIFF, PNG ฯลฯ ขั้นตอนการแปลงสไลด์เป็นรูปภาพนั้นง่าย รับสไลด์ทั้งหมดโดยใช้ [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) และวนซ้ำในแต่ละสไลด์ ในระหว่างการทำซ้ำแต่ละครั้ง ให้ใช้ [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) สำหรับภาพสไลด์แล้วบันทึกลงในรูปแบบภาพที่ต้องการ 

{{% blocks/products/pf/feature-page-code h3="C ++ PowerPoint เป็นการแปลงรูปภาพ" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}