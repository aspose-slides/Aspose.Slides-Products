---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera POTX till GIF via C++-applikation
weight: 5600
url: /sv/cpp/conversion/potx-to-gif/ 
description: Exempel på C++-konverteringskod för POTX-dokument till GIF-format. Använd exempelkod för batch-POTX till GIF-konvertering inom valfri C++-applikation.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera POTX till GIF via C++" h2="Högpresterande POTX till GIF-konvertering med C++-bibliotek utan behov av Microsoft PowerPoint-installation."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hur man konverterar POTX till GIF med C++" %}}

För att konvertera POTX till GIF kommer vi att använda
 [Aspose.Slides för C++](https://products.aspose.com/slides/cpp/)
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTX till GIF C++ Källkod för konvertering" >}}
```cs
// Load the POTX
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.potx");

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

bitmap->Save(u"output.gif", ImageFormat::get_Gif());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steg för att konvertera POTX till GIF via C++" intro="C++-utvecklare kan enkelt konvertera POTX-fil till GIF på bara några rader kod." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda POTX-fil med Aspose.Slides för C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Välj den första bilden.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ställ in önskade mått.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skaffa miniatyrbilden med önskade mått.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa metoden Save() med GIF-utgångsparameter .{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna GIF-filen i ett kompatibelt program.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systemkrav" intro="Innan du kör C++-konverteringsexempelkoden, se till att du har följande förutsättningar." %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32 bit, Windows 64 bit och Linux 64 bit.
- Aspose.Slides för C++ DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis app att konvertera POTX till GIF"
  description="[Prova vår gratis MP4 To MP3 -app](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera POTX till många andra filformat, inklusive några som anges nedan." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-bmp/" name="POTX TO BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-emf/" name="POTX TO EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-html/" name="POTX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pdf/" name="POTX TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-png/" name="POTX TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pot/" name="POTX TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-potm/" name="POTX TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pps/" name="POTX TO PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-svg/" name="POTX TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-xml/" name="POTX TO XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-xps/" name="POTX TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
