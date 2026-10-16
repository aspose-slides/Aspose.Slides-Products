---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte OTP na BMP v Pythonu
url: /cs/python-java/conversion/otp-to-bmp/
keywords: Převod prezentací v Pythonu, převod prezentací do jazyka Python, Python pro prezentace, Aspose.Slides Python, převod OTP do BMP, knihovna prezentací Pythonu
description: Převeďte OTP na BMP v Pythonu. Použijte rozhraní API knihovny Python k převodu souborů OTP do BMP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte bez námahy OTP do BMP pomocí Python: Aspose.Slides to the Rescue!" h2="Vdechněte svým prezentacím nový život pomocí Pythonu. Náš průvodce vás provede převodem stávajících PowerPoint snímků na poutavé prezentace v Pythonu." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte OTP na BMP pomocí Pythonu" variant="code" %}}

Chcete-li převést OTP do BMP, budete muset vytvořit prezentaci ze souboru OTP a uložit ji jako BMP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Výukový program Pythonu pro převod OTP do BMP" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.otp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte OTP na BMP v Pythonu" %}}

Už vás nebaví zápasit se složitým prezentačním softwarem? Nehledejte nic jiného než [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/)! Tato výkonná knihovna vám umožňuje snadno vytvářet, upravovat a převádět prezentace mezi různými formáty. Potřebujete přejít z OTP na BMP? Díky Aspose.Slides je to hračka a vyžaduje jen pár řádků kódu Pythonu.

**Aspose.Slides pro Python přes Javu** se jako špičkové rozhraní API pro zpracování dokumentů může pochlubit bleskovou rychlostí převodu, která zajišťuje rychlou transformaci vašich prezentací OTP do formátu BMP. Zbavte se omezení tradičních nástrojů – Aspose.Slides vám poskytuje flexibilitu při převodu prezentací z OTP nejen do BMP, ale také široké škály dalších formátů, což vám umožňuje bezchybně přizpůsobit vaše prezentace jakékoli situaci.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Výukový program Python. Jak převést OTP do BMP pomocí Aspose.Slides pro Python přes Java API." intro="Chcete-li převést OTP na BMP pomocí Aspose.Slides pro Python přes Javu, musíte importovat balíček do vašeho skriptu Python a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete zdrojové soubory OTP v Pythonu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložit výsledek jako soubor BMP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Převést OTP do jiných podporovaných formátů" subTitle="Můžete také převést OTP a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
