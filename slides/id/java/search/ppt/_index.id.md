---
title: Cari Teks di File Presentasi PPT menggunakan Java
url: /id/java/search/ppt/
keywords: cari kata dalam PPT, cari dan ganti teks dalam PPT, cari teks PPT Presentasi
description: kode sumber Java untuk mencari teks dalam Presentasi PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Telusuri Teks PPT menggunakan Java" h2="Bangun aplikasi Java Anda sendiri untuk menelusuri dan mengganti teks dalam file presentasi menggunakan API sisi server. Pelajari cara menemukan semua pintu masuk dari kata atau frasa tertentu dalam dokumen presentasi. Cari teks dengan pencocokan data yang tepat dan pencocokan ekspresi reguler." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Cari dan Ganti Teks Presentasi PPT melalui Java" %}}
Pencarian dokumen dasar dan mengganti teks dalam konten, komentar, catatan slide, atau metadata dengan API Aspose.Slides for Java dapat dilakukan hanya dengan beberapa baris kode. Gunakan pencocokan ekspresi reguler, cocokkan huruf besar-kecil untuk mencari teks dalam presentasi. Cari teks dalam judul, konten, footer atau header.
{{% blocks/products/pf/agp/code-block title="Cari teks PPT Presentasi menggunakan Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menelusuri Teks dalam PPT melalui Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mencari file teks PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPT dengan contoh Presentasi.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gunakan metode [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) untuk mencari dan mengganti teks.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Penelusuran PPT Online" sectionDescription="Cari dan ganti teks dalam konten, komentar, atau metadata dalam dokumen PPT sekarang juga." >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Pencarian Lain yang Didukung" subTitle="Menggunakan Java, Anda juga dapat menelusuri teks dalam format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}