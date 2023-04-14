---
title: Konversi PPTX ke Word di Java
url: /id/java/conversion/pptx-to-word/
keywords: Konversi PPTX ke Word, PPTX ke Word, PPTX ke DOC, PowerPoint ke Word, API Java, Perpustakaan Java
description: Konversi PPTX ke Word di Java. Gunakan Java library API untuk mengonversi PowerPoint ke Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversi PPTX ke Word di Java" h2="API Java lintas platform yang kuat untuk mengonversi PowerPoint ke Word menggunakan kode Java tanpa Microsoft PowerPoint atau Office" >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PowerPoint ke Word menggunakan Aspose.Slides dan Aspose.Words" %}}

[**Aspose.Slides untuk Java**](https://products.aspose.com/slides/id/java/) dan [**Aspose.Words untuk Java**](https://products.aspose.com/ kata/java/) adalah pustaka Java yang kuat yang digunakan untuk memanipulasi dan mengonversi presentasi PowerPoint, dokumen Word, dan file lainnya. Saat Anda mengonversi PowerPoint ke Word, pada dasarnya Anda memindahkan konten slide presentasi ke halaman dalam dokumen Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konversikan PowerPoint ke Word di Java" %}}
Anda dapat mengonversi PPTX ke Word dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode Java untuk mengonversi PowerPoint ke Word" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Bagaimana mengkonversi PPTX ke Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk Java** dan **Aspose.Words untuk Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat instance kelas Presentation dan kelas Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat presentasi PPTX yang ingin Anda konversi ke Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hasilkan gambar dan teks berdasarkan konten slide.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan dokumen Word yang dihasilkan.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PowerPoint ke file dalam format lain" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}