---
title: Hapus Anotasi PPTX menggunakan .NET
weight: 4380
url: /id/net/annotation/pptx/ 
description: Kode sumber C# untuk menghapus anotasi format PPTX pada Platform .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Hapus Komentar dan Penulis Komentar dari PPTX di C#" h2="Bangun aplikasi .NET Anda sendiri untuk memanipulasi komentar dan penulis dalam file dokumen menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Hapus Komentar dari PPTX melalui C#" %}}
Untuk menghapus anotasi dari file PPTX, kami akan menggunakan API [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net) yang kaya fitur, andal, dan mudah digunakan API manipulasi dokumen untuk platform C#.
{{% blocks/products/pf/agp/code-block title="Hapus Anotasi dari PPTX - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menghapus Komentar dari PPTX melalui C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk .NET**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/net/installation/).
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

{{< blocks/products/pf/agp/other-supported-section title="Format Anotasi Lain yang Didukung" subTitle="Menggunakan C#, seseorang dapat dengan mudah membuat anotasi format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}