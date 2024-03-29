---
title: Konversi PPSX ke SVG melalui C#
weight: 1930
url: /id/net/conversion/ppsx-to-svg/ 
description: Contoh kode untuk konversi PPSX ke SVG C#. Gunakan kode contoh API untuk file PPSX batch ke konversi SVG dalam VB.NET, Asp.NET atau aplikasi berbasis .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi PPSX ke SVG melalui C#" h2="Ekspor file PowerPoint® PPSX ke SVG di .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi PPSX ke SVG Menggunakan C#" %}}

 Untuk mengonversi PPSX ke SVG, kami akan menggunakan
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


{{< blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi PPSX ke SVG melalui C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Pengembang .NET dapat dengan mudah memuat & mengonversi file PPSX ke SVG hanya dalam beberapa baris kode." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file PPSX dengan instance kelas Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Panggil metode Simpan sambil menentukan jalur file keluaran & SaveFormat.Svg sebagai parameter
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
File SVG akan disimpan di jalur yang ditentukan
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

{{% blocks/products/pf/agp/code-block title="Kode contoh ini menunjukkan Konversi PPSX ke SVG C#" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("template.ppsx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];

        using (FileStream fileStream = new FileStream($"slide-{index}.svg", FileMode.Create, FileAccess.Write))
        {
            slide.WriteAsSvg(fileStream);   
        }
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
        sectionTitle="Aplikasi gratis untuk mengonversi PPSX ke SVG" 
        sectionDescription="[Coba aplikasi Video gratis kami](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPSX ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Buka Format presentasi XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Spesifikasi Kertas XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}