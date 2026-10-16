---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPSM na JPEG pomocí aplikace C++
weight: 8060
url: /cs/cpp/conversion/ppsm-to-jpeg/ 
description: Ukázka převodního kódu C++ pro dokument PPSM do formátu JPEG. Použijte ukázkový kód pro dávkový převod PPSM na JPEG v jakékoli aplikaci C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPSM na JPEG přes C++" h2="Vysoce výkonný převod PPSM na JPEG pomocí knihovny C++ bez nutnosti instalace Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak převést PPSM na JPEG pomocí C++" %}}

K převodu PPSM na JPEG použijeme
 [Aspose.Slides pro C++](https://products.aspose.com/slides/cs/cpp/)
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Zdrojový kód konverze PPSM na JPEG C++" >}}
```cs
// Load the PPSM
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppsm");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky pro převod PPSM na JPEG přes C++" intro="Vývojáři C++ mohou snadno převést soubor PPSM na JPEG pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPSM pomocí Aspose.Slides pro C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyberte první snímek.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nastavte požadované rozměry.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte miniaturu s požadovanými rozměry.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu Save() s výstupním parametrem JPEG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor JPEG v kompatibilním programu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového kódu převodu C++ se ujistěte, že máte následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
- Aspose.Slides pro C++ DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu PPSM na JPEG"
  description="[Vyzkoušejte naši bezplatnou aplikaci pro převod PPT až JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést PPSM do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-xml/" name="PPSM TO XML" description="Rozšiřitelný značkovací jazyk" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
