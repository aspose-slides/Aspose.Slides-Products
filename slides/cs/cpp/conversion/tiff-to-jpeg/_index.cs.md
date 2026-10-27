---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte TIFF na JPEG pomocí aplikace C++
weight: 4420
url: /cs/cpp/conversion/tiff-to-jpeg/ 
description: Ukázka převodního kódu C++ pro dokument TIFF do formátu JPEG. Použijte ukázkový kód pro dávkový převod TIFF na JPEG v jakékoli aplikaci C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte TIFF na JPEG pomocí C++" h2="Vysoce výkonný převod TIFF do JPEG pomocí knihovny C++ bez nutnosti instalace Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak převést TIFF na JPEG pomocí C++" %}}

K převodu TIFF na JPEG použijeme
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Zdrojový kód převodu TIFF na JPEG C++" >}}
```cs
// Load the TIFF
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.tiff");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky pro převod TIFF na JPEG přes C++" intro="Vývojáři C++ mohou snadno převést soubor TIFF na JPEG pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor TIFF pomocí Aspose.Slides pro C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Vytvořeno pomocí Aspose.Slides" title="Převod TIFF na JPEG online" description="Bezplatná aplikace Aspose.Slides Conversion je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory TIFF." button="Otevřít Aspose.Slides Conversion" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" upload="Přetáhněte nebo nahrajte soubor" saveAs="Uložit jako" convert="Převést" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides převádí soubory, ještě než začnete psát kód.
- Nahrajte soubory TIFF a uložte je jako JPEG.
- Stáhněte výsledek nebo převeďte další soubory.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést TIFF do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="Rozšiřitelný značkovací jazyk" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
