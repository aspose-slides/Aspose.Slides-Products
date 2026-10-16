---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPS till ODP via Java
weight: 180
url: /sv/java/conversion/pps-to-odp/ 
description: Exempel på Java-konverteringskod för PPS-format till ODP-fil. Använd den här exempelkoden för att exportera PowerPoint- och OpenOffice-presentationer till ODP inom alla Java-baserade webb- eller skrivbordsapplikationer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPS till ODP via Java" h2="PPS till ODP Java-konvertering för att konvertera enstaka eller flera sidor till ODP med hjälp av On-premise Java-bibliotek."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hur man konverterar PPS till ODP med Java" %}}

För att rendera PPS till ODP kommer vi att använda
 [Aspose.Slides för Java](https://products.aspose.com/slides/sv/java/)
 API som är ett funktionsrikt, kraftfullt och lättanvänt konverterings-API för Java-plattformen. Du kan ladda ner den senaste versionen direkt från
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Förvar" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Beroende" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPS till ODP Java-konvertering källkod" >}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("template.pps");
// save the presentation as ODP
presentation.save("output.odp", SaveFormat.Odp);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steg för att konvertera PPS till ODP via Java" intro="Java-utvecklare kan enkelt konvertera PPS-fil till ODP på ​​bara några rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PPS-fil med en instans av klassen Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden Presentation.save medan du anger sökvägen till utdatafilen och SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP-filen kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör exempelkoden för Java-konvertering, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.
- Hämta senaste versionen av Aspose.Slides för Java direkt från Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app att konvertera PPS till ODP"
  description="[Prova vår gratis Editor -app](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPS till många andra filformat inklusive några som anges nedan." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-gif/" name="PPS TO GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-html/" name="PPS TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-pdf/" name="PPS TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-png/" name="PPS TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-potm/" name="PPS TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-potx/" name="PPS TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-svg/" name="PPS TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF-format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/pps-to-xps/" name="PPS TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
