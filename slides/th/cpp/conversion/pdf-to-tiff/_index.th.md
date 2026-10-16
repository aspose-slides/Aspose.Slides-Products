---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PDF เป็น TIFF ใน C++
url: /th/cpp/conversion/pdf-to-tiff/
keywords: PDF เป็น TIFF, แปลง PDF เป็น TIFF, C++ API, C++ Library, PDF, TIFF
description: แปลง PDF เป็น TIFF ใน C++ ใช้ C++ library API เพื่อแปลงไฟล์ PDF เป็น TIFFs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PDF เป็น TIFF ใน C++" h2="ไลบรารี C++ ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PDF เป็น TIFF โดยใช้ C++" variant="code" %}}

หากต้องการแปลง PDF เป็น TIFF คุณจะต้องสร้างงานนำเสนอจากไฟล์ PDF และบันทึกเป็น TIFF

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ด C++ สำหรับแปลง PDF เป็น TIFF" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"InputPDF.pdf");
pres->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PDF เป็น TIFF ใน C++" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ ที่ทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง PDF เป็น TIFF เมื่อใช้ **Aspose.Slides สำหรับ C+++** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ PDF เป็น TIFF ด้วยโค้ด C++ เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ C++ จะส่งออกไฟล์ PDF เป็นรูปแบบไฟล์ TIFF ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง PDF เป็น TIFF และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PDF เป็น TIFF โดยใช้ Aspose.Slides สำหรับ C++ API" intro="นี่คือขั้นตอนในการแปลง PDF เป็น TIFF ใน C++" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง [**Aposose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ C++ ของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดซอร์สไฟล์ PDF ใน C++{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกผลลัพธ์เป็นไฟล์ TIFF{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="ตัวแปลงออนไลน์ฟรี"
  description="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แปลง PDF เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง PDF และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
