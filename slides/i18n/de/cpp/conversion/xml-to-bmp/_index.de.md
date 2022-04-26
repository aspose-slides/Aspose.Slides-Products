---
title: Konvertieren Sie XML in BMP über eine C++-Anwendung
weight: 3180
url: /de/cpp/conversion/xml-to-bmp/ 
description: Beispiel-C++-Konvertierungscode für ein XML-Dokument in das BMP-Format. Verwenden Sie Beispielcode für die Batch-Konvertierung von XML in BMP innerhalb einer beliebigen C++-Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie XML über C++ in BMP" h2="Leistungsstarke XML-zu-BMP-Konvertierung unter Verwendung der C++-Bibliothek ohne die Notwendigkeit einer Microsoft PowerPoint-Installation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie XML in BMP mit C++" %}}

 Um XML in BMP zu konvertieren, verwenden wir
 [Aspose.Folien für C++](https://products.aspose.com/slides/cpp)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende API zur Dokumentenbearbeitung und -konvertierung für die C++-Plattform ist. Sie können die neueste Version direkt herunterladen, einfach öffnen
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 Paketmanager, suche nach
 Aspose.Slides.Cpp
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Befehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von XML in BMP über C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-Entwickler können XML-Dateien in nur wenigen Codezeilen problemlos in BMP konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. XML-Datei mit Aspose.Slides für C++-Präsentationsobjekt laden.
1. Wählen Sie die erste Folie aus.
1. Stellen Sie die gewünschten Abmessungen ein.
1. Holen Sie sich das Miniaturbild mit den gewünschten Abmessungen.
1. Rufen Sie die Save()-Methode mit dem BMP-Ausgabeparameter auf.
1. Öffnen Sie die BMP-Datei in einem kompatiblen Programm.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Beispielcodes für die C++-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
- Aspose.Slides für C++-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XML-zu-BMP-C++-Konvertierungsquellcode" offSpacer="" %}}

```cs
// Load the XML
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.xml");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="xml-to-bmp"
        sectionTitle="Kostenlose App, um XML in BMP zu konvertieren" 
        sectionDescription="[Probieren Sie unsere kostenlose Video App aus](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können XML auch in viele andere Dateiformate konvertieren, einschließlich der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-emf/" name="XML TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-gif/" name="XML TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-html/" name="XML TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-jpeg/" name="XML TO JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-odp/" name="XML TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-otp/" name="XML TO OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-pdf/" name="XML TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-png/" name="XML TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-pot/" name="XML TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-potm/" name="XML TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-potx/" name="XML TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-pps/" name="XML TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-ppsm/" name="XML TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-ppsx/" name="XML TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-ppt/" name="XML TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-pptm/" name="XML TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-pptx/" name="XML TO PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-svg/" name="XML TO SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-tiff/" name="XML TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/xml-to-xps/" name="XML TO XPS" description="XML-Papierspezifikationen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}