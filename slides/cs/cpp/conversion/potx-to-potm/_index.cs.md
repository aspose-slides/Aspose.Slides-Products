---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte POTX na POTM pomocí aplikace C++
weight: 4350
url: /cs/cpp/conversion/potx-to-potm/ 
description: Ukázka převodního kódu C++ pro dokument POTX do formátu POTM. Použijte ukázkový kód pro dávkovou konverzi POTX na POTM v jakékoli aplikaci C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte POTX na POTM přes C++" h2="Vysoce výkonný převod POTX do POTM pomocí knihovny C++ bez nutnosti instalace Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak převést POTX na POTM pomocí C++" %}}

Abychom převedli POTX na POTM, použijeme
 [Aspose.Slides pro C++](https://products.aspose.com/slides/cpp/)
 API, což je funkčně bohaté, výkonné a snadno použitelné rozhraní API pro manipulaci a konverzi dokumentů pro platformu C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 správce balíčků, vyhledejte
 Aspose.Slides.Cpp
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Zdrojový kód konverze POTX na POTM C++" >}}
```cs
// Load the POTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.potx");
// Save in POTM format.
prs->Save(u"convertedFile.potm", Aspose::Slides::Export::SaveFormat::Potm);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky k převodu POTX na POTM přes C++" intro="Vývojáři C++ mohou snadno převést soubor POTX na POTM pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor POTX pomocí Aspose.Slides pro C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu Save().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Předejte cestu výstupního souboru s příponou (POTM).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor POTM bude uložen do zadané cesty.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor POTM v kompatibilním programu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového kódu převodu C++ se ujistěte, že máte následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
- Aspose.Slides pro C++ DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu POTX na POTM"
  description="[Vyzkoušejte zdarma Video App](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést POTX do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-bmp/" name="POTX TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-emf/" name="POTX TO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-gif/" name="POTX TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-html/" name="POTX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-odp/" name="POTX TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-otp/" name="POTX TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pdf/" name="POTX TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-png/" name="POTX TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pot/" name="POTX TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pps/" name="POTX TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-svg/" name="POTX TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-xml/" name="POTX TO XML" description="Rozšiřitelný značkovací jazyk" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/potx-to-xps/" name="POTX TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
