---
title: Gabungkan File PPSM melalui Java
weight: 3190
url: /id/java/merger/ppsm/ 
description: Kode sampel Java untuk menggabungkan dokumen PPSM di Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Gabungkan Format PPSM di Java" h2="Penggabungan dokumen PPSM asli menggunakan Java API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Cara Menggabungkan File PPSM Menggunakan Java" %}}

 Untuk menggabungkan file PPSM, kami akan menggunakan
 [Aspose.Slides untuk Java](https://products.aspose.com/slides/java)
 API yang merupakan API penggabungan yang kaya fitur, kuat, dan mudah digunakan untuk platform Java. Anda dapat mengunduh versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Langkah-langkah Menggabungkan File PPSM di Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Penggabungan dan penggabungan dokumen dasar dengan [Aspose.Slides for Java](https://products.aspose.com/slides/java) API dapat dilakukan hanya dengan beberapa baris kode." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file PPSM pertama dengan instance kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat dokumen PPSM kedua dengan instance kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi setiap slide file PPSM kedua.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dengan setiap iterasi, gunakan addClone() untuk menambahkan slide dengan file pertama .
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gunakan metode save() untuk menyimpan di jalur yang ditentukan
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides untuk Java mendukung pada semua platform utama dan Sistem Operasi. Harap pastikan bahwa Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan versi terbaru Aspose.Slides untuk Java langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Gabungkan File PPSM - Java" offSpacer="" %}}

```cs
// Load first PPSM File
Presentation prest1 = new Presentation("prest1.ppsm");

// Load second PPSM File
Presentation prest2 = new Presentation("prest2.ppsm");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.ppsm", SaveFormat.Ppsm);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Slides untuk Java API" %}}

 Aspose.Slides API dapat digunakan untuk membaca, menulis, memanipulasi, dan mengonversi dokumen Microsoft PowerPoint ke PDF, XPS, HTML, TIFF, ODP, dan berbagai format lainnya. Seseorang dapat membuat file baru dari awal dan menyimpannya dalam format yang didukung yang relevan. Aspose.Slides adalah API mandiri untuk membuat, mengurai, atau memanipulasi presentasi, slide, dan elemen dan tidak bergantung pada perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPSM Merger Live Demos" sectionDescription="Merge PPSM documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPSM files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" >}}
Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Penggabungan Lainnya yang Didukung" subTitle="Menggunakan Java, One juga dapat menggabungkan banyak format file lain termasuk.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/odp/" name="ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/otp/" name="OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/pot/" name="POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/potm/" name="POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/potx/" name="POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/pps/" name="PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/ppsx/" name="PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/pptm/" name="PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/merger/pptx/" name="PPTX" description="Buka Format presentasi XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}