---
title: Zobrazit nebo upravit metadata souborů OTP přes .NET
weight: 6590
url: /cs/net/metadata/otp/ 
description: Zdrojový kód C# pro úpravu nebo zobrazení metadat formátu OTP na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Extrahujte metadata OTP přes .NET" h2="Sestavte si své vlastní aplikace .NET pro přidání, úpravu, odstranění nebo extrahování metadat ze souborů OTP pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak extrahovat OTP metadata pomocí C#" %}}

 Abychom extrahovali metadata OTP, použijeme
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
 API, což je funkčně bohaté, výkonné a snadno použitelné API metadat dokumentu pro platformu C#. OTEVŘENO
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 správce balíčků, vyhledejte
 **Aspose.Slides**
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Kroky k extrahování metadat OTP přes C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Třída IDocumentProperties představuje vlastnosti dokumentu přidružené k souboru prezentace. Vývojáři mohou tuto vlastnost použít k přístupu k metadatům, jak je popsáno níže." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation s cestou k souboru OTP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Získejte objekt DocumentProperties spojený s Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Opakujte položky v objektu DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přístup a úpravy uživatelských vlastností
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for .NET je podporován na všech hlavních operačních systémech. Jen se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
- Vývojové prostředí jako Microsoft Visual Studio.
- Aspose.Slides pro .NET odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrahovat metadata jednorázového hesla – C#" offSpacer="" %}}

```cs

// instantiate the Presentation class with path to OTP file
var presentation = new Aspose.Slides.Presentation("template.otp");

// get DocumentProperties object associated with the Presentation object
var properties = presentation.DocumentProperties;

// access and modify custom properties
for (int i = 0; i < properties.CountOfCustomProperties; i++)
{
    // display names and values of custom properties
    System.Console.WriteLine("Custom Property Name : " + properties.GetCustomPropertyName(i));
    System.Console.WriteLine("Custom Property Value : " + properties[properties.GetCustomPropertyName(i)]);

    // modify values of custom properties
    properties[properties.GetCustomPropertyName(i)] = "New Value " + (i + 1);
}

// save your presentation to a file
presentation.Save("output.otp", Aspose.Slides.Export.SaveFormat.Otp);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Slides for .NET API" %}}

 Aspose.Slides API lze použít ke čtení, zápisu, manipulaci a převodu dokumentů Microsoft PowerPoint do PDF, XPS, HTML, TIFF, ODP a různých dalších formátů. Je možné vytvářet nové soubory od začátku a ukládat je v příslušných podporovaných formátech. Aspose.Slides je samostatné API pro vytváření, analýzu nebo manipulaci s prezentacemi, snímky a prvky a nezávisí na žádném softwaru, jako je Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of OTP via Online App" sectionDescription="View & edit Metadata to OTP documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your OTP file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" >}}
Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty metadat" subTitle="Pomocí C# lze také manipulovat s metadaty mnoha dalších formátů včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/odp/" name="ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/pot/" name="POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/potm/" name="POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/potx/" name="POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/pps/" name="PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/ppsm/" name="PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/ppsx/" name="PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/pptm/" name="PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/metadata/pptx/" name="PPTX" description="Formát otevřené prezentace XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}