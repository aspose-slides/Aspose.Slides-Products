---
title: Edit PDF di Jawa
url: /id/java/editor/pdf/
keywords: Edit PDF, PDF, API Java, Perpustakaan Java
description: Edit PDF di Jawa. Gunakan Java library API untuk mengedit dokumen PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PDF di Jawa" h2="Pustaka Java berkecepatan tinggi dan lintas platform untuk mengedit PDF menggunakan kode Java" >}}

{{% blocks/products/pf/feature-page-section h2="Edit PDF menggunakan Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/) adalah library Java andal yang digunakan untuk memanipulasi dan mengedit presentasi, dokumen PDF, dan file lainnya. Anda dapat mengedit dokumen PDF dengan menambahkan baris teks baru ke dalamnya. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit PDF di Jawa" %}}
Menggunakan [**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/), Anda dapat menambahkan baris teks baru ke dokumen PDF hanya dengan beberapa baris kode.

{{% blocks/products/pf/agp/code-block title="Kode Java untuk mengedit PDF" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("document.pdf");

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("document.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cara mengedit PDF di Jawa" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk Java**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan perpustakaan sebagai referensi dalam proyek Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat sebuah instance dari kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat dokumen PDF yang ingin Anda edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan baris teks baru.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan file PDF yang diubah.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Mengedit file lain" subTitle="Anda juga dapat mengedit file dalam format lain" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}