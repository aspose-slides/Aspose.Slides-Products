---
title: Konvertieren Sie PPTX über C# in JPEG
weight: 480
url: /de/net/conversion/pptx-to-jpeg/ 
description: Beispielcode für die Umwandlung von PPTX in JPEG C#. Verwenden Sie den API-Beispielcode für die Batch-Konvertierung von PPTX-Dateien in JPEG innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie PPTX über C# in JPEG" h2="Exportieren Sie PowerPoint® PPTX-Dateien in JPEG auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie PPTX in JPEG mit C#" %}}

 Um PPTX in JPEG zu konvertieren, verwenden wir
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


{{< blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von PPTX in JPEG über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET-Entwickler können PPTX-Dateien in nur wenigen Codezeilen einfach laden und in JPEG konvertieren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die PPTX-Datei mit einer Instanz der Präsentationsklasse
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

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die Umwandlung von PPTX in JPEG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pptx"))
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
        sectionTitle="Kostenlose App, um PPTX in JPEG zu konvertieren" 
        sectionDescription="[Versuchen Sie unsere kostenlose App, um PPT in JPG konvertieren zu können](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können PPTX auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML-Papierspezifikationen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}