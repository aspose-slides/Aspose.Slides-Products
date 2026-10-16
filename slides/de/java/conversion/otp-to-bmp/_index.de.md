---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie OTP über Java in BMP
weight: 6880
url: /de/java/conversion/otp-to-bmp/ 
description: Beispiel-Java-Konvertierungscode für das OTP-Format in eine BMP-Datei. Verwenden Sie diesen Beispielcode, um PowerPoint- und OpenOffice-Präsentationen in BMP innerhalb einer beliebigen Web- oder Desktop-Java-basierten Anwendung zu exportieren.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie OTP über Java in BMP" h2="OTP-zu-BMP-Java-Konvertierung zum Konvertieren einzelner oder mehrerer Seiten in BMP mithilfe der lokalen Java-Bibliothek."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="So konvertieren Sie OTP in BMP mit Java" %}}

Um OTP in BMP zu rendern, verwenden wir
 [Aspose.Folien für Java](https://products.aspose.com/slides/de/java/)
 API, die eine funktionsreiche, leistungsstarke und einfach zu verwendende Konvertierungs-API für die Java-Plattform ist. Sie können die neueste Version direkt von herunterladen
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 und installieren Sie es in Ihrem Maven-basierten Projekt, indem Sie der pom.xml die folgenden Konfigurationen hinzufügen.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repository" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Abhängigkeit" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP-zu-BMP-Java-Konvertierungsquellcode" >}}
```cs
// load OTP with Aspose.Slides
Presentation presentation = new Presentation("template.otp");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type BMP for every slide
  File outputfile = new File(sld.getSlideNumber() + ".bmp");
  
  // save the slide image to disk
  ImageIO.write(bi, "bmp", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Schritte zum Konvertieren von OTP in BMP über Java" intro="Java-Entwickler können OTP-Dateien in nur wenigen Codezeilen problemlos in BMP konvertieren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die OTP-Datei mit einer Instanz der Präsentationsklasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Durchlaufen Sie jede Folie in der Präsentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie bei jeder Iteration ein Bild in voller Größe als Bitmap{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Bitmap.save-Methode mit BMP-Dateierweiterung und ImageFormat auf{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielcodes für die Java-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Runtime Environment für JSP/JSF-Anwendung und Desktop-Anwendungen.
- Holen Sie sich die neueste Version von Aspose.Slides für Java direkt von Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenlose App, um OTP in BMP zu konvertieren"
  description="[Versuchen Sie unsere kostenlose App, um PPT in BMP konvertieren zu können](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können OTP auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-gif/" name="OTP TO GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-html/" name="OTP TO HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-jpeg/" name="OTP TO JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-png/" name="OTP TO PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Makrofähige Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint-Diashow" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Makrofähige Präsentationsdatei" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Offenes XML-Präsentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-svg/" name="OTP TO SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF-Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/otp-to-xps/" name="OTP TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
