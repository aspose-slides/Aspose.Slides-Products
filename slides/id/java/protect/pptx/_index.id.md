---
title: Lindungi File Presentasi PPTX menggunakan Java
url: /id/java/protect/pptx/
keywords: Perlindungan Tulis PPTX, Enkripsi PPTX, Kunci Presentasi PPTX, Lindungi PPTX
description: kode sumber Java untuk melindungi Presentasi PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Kunci atau Proteksi Kata Sandi PPTX menggunakan Java" h2="Bangun aplikasi Java Anda sendiri untuk melindungi file presentasi menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Melindungi Presentasi PPTX melalui Java" %}}
Dengan menggunakan Aspose.Slides for Java, Anda dapat melindungi presentasi PPTX dari pembukaan atau modifikasi dengan menyetel sandi. Kemudian, untuk membuka atau memodifikasi presentasi yang dikunci, pengguna harus memberikan kata sandi.
{{% blocks/products/pf/agp/code-block title="Mengenkripsi Presentasi PPTX menggunakan Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Menyetel Write Protection ke Presentasi PPTX menggunakan Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Melindungi Kata Sandi PPTX melalui Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk Melindungi file PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPTX dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lindungi presentasi menggunakan kelas ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Perlindungan Lain yang Didukung" subTitle="Menggunakan Java, Anda juga dapat memproteksi format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}