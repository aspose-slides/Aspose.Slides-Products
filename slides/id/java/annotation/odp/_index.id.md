---
title: Hapus Anotasi ODP menggunakan Java
weight: 1790
url: /id/java/annotation/odp/ 
description: Contoh kode Java untuk menghapus anotasi format ODP di Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Hapus Komentar dan Penulis Komentar dari ODP di Java" h2="Bangun aplikasi Java Anda sendiri untuk memanipulasi komentar dan penulis dalam file dokumen menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Hapus Komentar dari ODP melalui Java" %}}
Untuk menghapus anotasi dari file ODP, kami akan menggunakan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/) API yang kaya fitur, andal, dan mudah digunakan API manipulasi dokumen untuk platform Java.
{{% blocks/products/pf/agp/code-block title="Hapus Anotasi dari ODP - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
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

{{< blocks/products/pf/feature-page-section  h2="Cara Menghapus Komentar dari ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk Java**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat ODP dengan instance kelas Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi semua Penulis ODP yang dimuat
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}