---
title: Lihat atau Edit Metadata File PPTM menggunakan C++
url: /id/cpp/metadata/pptm/
keywords: Edit Metadata PPTM, Lihat Metadata PPTM, Edit properti PPTM, Lihat properti PPTM
description: kode sumber C++ untuk mengedit atau melihat metadata format PPTM.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edit properti PPTM menggunakan C++" h2="Bangun aplikasi C++ Anda sendiri untuk mengubah properti Bawaan dan Kustom dalam file presentasi menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTM" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Properti PPTM melalui C++" %}}
Dengan menggunakan Aspose.Slides for C++, developer dapat mengakses dan mengubah nilai properti bawaan serta properti kustom. Pengembang dapat menggunakan properti [DocumentProperties](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) yang diekspos oleh objek Presentasi untuk mengakses properti dokumen dari file presentasi.
{{% blocks/products/pf/agp/code-block title="Modifikasi PPTM Properti Bawaan - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class that represents the Presentation
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"presentation.pptm");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

// Set the builtin properties
documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptm", SaveFormat::Pptm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Tambahkan Properti Kustom ke PPTM - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class
auto presentation = System::MakeObject<Presentation>();

// Getting Document Properties
auto documentProperties = presentation->get_DocumentProperties();

// Adding Custom properties
documentProperties->idx_set(u"New Custom", ObjectExt::Box<int32_t>(12));
documentProperties->idx_set(u"My Name", ObjectExt::Box<String>(u"Aspose Metadata Editor"));
documentProperties->idx_set(u"Custom", ObjectExt::Box<int32_t>(124));

// Getting property name at particular index
String getPropertyName = documentProperties->GetCustomPropertyName(2);

// Removing selected property
documentProperties->RemoveCustomProperty(getPropertyName);

// Saving presentation
presentation->Save(u"CustomDocumentProperties_out.pptm", SaveFormat::Pptm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Mengekstrak Metadata PPTM melalui C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk Mengekstrak Metadata dari file PPTM." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat instance kelas Presentasi dengan jalur ke file PPTM
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dapatkan objek DocumentProperties yang terkait dengan Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi item dalam objek DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Akses dan ubah properti khusus
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Metadata Lain yang Didukung" subTitle="Menggunakan C++, Anda juga dapat memanipulasi metadata dari banyak format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}