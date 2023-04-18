---
title: Hapus Anotasi PPTX menggunakan Java
weight: 360
url: /id/java/annotation/pptx/ 
description: Kode sampel Java untuk menghapus anotasi format PPTX di Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Hapus Komentar dan Penulis Komentar dari PPTX di Java" h2="Bangun aplikasi Java Anda sendiri untuk memanipulasi komentar dan penulis dalam file dokumen menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Hapus Komentar dari PPTX via Java" %}}
Untuk menghapus anotasi dari file PPTX, kami akan menggunakan API [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/) yang kaya fitur, andal, dan mudah digunakan API manipulasi dokumen untuk platform Java.
{{% blocks/products/pf/agp/code-block title="Hapus Anotasi dari PPTX - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.pptx");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menghapus Komentar dari PPTX melalui Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk Java**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPTX dengan instance kelas Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi semua Penulis PPTX yang dimuat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hapus semua Komentar dari seorang penulis
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hapus semua Penulis di bagian akhir
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Anotasi Lain yang Didukung" subTitle="Menggunakan Java, seseorang dapat dengan mudah membuat anotasi format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}