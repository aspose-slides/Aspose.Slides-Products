---
title: Převeďte POTM na BMP v Pythonu
url: /cs/python-java/conversion/potm-to-bmp/
keywords: Převod prezentací v Pythonu, převod prezentací do jazyka Python, Python pro prezentace, Aspose.Slides Python, převod POTM do BMP, knihovna prezentací Pythonu
description: Převeďte POTM na BMP v Pythonu. Použijte rozhraní API knihovny Python k převodu souborů POTM do BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte bez námahy POTM do BMP pomocí Python: Aspose.Slides to the Rescue!" h2="Vdechněte svým prezentacím nový život pomocí Pythonu. Náš průvodce vás provede převodem stávajících PowerPoint snímků na poutavé prezentace v Pythonu." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte POTM na BMP v Pythonu" %}}

Už vás nebaví zápasit se složitým prezentačním softwarem? Nehledejte nic jiného než [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/)! Tato výkonná knihovna vám umožňuje snadno vytvářet, upravovat a převádět prezentace mezi různými formáty. Potřebujete přejít z POTM na BMP? Díky Aspose.Slides je to hračka a vyžaduje jen pár řádků kódu Pythonu.

**Aspose.Slides pro Python přes Javu** se jako špičkové rozhraní API pro zpracování dokumentů může pochlubit bleskovou rychlostí převodu, která zajišťuje rychlou transformaci vašich prezentací POTM do formátu BMP. Zbavte se omezení tradičních nástrojů – Aspose.Slides vám poskytuje flexibilitu při převodu prezentací z POTM nejen do BMP, ale také široké škály dalších formátů, což vám umožňuje bezchybně přizpůsobit vaše prezentace jakékoli situaci.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte POTM na BMP pomocí Pythonu" %}}
Chcete-li převést POTM do BMP, budete muset vytvořit prezentaci ze souboru POTM a uložit ji jako BMP.

{{% blocks/products/pf/agp/code-block title="Výukový program Pythonu pro převod POTM do BMP" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.potm");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Výukový program Python. Jak převést POTM do BMP pomocí Aspose.Slides pro Python přes Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést POTM na BMP pomocí Aspose.Slides pro Python přes Javu, musíte importovat balíček do vašeho skriptu Python a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory POTM v Pythonu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést POTM do jiných podporovaných formátů" subTitle="Můžete také převést POTM a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}