---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Upravujte soubory POTM přes .NET
url: /cs/net/editor/potm/ 
description: Zdrojový kód C# pro úpravu dokumentu POTM na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Upravit formáty POTM v C#" h2="Nativní a vysoce výkonné úpravy dokumentů POTM pomocí rozhraní Aspose.Slides pro .NET API na straně serveru bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Jak upravit soubor POTM pomocí C#" %}}

K úpravě souboru POTM použijeme rozhraní <a href="https://products.aspose.com/slides/cs/net">Aspose.Slides for .NET</a> API, které je bohaté na funkce a výkonné a snadno použitelné API pro platformu C# pro jakýkoli editor. Otevřete správce balíčků <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a>, vyhledejte <b>Aspose.Slides</b> a nainstalujte. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Upravit soubory POTM – C#" >}}
```cs
using var presentation = new Presentation("document.potm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.potm", SaveFormat.Potm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Kroky pro úpravu souborů POTM v C#" intro="Základní úprava dokumentu s [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net) Rozhraní API lze vytvořit pomocí několika řádků kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor POTM pomocí objektu `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte cílový snímek a tvar prostřednictvím proměnných.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aktualizujte text pomocí `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte upravenou prezentaci pomocí `SaveFormat.Potm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Naše API jsou podporována na všech hlavních platformách a operačních systémech. Před spuštěním níže uvedeného kódu se prosím ujistěte, že máte ve svém systému následující předpoklady." %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin
- Vývojové prostředí jako Microsoft Visual Studio
- Aspose.Slides pro .NET DLL odkazovaný ve vašem projektu - Nainstalujte z NuGet pomocí tlačítka Stáhnout výše

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Vytvořeno pomocí Aspose.Slides" title="Upravujte soubory PPTX online" description="Bezplatná aplikace Aspose.Slides Editor je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Editor" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides zpracuje vaše soubory, ještě než napíšete kód.
- Nahrajte soubory PPTX a okamžitě je upravte.
- Uložte a stáhněte upravený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. These settings can include styles, backgrounds, colour palette, fonts and defaults along with macros that consist of custom functions for doing particular task. They may also be opened by a previous version of PowerPoint with Open XML document support installed. POTM files can be opened in Microsoft PowerPoint for editing like any other PowerPoint file.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
