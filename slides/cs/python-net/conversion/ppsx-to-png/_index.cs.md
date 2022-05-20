---
title: Převeďte PPSX na PNG v Pythonu
weight: 2080
url: /cs/python-net/conversion/ppsx-to-png/ 
keywords: "Convert, PowerPoint, PPSX, PNG, Presentation, Python"
description: Ukázkový kód pro převod PPSX na PNG Python. Použijte PowerPoint Python API pro dávkový převod souborů PPSX na soubory PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převeďte PPSX na PNG v Pythonu" h2="Výkonná PowerPoint Python knihovna pro převod PPSX do PNG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Převeďte PPSX na PNG v Pythonu" %}}

Potřebujete převést PPSX soubory do PNG programově? Pomocí [*Aspose.Slides pro Python přes .NET*](https://products.aspose.com/slides/cs/python-net/) může každý vývojář převést PPSX do formátu PNG pomocí pouhých několika řádků kódu Python.

Aspose.Slides pro Python jako moderní API pro zpracování prezentací rychle vytváří PNG z PPSX. Otestujte kvalitu převodu PPSX na PNG přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion/ppt-to-png). Knihovna Aspose PowerPoint PPTX umožňuje převádět soubory PPSX do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [PyPI](https://pypi.org/project/Aspose.Slides/) pomocí následujícího příkazu pip:

{{% blocks/products/pf/agp/code-block title="Konzole/terminál" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Jak převést PPSX na PNG v Pythonu" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k převodu souboru PPSX na PNG pomocí Pythonu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte soubor PPSX s instancí třídy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Volejte metodu `save` a zadávejte cestu k výstupnímu souboru a SaveFormat.PNG jako parametry
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Soubor PPSX bude uložen do zadané cesty
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového zdrojového kódu konverze Pythonu se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- OS Microsoft Windows nebo Linux (viz [více](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 nebo novější
- Aspose.Slides pro Python odkazovaný ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento ukázkový kód ukazuje převod PPSX na PNG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Uložte PPSX jako PNG v Pythonu" %}}
Pomocí bezplatné aplikace si můžete prohlédnout ukázku procesu převodu PPSX na PNG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Aplikace zdarma k převodu PPSX na PNG" 
        sectionDescription="[Vyzkoušejte naši bezplatnou aplikaci pro převod PPT až PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="PPSX můžete také převést do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Vylepšený formát metasouborů" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument Flat XML prezentace" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Přenosný formát dokumentu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Soubor prezentace s podporou maker" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/python-net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Specifikace papíru XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}