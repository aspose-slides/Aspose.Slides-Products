---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปลดล็อกงานนำเสนอ ODP ด้วย Python
url: /th/python-net/unlock/odp/
description: ลบการเข้ารหัสและการป้องกันการเขียนออกจากงานนำเสนอ ODP ด้วย Python
keywords: ปลดล็อก ODP, ลบรหัสผ่านออกจาก ODP, ลบการเข้ารหัส ODP, ลบการป้องกันการเขียนออกจาก ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปลดล็อกงานนำเสนอ ODP ด้วย Python" h2="สร้างแอปพลิเคชัน Python ที่ลบรหัสผ่านสำหรับเปิดและการตั้งค่าการป้องกันการเขียนออกจากงานนำเสนอ ODP ด้วย Aspose.Slides" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบการเข้ารหัสและการป้องกันการเขียนออกจาก ODP ด้วย Python" variant="code" %}}

ด้วย [Aspose.Slides for Python via .NET](/slides/th/python-net/) คุณสามารถลบการเข้ารหัสที่ต้องใช้รหัสผ่านในการเปิดงานนำเสนอ ODP หรือปิดการตั้งค่าการป้องกันการเขียนได้ หากต้องการเปิดไฟล์ที่เข้ารหัส ให้ระบุรหัสผ่านปัจจุบันผ่าน `LoadOptions`

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการเข้ารหัสออกจากงานนำเสนอ ODP – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการป้องกันการเขียนออกจากงานนำเสนอ ODP – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบการป้องกันออกจาก ODP ด้วย Python" intro="ทำตามขั้นตอนต่อไปนี้เพื่อลบการป้องกันออกจากงานนำเสนอ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สำหรับไฟล์ ODP ที่เข้ารหัส ให้ตั้งรหัสผ่านปัจจุบันใน `LoadOptions` แล้วเปิดไฟล์ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `ProtectionManager.remove_encryption` เพื่อลบรหัสผ่านสำหรับเปิด หรือเรียก `ProtectionManager.remove_write_protection` เพื่อปิดการป้องกันการเขียน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่ได้ด้วย `SaveFormat.ODP`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="สร้างด้วย Aspose.Slides" title="ปลดล็อกไฟล์ ODP ทางออนไลน์" description="แอป Aspose.Slides Unlock ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Unlock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบการป้องกันอย่างไรก่อนเขียนโค้ด
- ลบรหัสผ่านหรือการป้องกันการเขียนออกจากไฟล์ ODP ของคุณ
- ดาวน์โหลดไฟล์ที่ปลดล็อกแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปลดล็อก" subTitle="ใช้ Python เพื่อลบการป้องกันออกจากรูปแบบงานนำเสนออื่นที่รองรับ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
