---
title: Konwertuj PNG na SVG w C#
weight: 240
url: /pl/net/conversion/png-to-svg/ 
keywords: PNG do SVG, konwertuj PNG do SVG, C# API, biblioteka .NET
description: Konwertuj PNG na SVG w C#. Użyj interfejsu API biblioteki .NET, aby przekonwertować pliki PNG na SVG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konwertuj PNG na SVG w C#" h2="PowerPoint .NET API do konwertowania plików PNG do SVG na platformach NET Framework, .NET Core, Windows Azure, Mono lub Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="jpg" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}


{{% blocks/products/pf/agp/content h2="Konwertuj PNG na SVG w C#" %}}

Jak przekonwertować PNG do SVG w kodzie?

Używając [**Aspose.Slides for .NET**](https://products.aspose.com/slides/pl/net/), każdy programista lub aplikacja może przekonwertować PNG na SVG za pomocą zaledwie kilku wierszy kodu C#.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides for .NET szybko eksportuje pliki PNG do SVG. Biblioteka Aspose PowerPoint umożliwia konwersję PNG do SVG i obrazów w innych formatach.

Aby zainstalować Aspose.Slides: Otwórz menedżera pakietów [NuGet](https://www.nuget.org/packages/aspose.slides.net). Wyszukaj Aspose.Slides i zainstaluj go.
 
Możesz też zainstalować **Aspose.Slides**, uruchamiając to polecenie z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Jak przekonwertować PNG do SVG w C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Programiści i aplikacje mogą konwertować PNG do SVG w ten sposób:" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz wystąpienie klasy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj obraz PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj ramkę do zdjęć.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz plik jako obraz SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu C# konwersji PNG do SVG Twój komputer musi mieć następujące wymagania wstępne:

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z platformami .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
- Środowisko programistyczne, takie jak Microsoft Visual Studio.
- W projekcie odniesiono się do Aspose.Slides dla .NET DLL.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod C# do konwersji PNG do SVG" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation())
    {
        IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
        pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

        using (FileStream stream = new FileStream($"doc.svg", FileMode.Create, FileAccess.Write))
        {
            pres.Slides[0].WriteAsSvg(stream);
        }
    }
```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->
    
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Aspose.Slides obsługuje operacje konwersji dla wielu formatów plików" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Open XML presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML Paper Specifications" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}