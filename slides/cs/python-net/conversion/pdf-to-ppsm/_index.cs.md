---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PDF na PPSM v Pythonu
weight: 800
url: /cs/python-net/conversion/pdf-to-ppsm/ 
keywords: "Convert, PowerPoint, PDF, PPSM, Presentation, Python"
description: Ukázkový kód pro převod PDF na PPSM Python. Použijte PowerPoint Python API pro dávkový převod souborů PDF na soubory PPSM.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PDF na PPSM v Pythonu" h2="Výkonná PowerPoint Python knihovna pro převod PDF do PPSM"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF na PPSM v Pythonu" %}}

Potřebujete převést soubory PDF do PPSM programově? Pomocí [*Aspose.Slides pro Python přes .NET*](https://products.aspose.com/slides/cs/python-net/) může každý vývojář převést PDF do formátu PPSM pomocí pouhých několika řádků kódu Python.

Aspose.Slides pro Python jako moderní API pro zpracování prezentací rychle vytváří PPSM z PDF. Otestujte kvalitu převodu PDF na PPSM přímo ve svém [prohlížeči](https://products.aspose.app/slides/conversion). Knihovna Aspose PowerPoint PPTX umožňuje převádět soubory PDF do mnoha oblíbených formátů.

Knihovnu můžete nainstalovat z [PyPI](https://pypi.org/project/Aspose.Slides/) pomocí následujícího příkazu pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konzole/terminál" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Uložit PDF jako PPSM v Pythonu" %}}

Pomocí bezplatné aplikace si můžete prohlédnout ukázku procesu převodu PDF na PPSM.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tento ukázkový kód ukazuje převod PDF na PPSM Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.ppsm", slides.export.SaveFormat.PPSM)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PDF na PPSM v Pythonu" intro="Toto jsou kroky k převodu souboru PDF na PPSM pomocí Pythonu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PDF s instancí třídy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Volejte metodu `save` a zadávejte cestu k výstupnímu souboru a SaveFormat.PPSM jako parametry{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Soubor PDF bude uložen do zadané cesty{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Požadavky na systém" intro="Před spuštěním ukázkového zdrojového kódu konverze Pythonu se ujistěte, že máte následující předpoklady." %}}

- OS Microsoft Windows nebo Linux (viz [více](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 nebo novější
- Aspose.Slides pro Python odkazovaný ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikace zdarma k převodu PDF na PPSM"
  description="[Vyzkoušejte naši bezplatnou aplikaci pro převod PDF až PPSM](https://products.aspose.app/slides/import/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované konverze" subTitle="PDF můžete také převést do mnoha dalších formátů souborů. Další podporované konverze naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Bitmapový obrázek" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Vylepšený formát metasouborů" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocument Flat XML prezentace" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Grafický výměnný formát" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Obrázek JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="Formát prezentace OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="Standardní formát OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Přenosná síťová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="Soubory šablon Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Prezentace PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Soubor prezentace s podporou maker" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Formát otevřené prezentace XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Škálovatelná vektorová grafika" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="Formát SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Formát tagovaného obrázku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="Specifikace papíru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
