---
title: Ekstrak teks dan gambar dari dokumen ODP melalui C++
weight: 460
url: /id/cpp/parser/odp/ 
description: Contoh kode C++ untuk mengekstrak teks dan gambar dari file ODP di C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit dan Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Mengurai Format ODP di C++" h2="Penguraian dokumen ODP asli dan berkinerja tinggi menggunakan Aspose.Slides sisi server untuk API C++, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides.cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Parsing File ODP Menggunakan C++" %}}

 Untuk mengurai file ODP, kami akan menggunakan
 [Aspose.Slides untuk C++](https://products.aspose.com/slides/id/cpp/)
 API yang merupakan API parsing dokumen yang kaya fitur, kuat, dan mudah digunakan untuk platform C++. Bisa langsung download versi terbarunya, tinggal buka
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 manajer paket, cari
 **Aspose.Slides.Cpp**
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Langkah-langkah Parsing File ODP di C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Penguraian dokumen dasar dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/) API dapat dilakukan hanya dengan beberapa baris kode." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file ODP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dapatkan Array objek ITextFrame dari slide pertama.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi Array dari TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi paragraf di ITextFrame saat ini.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi bagian-bagian dalam IParagraph saat ini.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Menampilkan teks.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides untuk C++ mendukung pada semua platform utama dan Sistem Operasi. Harap pastikan bahwa Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit dan Linux 64 bit.
- Aspose.Slides untuk C++ DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Parsing File ODP - C++" offSpacer="" %}}

```cs
// Sample file path
const String sourceFilePath = u"SourcePath\sourceFile.odp";

// Load the ODP file
SharedPtr<Presentation> presentation = MakeObject<Presentation>(sourceFilePath);

// Get an Array of ITextFrame objects from the first slide
System::ArrayPtr<SharedPtr<ITextFrame>> textFramesSlideOne = SlideUtil::GetAllTextBoxes(presentation->get_Slides()->idx_get(0));

// Loop through the Array of TextFrames
for (int i = 0; i get_Length(); i++){
	// Loop through paragraphs in current ITextFrame
	for (SharedPtr<IParagraph> paragraph : textFramesSlideOne[i]->get_Paragraphs()){
		// Loop through portions in the current IParagraph
		for (SharedPtr<IPortion> portion : paragraph->get_Portions()){
			// Display text
			Console::WriteLine(portion->get_Text());
		}
	}
}  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Tentang Aspose.Slides untuk C++ API" %}}

 Aspose.Slides API dapat digunakan untuk membaca, menulis, memanipulasi, dan mengonversi dokumen Microsoft PowerPoint ke PDF, XPS, HTML, TIFF, ODP, dan berbagai format lainnya. Seseorang dapat membuat file baru dari awal dan menyimpannya dalam format yang didukung yang relevan. Aspose.Slides adalah API mandiri untuk membuat, mengurai, atau memanipulasi presentasi, slide, dan elemen dan tidak bergantung pada perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Parser Live Demos" sectionDescription="Extract text and images from ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Dokumen Parsing yang Didukung Lainnya" subTitle="Menggunakan C++, seseorang dapat dengan mudah mengurai format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/parser/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/parser/pptx/" name="PPTX" description="Buka Format presentasi XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}