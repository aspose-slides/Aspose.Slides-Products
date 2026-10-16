---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPSX till JPEG via C++-applikation
weight: 1750
url: /sv/cpp/conversion/ppsx-to-jpeg/ 
description: Exempel på C++-konverteringskod för PPSX-dokument till JPEG-format. Använd exempelkod för batchkonvertering av PPSX till JPEG inom valfri C++-applikation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPSX till JPEG via C++" h2="Högpresterande PPSX till JPEG-konvertering med C++-bibliotek utan behov av Microsoft PowerPoint-installation."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hur man konverterar PPSX till JPEG med C++" %}}

För att konvertera PPSX till JPEG kommer vi att använda
 [Aspose.Slides för C++](https://products.aspose.com/slides/sv/cpp/)
 API som är ett funktionsrikt, kraftfullt och lättanvänt API för dokumentmanipulering och konvertering för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 pakethanterare, sök efter
 Aspose.Slides.Cpp
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Kommando" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX till JPEG C++ källkod för konvertering" >}}
```cs
// Load the PPSX
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppsx");

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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steg för att konvertera PPSX till JPEG via C++" intro="C++-utvecklare kan enkelt konvertera PPSX-fil till JPEG på bara några rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda PPSX-fil med Aspose.Slides för C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Välj den första bilden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ställ in önskade mått.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skaffa miniatyrbilden med önskade mått.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden Save() med JPEG-utgångsparameter .{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna JPEG-filen i ett kompatibelt program.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör C++-konverteringsexempelkoden, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32 bit, Windows 64 bit och Linux 64 bit.
- Aspose.Slides för C++ DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app att konvertera PPSX till JPEG"
  description="[Prova vår gratis app att konvertera PPT till JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPSX till många andra filformat, inklusive några som anges nedan." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
