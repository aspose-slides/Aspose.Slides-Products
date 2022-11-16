---
title: Konversi PDF ke PNG di C#
weight: 90
url: /id/net/conversion/pdf-to-png/ 
keywords: PDF ke PNG, Konversi PDF ke PNG, C# API, .NET Library, PDF, PNG
description: Konversi PDF ke PNG di C#. Gunakan .NET library API untuk mengonversi halaman PDF ke gambar PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konversi PDF ke PNG di C#" h2="PowerPoint .NET API untuk mengonversi dokumen PDF ke gambar PNG di NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="jpg" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}


{{% blocks/products/pf/agp/content h2="Cara Mengonversi PDF ke PNG di C#" %}}

Bagaimana cara mengonversi PDF ke PNG dalam kode?

Menggunakan [**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/), pengembang atau aplikasi apa pun dapat mengonversi PDF ke format PNG hanya dengan beberapa baris kode C#.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk .NET mengekspor halaman PDF ke PNG dengan cepat. Perpustakaan Apose PowerPoint memungkinkan Anda mengonversi PDF ke PNG dan banyak format file lainnya

Untuk menginstal Aspose.Slides: Buka [NuGet](https://www.nuget.org/packages/aspose.slides.net) pengelola paket. Cari *Aspose.Slides* dan instal.
 
Atau Anda dapat menginstal **Aspose.Slides** dengan menjalankan perintah ini dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Cara Mengonversi PDF ke PNG di C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Pengembang dan aplikasi dapat mengonversi PDF ke PNG dengan cara ini:" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat sebuah instance dari kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan slide berdasarkan halaman PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Panggil metode simpan untuk menyimpan slide sebagai gambar PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum Anda menjalankan kode C# konversi PDF ke PNG, mesin Anda harus memiliki prasyarat berikut:

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Platform .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin.
- Lingkungan pengembangan seperti Microsoft Visual Studio.
- Aspose.Slides untuk .NET DLL telah dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode C# untuk mengonversi PDF ke PNG" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation())
    {
        pres.Slides.AddFromPdf("doc.pdf");
        pres.Slides.RemoveAt(0); // removes default empty slide

        for (var index = 0; index < pres.Slides.Count; index++)
        {
            ISlide slide = pres.Slides[index];
            slide.GetThumbnail(new Size(960, 720)).Save($"image-{index}.png");
        }
    }
```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->
    
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Aspose.Slides mendukung operasi konversi untuk banyak format file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-png/" name="PPT TO PNG" description="PNG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Paper Specifications" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}