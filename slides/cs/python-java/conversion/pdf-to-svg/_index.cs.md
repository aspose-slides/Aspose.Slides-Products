---
title: Převeďte PDF na SVG v Pythonu
url: /cs/python-java/conversion/pdf-to-svg/
keywords: Převod prezentací v Pythonu, převod prezentací do jazyka Python, Python pro prezentace, Aspose.Slides Python, převod PDF do SVG, knihovna prezentací Pythonu
description: Převeďte PDF na SVG v Pythonu. Použijte rozhraní API knihovny Python k převodu souborů PDF do SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte bez námahy PDF do SVG pomocí Python: Aspose.Slides to the Rescue!" h2="Vdechněte svým prezentacím nový život pomocí Pythonu. Náš průvodce vás provede převodem stávajících PowerPoint snímků na poutavé prezentace v Pythonu." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PDF na SVG v Pythonu" %}}

Už vás nebaví zápasit se složitým prezentačním softwarem? Nehledejte nic jiného než [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/)! Tato výkonná knihovna vám umožňuje snadno vytvářet, upravovat a převádět prezentace mezi různými formáty. Potřebujete přejít z PDF na SVG? Díky Aspose.Slides je to hračka a vyžaduje jen pár řádků kódu Pythonu.

**Aspose.Slides pro Python přes Javu** se jako špičkové rozhraní API pro zpracování dokumentů může pochlubit bleskovou rychlostí převodu, která zajišťuje rychlou transformaci vašich prezentací PDF do formátu SVG. Zbavte se omezení tradičních nástrojů – Aspose.Slides vám poskytuje flexibilitu při převodu prezentací z PDF nejen do SVG, ale také široké škály dalších formátů, což vám umožňuje bezchybně přizpůsobit vaše prezentace jakékoli situaci.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte PDF na SVG pomocí Pythonu" %}}
Chcete-li převést PDF do SVG, budete muset vytvořit prezentaci ze souboru PDF a uložit ji jako SVG.

{{% blocks/products/pf/agp/code-block title="Výukový program Pythonu pro převod PDF do SVG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

for i in range(pres.getSlides().size()):
    outputStream = open('slide" + i + ".svg', "wb")
    outputStream.write(Slide.writeAsSvgToBytes(pres.getSlides().get_Item(i)))

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Výukový program Python. Jak převést PDF do SVG pomocí Aspose.Slides pro Python přes Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Chcete-li převést PDF na SVG pomocí Aspose.Slides pro Python přes Javu, musíte importovat balíček do vašeho skriptu Python a vytvořit instanci třídy Presentation. Třída Prezentace představuje dokument PowerPoint a poskytuje metody pro přístup a manipulaci s jeho prvky." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides pro Python přes Java**](https://products.aspose.com/slides/cs/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PDF v Pythonu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést PDF do jiných podporovaných formátů" subTitle="Můžete také převést PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}