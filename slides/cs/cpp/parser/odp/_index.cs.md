---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: Extrakce textu z prezentací ODP v C++
url: /cs/cpp/parser/odp/ 
description: Extrahujte text z prezentací ODP v C++. Pomocí Aspose.Slides for C++ parsujte snímky, textové rámce, odstavce a části textu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parsování prezentací ODP v C++" h2="Pomocí Aspose.Slides for C++ extrahujete text ze snímků prezentace bez aplikace Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parsování souboru ODP v C++" %}}

Pomocí Aspose.Slides for C++ parsujete soubory prezentací ODP a extrahujete text ze snímků. API zpřístupňuje text snímků přes `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` a `IPortion`, takže text přečtete bez automatizace aplikace Microsoft PowerPoint. Nainstalujte balíček [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) z NuGet nebo použijte níže uvedený příkaz v konzole Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parsování souborů ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak parsovat soubory ODP v C++" intro="Extrahujte text ze souborů ODP pomocí Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte objekty `ITextFrame` z prvního snímku pomocí `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte objekty `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte objekty `IParagraph` v každém `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte objekty `IPortion` v každém `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přečtěte text pomocí `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systémové požadavky" intro="Aspose.Slides for C++ podporuje hlavní desktopové a serverové platformy. Ujistěte se, že váš projekt splňuje následující předpoklady." %}}

-  Microsoft Windows, Linux, macOS nebo jiný kompatibilní operační systém s podporovaným běhovým prostředím C++.
-  Knihovna Aspose.Slides for C++ odkazovaná ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Vytvořeno pomocí Aspose.Slides" title="Extrakce textu a obrázků online" description="Bezplatná aplikace Aspose.Slides Parser je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Parser" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides čte vaše soubory, ještě než napíšete kód.
- Nahrajte soubor ODP a získejte jeho text a obrázky.
- Stáhněte vše jako jeden archiv ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

An ODP file is an OpenDocument presentation file used by applications such as OpenOffice Impress and LibreOffice Impress. It stores slides, text, images, formatting, animations, and other presentation content in an open XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro parsování" subTitle="V C++ můžete parsovat také další formáty prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/parser/ppt/" name="PPT" description="Prezentace PowerPoint 97–2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/parser/pptx/" name="PPTX" description="Prezentace PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
