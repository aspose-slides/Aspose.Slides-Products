---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte FODP na BMP v Pythonu
weight: 10
url: /cs/python-net/conversion/fodp-to-bmp/ 
keywords: "Convert, PowerPoint, FODP, BMP, Presentation, Python"
description: Ukázkový kód pro konverzi FODP na BMP Python. Použijte PowerPoint Python API pro dávkový převod souborů FODP na soubory BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte FODP na BMP v Pythonu" h2="Výkonná PowerPoint Python knihovna pro převod FODP do BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte FODP na BMP v Pythonu" %}}

Potřebujete převést soubory FODP na BMP programově? Pomocí [*Aspose.Slides pro Python přes .NET*](https://products.aspose.com/slides/cs/python-net/) může každý vývojář převést FODP do formátu BMP pomocí pouhých několika řádků kódu Python.

Jako moderní API pro zpracování prezentací vytváří Aspose.Slides pro Python rychle BMP z FODP. Otestujte kvalitu převodu FODP na BMP přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion). Knihovna Aspose PowerPoint PPTX umožňuje převádět soubory FODP do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [PyPI](https://pypi.org/project/Aspose.Slides/) pomocí následujícího příkazu pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzole/terminál" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Uložte FODP jako BMP v Pythonu" %}}

Pomocí bezplatné aplikace si můžete prohlédnout ukázku procesu převodu FODP na BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tento ukázkový kód ukazuje konverzi FODP na BMP Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést FODP na BMP v Pythonu" intro="Toto jsou kroky k převodu souboru FODP na BMP pomocí Pythonu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor FODP s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Volejte metodu `save` a zadávejte cestu k výstupnímu souboru a SaveFormat.BMP jako parametry{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor FODP bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového zdrojového kódu konverze Pythonu se ujistěte, že máte následující předpoklady." %}}

- OS Microsoft Windows nebo Linux (viz [více](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 nebo novější
- Aspose.Slides pro Python odkazovaný ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu FODP na BMP"
  description="[Vyzkoušejte zdarma Editor App](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="FODP můžete také převést do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-emf/" name="FODP TO EMF" description="Vylepšený formát metasouborů" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Přenosný formát dokumentu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="Přenosná síťová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Soubor prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-svg/" name="FODP TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
