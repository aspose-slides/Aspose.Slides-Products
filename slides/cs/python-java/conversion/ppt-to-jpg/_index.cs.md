---
title: Převeďte PPT na JPG v Pythonu
url: /cs/python-java/conversion/ppt-to-jpg/
keywords: Převod prezentací v Pythonu, převod prezentací do jazyka Python, Python pro prezentace, Aspose.Slides Python, převod PPT do JPG, knihovna prezentací Pythonu
description: Převeďte PPT na JPG v Pythonu. Použijte rozhraní API knihovny Python k převodu souborů PPT do JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte bez námahy PPT do JPG pomocí Python: Aspose.Slides to the Rescue!" h2="Vdechněte svým prezentacím nový život pomocí Pythonu. Náš průvodce vás provede převodem stávajících PowerPoint snímků na poutavé prezentace v Pythonu." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PPT na JPG v Pythonu" %}}

Už vás nebaví zápasit se složitým prezentačním softwarem? Nehledejte nic jiného než [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/)! Tato výkonná knihovna vám umožňuje snadno vytvářet, upravovat a převádět prezentace mezi různými formáty. Potřebujete přejít z PPT na JPG? Díky Aspose.Slides je to hračka a vyžaduje jen pár řádků kódu Pythonu.

**Aspose.Slides pro Python přes Javu** se jako špičkové rozhraní API pro zpracování dokumentů může pochlubit bleskovou rychlostí převodu, která zajišťuje rychlou transformaci vašich prezentací PPT do formátu JPG. Zbavte se omezení tradičních nástrojů – Aspose.Slides vám poskytuje flexibilitu při převodu prezentací z PPT nejen do JPG, ale také široké škály dalších formátů, což vám umožňuje bezchybně přizpůsobit vaše prezentace jakékoli situaci.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte PPT na JPG pomocí Pythonu" %}}
Chcete-li převést PPT do JPG, budete muset vytvořit prezentaci ze souboru PPT a uložit ji jako JPG.

{{% blocks/products/pf/agp/code-block title="Výukový program Pythonu pro převod PPT do JPG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppt");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Výukový program Python. Jak převést PPT do JPG pomocí Aspose.Slides pro Python přes Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést PPT na JPG pomocí Aspose.Slides pro Python přes Javu, musíte importovat balíček do vašeho skriptu Python a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PPT v Pythonu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést PPT do jiných podporovaných formátů" subTitle="Můžete také převést PPT a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}