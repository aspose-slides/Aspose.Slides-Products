---
title: Konversi PPS ke GIF melalui C#
weight: 4000
url: /id/net/conversion/pps-to-gif/ 
description: Contoh kode untuk konversi PPS ke GIF C#. Gunakan kode contoh API untuk file batch PPS ke konversi GIF dalam VB.NET, Asp.NET atau aplikasi berbasis .NET apa pun.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi PPS ke GIF melalui C#" h2="Ekspor file PowerPoint® PPS ke GIF di .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi PPS ke GIF Menggunakan C#" %}}

 Untuk mengonversi PPS ke GIF, kami akan menggunakan
 [Aspose.Slides untuk .NET](https://products.aspose.com/slides/id/net)
 API yang kaya fitur, kuat, dan mudah digunakan untuk manipulasi dokumen dan API konversi untuk platform C#. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 manajer paket, cari
 Aspose.Slide
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi PPS ke GIF melalui C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Pengembang .NET dapat dengan mudah memuat & mengonversi file PPS ke GIF hanya dalam beberapa baris kode." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file PPS dengan instance kelas Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi setiap Slide dalam Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat gambar skala penuh sebagai Bitmap dengan setiap iterasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Panggil metode Bitmap.Save dengan ekstensi file GIF & ImageFormat.Gif sebagai parameter
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan kode sumber sampel konversi .NET, pastikan Anda memiliki prasyarat berikut ini.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Platform .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin.
- Lingkungan pengembangan seperti Microsoft Visual Studio.
- Aspose.Slides untuk .NET DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode contoh ini menunjukkan Konversi PPS ke GIF C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pps"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Aplikasi gratis untuk mengonversi PPS ke GIF" 
        sectionDescription="[Coba aplikasi Editor gratis kami](https://products.aspose.app/slides/editor/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPS ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-bmp/" name="PPS TO BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-emf/" name="PPS TO EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-html/" name="PPS TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-odp/" name="PPS TO ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-otp/" name="PPS TO OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-pdf/" name="PPS TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-png/" name="PPS TO PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-pot/" name="PPS TO POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-potm/" name="PPS TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-potx/" name="PPS TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Buka Format presentasi XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-svg/" name="PPS TO SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-swf/" name="PPS TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/pps-to-xps/" name="PPS TO XPS" description="Spesifikasi Kertas XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}