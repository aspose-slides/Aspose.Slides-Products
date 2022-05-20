---
title: Konvertieren Sie PPT über eine C++-Anwendung in JPEG
weight: 3530
url: /de/cpp/conversion/ppt-to-jpeg/ 
description: Beispiel-C++-Konvertierungscode für ein PPT-Dokument in das JPEG-Format. Verwenden Sie Beispielcode für die Stapelkonvertierung von PPT in JPEG in einer beliebigen C++-Anwendung.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie PPT über C++ in JPEG" h2="Leistungsstarke PPT-zu-JPEG-Konvertierung mithilfe der C++-Bibliothek ohne die Notwendigkeit einer Microsoft PowerPoint-Installation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie PPT in JPEG mit C++" %}}

 Um PPT in JPEG zu konvertieren, verwenden wir
 [Aspose.Folien für C++](https://products.aspose.com/slides/de/cpp)
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von PPT in JPEG über C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-Entwickler können PPT-Dateien in nur wenigen Codezeilen problemlos in JPEG konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die PPT-Datei mit Aspose.Slides für C++-Präsentationsobjekt.
1. Wählen Sie die erste Folie aus.
1. Stellen Sie die gewünschten Abmessungen ein.
1. Holen Sie sich das Miniaturbild mit den gewünschten Abmessungen.
1. Rufen Sie die Save()-Methode mit dem JPEG-Ausgabeparameter auf.
1. Öffnen Sie die JPEG-Datei in einem kompatiblen Programm.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Beispielcodes für die C++-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
- Aspose.Slides für C++-DLL, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPT-zu-JPEG-C++-Konvertierungsquellcode" offSpacer="" %}}

```cs
// Load the PPT
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppt");

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

bitmap->Save(u"output.jpeg", ImageFormat::get_Jpeg());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Kostenlose App, um PPT in JPEG zu konvertieren" 
        sectionDescription="[Versuchen Sie unsere kostenlose App, um PPT in JPG konvertieren zu können](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können PPT auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-html/" name="PPT TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument-Standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-png/" name="PPT TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-xml/" name="PPT TO XML" description="Erweiterbare Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML-Papierspezifikationen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}