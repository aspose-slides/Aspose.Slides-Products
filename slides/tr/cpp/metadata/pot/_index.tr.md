---
title: C++ ile POT Belge Meta Verilerini Düzenleme veya Görüntüleme
weight: 5800
url: /tr/cpp/metadata/pot/ 
description: Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment'da POT dosya meta verilerini düzenlemek veya görüntülemek için C++ örnek kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="POT Meta Verilerini C++ ile Çıkarın" h2="Sunucu tarafı API'lerini kullanarak POT dosyalarına meta veri eklemek, düzenlemek, kaldırmak veya çıkarmak için kendi C++ uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak POT Meta Verileri Nasıl Elde Edilir" %}}

 POT meta verilerini çıkarmak için kullanacağız
 [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp)
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge meta veri çıkarma API'si olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 paket yöneticisi, ara
 **Aspose.Slides.Cpp**
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C++ ile POT Meta Verilerini Çıkarma Adımları" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="IDocumentProperties sınıfı, bir sunum dosyasıyla ilişkili belge özelliklerini temsil eder. Geliştiriciler, aşağıda açıklandığı gibi meta verilere erişmek için bu özelliği kullanabilir." >}}

{{< blocks/products/pf/agp/step-autogen >}}
POT dosyasını yükle
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
get\_DocumentProperties() kullanarak Belge Özelliklerini Alın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
döngü kullanarak tüm özellikler için yineleme
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Her yinelemede özellikleri yazdırın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C++ tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.
- Projenizde referans verilen C++ DLL için Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POT'un Meta Verilerini Çıkarın - C++" offSpacer="" %}}

```cs

const String templatePath = u"../templates/AccessModifyingProperties.pot";

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(templatePath);

// Create a reference to DocumentProperties object associated with Prsentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

for (int32_t i = 0; i get_CountOfCustomProperties(); i++){
	System::Console::WriteLine(u"Custom Property Name : {0}", documentProperties->GetCustomPropertyName(i));
	System::Console::WriteLine(u"Custom Property Vlaue : {0}", documentProperties->idx_get(documentProperties->GetCustomPropertyName(i)));
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides for C++ API Hakkında" %}}

 Aspose.Slides API, Microsoft PowerPoint belgelerini okumak, yazmak, değiştirmek ve PDF, XPS, HTML, TIFF, ODP ve diğer çeşitli formatlara dönüştürmek için kullanılabilir. Sıfırdan yeni dosyalar oluşturabilir ve bunları ilgili desteklenen biçimlerde kaydedebilirsiniz. Aspose.Slides, sunumlar, slaytlar ve öğeler oluşturmak, ayrıştırmak veya değiştirmek için bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılıma bağlı değildir.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of POT via Online App" sectionDescription="View & edit Metadata to POT documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POT file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" >}}
Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. The files, hence, generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Meta Veri Formatları" subTitle="C++ kullanarak, One ayrıca aşağıdakiler de dahil olmak üzere birçok başka biçimin meta verilerini işleyebilir:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/odp/" name="ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/otp/" name="OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/potm/" name="POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/potx/" name="POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/pps/" name="PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/ppsm/" name="PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/ppsx/" name="PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/pptm/" name="PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/metadata/pptx/" name="PPTX" description="Açık XML sunum Formatı" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}