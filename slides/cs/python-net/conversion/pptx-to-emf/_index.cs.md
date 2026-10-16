---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PPTX na EMF v Pythonu
weight: 2660
url: /cs/python-net/conversion/pptx-to-emf/ 
keywords: "Convert, PowerPoint, PPTX, EMF, Presentation, Python"
description: Ukázkový kód pro konverzi PPTX na EMF Python. Použijte PowerPoint Python API pro dávkový převod souborů PPTX na soubory EMF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PPTX na EMF v Pythonu" h2="Výkonná PowerPoint Python knihovna pro převod PPTX do EMF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PPTX na EMF v Pythonu" %}}

Potřebujete převést soubory PPTX na EMF programově? Pomocí [*Aspose.Slides pro Python přes .NET*](https://products.aspose.com/slides/cs/python-net/) může každý vývojář převést PPTX do formátu EMF pomocí pouhých několika řádků kódu Python.

Aspose.Slides pro Python jako moderní API pro zpracování prezentací rychle vytváří EMF z PPTX. Otestujte kvalitu převodu PPTX na EMF přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion). Knihovna Aspose PowerPoint PPTX umožňuje převádět soubory PPTX do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [PyPI](https://pypi.org/project/Aspose.Slides/) pomocí následujícího příkazu pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzole/terminál" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Uložte PPTX jako EMF v Pythonu" %}}

Pomocí bezplatné aplikace si můžete prohlédnout ukázku procesu převodu PPTX na EMF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tento ukázkový kód ukazuje převod PPTX na EMF Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PPTX na EMF v Pythonu" intro="Toto jsou kroky pro převod souboru PPTX na EMF pomocí Pythonu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPTX s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Volejte metodu `save` a zadávejte cestu k výstupnímu souboru a SaveFormat.EMF jako parametry{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor PPTX bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového zdrojového kódu konverze Pythonu se ujistěte, že máte následující předpoklady." %}}

- OS Microsoft Windows nebo Linux (viz [více](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 nebo novější
- Aspose.Slides pro Python odkazovaný ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu PPTX na EMF"
  description="[Vyzkoušejte zdarma Text To Gif App](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="Můžete také převést PPTX do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocument Flat XML prezentace" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Přenosný formát dokumentu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-png/" name="PPTX TO PNG" description="Přenosná síťová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-pot/" name="PPTX TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Soubor prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
