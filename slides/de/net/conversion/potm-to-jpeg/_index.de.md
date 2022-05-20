---
title: Konvertieren Sie POTM über C# in JPEG
weight: 6160
url: /de/net/conversion/potm-to-jpeg/ 
description: Beispielcode für die Umwandlung von POTM in JPEG C#. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von POTM-Dateien in JPEG innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie POTM über C# in JPEG" h2="Exportieren Sie PowerPoint®-POTM-Dateien in JPEG auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie POTM mit C# in JPEG" %}}

 Um POTM in JPEG zu konvertieren, verwenden wir
 [Aspose.Slides für .NET](https://products.aspose.com/slides/de/net)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende API zur Dokumentenbearbeitung und -konvertierung für die C#-Plattform ist. Offen
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 Paketmanager, suche nach
 Aspose.Folien
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von POTM in JPEG über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET-Entwickler können POTM-Dateien in nur wenigen Codezeilen einfach laden und in JPEG konvertieren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die POTM-Datei mit einer Instanz der Präsentationsklasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Durchlaufen Sie jede Folie in der Präsentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie bei jeder Iteration ein Bild in voller Größe als Bitmap
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rufen Sie die Bitmap.Save-Methode mit der JPEG-Dateierweiterung und ImageFormat.Jpeg als Parameter auf
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Beispielquellcodes für die .NET-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen.
- Entwicklungsumgebung wie Microsoft Visual Studio.
- Aspose.Slides für .NET-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die POTM-zu-JPEG-C#-Konvertierung" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.potm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
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
        sectionTitle="Kostenlose App, um POTM in JPEG zu konvertieren" 
        sectionDescription="[Versuchen Sie unsere kostenlose App, um PPT in JPG konvertieren zu können](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können POTM auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-emf/" name="POTM TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-gif/" name="POTM TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-html/" name="POTM TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-pdf/" name="POTM TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-png/" name="POTM TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-svg/" name="POTM TO SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/potm-to-xps/" name="POTM TO XPS" description="XML-Papierspezifikationen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}