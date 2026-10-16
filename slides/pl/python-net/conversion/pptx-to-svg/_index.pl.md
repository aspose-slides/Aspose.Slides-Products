---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPTX na SVG w Pythonie
weight: 2830
url: /pl/python-net/conversion/pptx-to-svg/ 
keywords: "Convert, PowerPoint, PPTX, SVG, Presentation, Python"
description: Przykładowy kod do konwersji PPTX do SVG Python. Użyj PowerPoint Python API do konwersji wsadowej plików PPTX na pliki SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPTX na SVG w Pythonie" h2="Potężna biblioteka PowerPoint Python do konwersji PPTX do SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PPTX na SVG w Pythonie" %}}

Chcesz programowo przekonwertować pliki PPTX na SVG? Używając [*Aspose.Slides for Python przez .NET*](https://products.aspose.com/slides/pl/python-net/) każdy programista może przekonwertować PPTX na format SVG za pomocą zaledwie kilku wierszy kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania prezentacji, Aspose.Slides for Python szybko tworzy SVG z PPTX. Przetestuj jakość konwersji PPTX do SVG bezpośrednio w [przeglądarce](https://products.aspose.app/slides/conversion). Biblioteka Aspose PowerPoint PPTX umożliwia konwersję plików PPTX do wielu popularnych formatów.

Możesz zainstalować bibliotekę z [PyPI](https://pypi.org/project/Aspose.Slides/) za pomocą następującego polecenia pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsola/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Zapisz PPTX jako SVG w Pythonie" %}}

Skorzystaj z bezpłatnej aplikacji, aby zobaczyć demonstrację procesu konwersji PPTX do SVG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ten przykładowy kod pokazuje konwersję PPTX do SVG w Pythonie" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PPTX na SVG w Pythonie?" intro="Oto kroki, aby przekonwertować plik PPTX na SVG za pomocą Pythona." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj plik PPTX z instancją klasy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `save` podczas określania ścieżki pliku wyjściowego i SaveFormat.SVG jako parametrów{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Plik PPTX zostanie zapisany pod określoną ścieżką{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="wymagania systemowe" intro="Przed uruchomieniem przykładowego kodu źródłowego konwersji w języku Python upewnij się, że spełnione są następujące wymagania wstępne." %}}

- System operacyjny Microsoft Windows lub Linux (zobacz [więcej](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 lub nowszy
- Aspose.Slides dla Pythona, do którego odwołuje się Twój projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="pptx-to-svg"
  title="Darmowa aplikacja do konwersji PPTX do SVG"
  description="[Wypróbuj naszą bezpłatną aplikację Editor](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować PPTX na wiele innych formatów plików. Zobacz inne obsługiwane konwersje poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmapa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Ulepszony format metapliku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="Prezentacja OpenDocument Flat XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Graficzny format wymiany" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-html/" name="PPTX TO HTML" description="hipertekstowy język znaczników" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="Obraz JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Format prezentacji OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Standardowy format OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="format dokumentu przenośnego" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-png/" name="PPTX TO PNG" description="Przenośna Grafika Sieciowa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-pot/" name="PPTX TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Pokaz slajdów z obsługą makr" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Plik prezentacji z obsługą makr" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Oznaczony format obrazu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Specyfikacje papieru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
