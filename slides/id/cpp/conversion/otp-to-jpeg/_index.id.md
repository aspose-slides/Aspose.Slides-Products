---
title: Konversi OTP ke JPEG melalui aplikasi C++
weight: 4520
url: /id/cpp/conversion/otp-to-jpeg/ 
description: Contoh kode konversi C++ untuk dokumen OTP ke format JPEG. Gunakan kode contoh untuk konversi batch OTP ke JPEG dalam Aplikasi C++ apa pun.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi OTP ke JPEG melalui C++" h2="Konversi OTP ke JPEG berkinerja tinggi menggunakan pustaka C++ tanpa perlu instalasi Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OTP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi OTP ke JPEG Menggunakan C++" %}}

 Untuk mengonversi OTP ke JPEG, kami akan menggunakan
 [Aspose.Slides untuk C++](https://products.aspose.com/slides/cpp/)
 API yang kaya fitur, kuat, dan mudah digunakan untuk manipulasi dokumen dan API konversi untuk platform C++. Bisa langsung download versi terbarunya, tinggal buka
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 manajer paket, cari
 Aspose.Slides.Cpp
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi OTP ke JPEG melalui C++" %}}

{{% blocks/products/pf/agp/text %}}

 Pengembang C++ dapat dengan mudah mengonversi file OTP ke JPEG hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file OTP dengan Aspose.Slides untuk Objek Presentasi C++.
1. Pilih slide pertama.
1. Atur dimensi yang diinginkan.
1. Dapatkan thumbnail dengan dimensi yang diinginkan.
1. Panggil metode Save() yang memiliki parameter output JPEG.
1. Buka file JPEG di program yang kompatibel.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan kode contoh konversi C++, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit dan Linux 64 bit.
- Aspose.Slides untuk C++ DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode Sumber Konversi OTP ke JPEG C++" offSpacer="" %}}

```cs
// Load the OTP
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.otp");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.jpeg", ImageFormat::get_Jpeg());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Aplikasi gratis untuk mengonversi OTP ke JPEG" 
        sectionDescription="[Coba aplikasi gratis kami untuk mengonversi PPT ke JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi OTP ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-bmp/" name="OTP TO BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-emf/" name="OTP TO EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-gif/" name="OTP TO GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-html/" name="OTP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-odp/" name="OTP TO ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pdf/" name="OTP TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-png/" name="OTP TO PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pot/" name="OTP TO POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-potm/" name="OTP TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-potx/" name="OTP TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pps/" name="OTP TO PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pptm/" name="OTP TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Buka Format presentasi XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-svg/" name="OTP TO SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-xml/" name="OTP TO XML" description="Bahasa Markup yang Dapat Diperluas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-xps/" name="OTP TO XPS" description="Spesifikasi Kertas XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}