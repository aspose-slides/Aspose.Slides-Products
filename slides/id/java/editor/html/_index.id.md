---
title: Edit HTML di Jawa
url: /id/java/editor/html/
keywords: Edit HTML, HTML, API Java, Pustaka Java
description: Edit HTML di Jawa. Gunakan Java library API untuk mengedit file HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML di Jawa" h2="Pustaka Java berkecepatan tinggi dan lintas platform untuk mengedit HTML menggunakan kode Java" >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML menggunakan Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/) adalah library Java canggih yang digunakan untuk memanipulasi dan mengedit presentasi, dokumen HTML, dan file lainnya. Anda dapat mengedit dokumen HTML dengan menambahkan baris teks baru ke dalamnya. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit HTML di Jawa" %}}
Menggunakan [**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/), Anda dapat menambahkan baris teks baru ke dokumen HTML hanya dengan beberapa baris kode.

{{% blocks/products/pf/agp/code-block title="Kode Java untuk mengedit HTML" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cara mengedit HTML di Java" >}}


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
Muat dokumen HTML yang ingin Anda edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan baris teks baru.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan file HTML yang diubah.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Mengedit file lain" subTitle="Anda juga dapat mengedit file dalam format lain" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}