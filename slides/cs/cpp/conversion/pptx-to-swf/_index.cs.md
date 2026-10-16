---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPTX na SWF pomocí aplikace C++
url: /cs/cpp/conversion/pptx-to-swf/ 
description: Ukázka převodního kódu C++ pro dokument PPTX do formátu SWF. Použijte ukázkový kód pro dávkový převod PPTX na SWF v jakékoli aplikaci C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převést PPTX na SWF přes C++" h2="Vysoce výkonný převod PPTX do SWF pomocí knihovny C++ bez nutnosti instalace Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak převést PPTX na SWF pomocí C++" %}}

Abychom převedli PPTX na SWF, použijeme rozhraní <a href="https://products.aspose.com/slides/cs/cpp">Aspose.Slides for C++</a> API, které je bohaté na funkce a výkonné a snadno použitelné rozhraní API pro manipulaci a konverzi dokumentů pro platformu C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít správce balíčků <a href="https://www.nuget.org/packages/aspose.slides">NuGet</a> a vyhledat <b>Aspose.Slides.Cpp </b> a nainstalujte. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Zdrojový kód konverze PPTX do SWF C++" >}}
```cs
// Load the PPTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pptx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky k převodu PPTX na SWF přes C++" intro="Aspose.SLIDES API usnadňuje vývojářům převod PPTX souboru na SWF v pouhých několika řádcích kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX pomocí Aspose.Slides pro C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu Save().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Předejte cestu výstupního souboru s příponou (SWF).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor SWF bude uložen do zadané cesty.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor SWF v kompatibilním programu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Aspose.SLIDES pro C++ podporuje na všech hlavních platformách a operačních systémech. Ujistěte se prosím, že máte následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
- Aspose.Slides pro C++ DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu PPTX na SWF"
  description="[Vyzkoušejte zdarma Video App](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést PPTX do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
