---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj FODP na SVG w Pythonie
weight: 190
url: /pl/python-net/conversion/fodp-to-svg/ 
keywords: "Convert, PowerPoint, FODP, SVG, Presentation, Python"
description: Przykładowy kod do konwersji FODP do SVG Python. Użyj PowerPoint Python API do wsadowej konwersji plików FODP na pliki SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj FODP na SVG w Pythonie" h2="Potężna biblioteka PowerPoint Python do konwersji FODP do SVG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj FODP na SVG w Pythonie" %}}

Chcesz programowo przekonwertować pliki FODP do SVG? Używając [*Aspose.Slides for Python przez .NET*](https://products.aspose.com/slides/pl/python-net/) każdy programista może przekonwertować FODP na format SVG za pomocą zaledwie kilku wierszy kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania prezentacji, Aspose.Slides for Python szybko tworzy SVG z FODP. Przetestuj jakość konwersji FODP do SVG bezpośrednio w [przeglądarce](https://products.aspose.app/slides/conversion). Biblioteka Aspose PowerPoint PPTX umożliwia konwersję plików FODP do wielu popularnych formatów.

Możesz zainstalować bibliotekę z [PyPI](https://pypi.org/project/Aspose.Slides/) za pomocą następującego polecenia pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsola/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Zapisz FODP jako SVG w Pythonie" %}}

Skorzystaj z bezpłatnej aplikacji, aby zobaczyć demonstrację procesu konwersji FODP do SVG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ten przykładowy kod pokazuje konwersję FODP do SVG w Pythonie" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować FODP do SVG w Pythonie?" intro="Oto kroki, aby przekonwertować plik FODP na SVG za pomocą Pythona." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj plik FODP z instancją klasy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `save` podczas określania ścieżki pliku wyjściowego i SaveFormat.SVG jako parametrów{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Plik FODP zostanie zapisany pod określoną ścieżką{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="wymagania systemowe" intro="Przed uruchomieniem przykładowego kodu źródłowego konwersji w języku Python upewnij się, że spełnione są następujące wymagania wstępne." %}}

- System operacyjny Microsoft Windows lub Linux (zobacz [więcej](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 lub nowszy
- Aspose.Slides dla Pythona, do którego odwołuje się Twój projekt.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Zbudowano z Aspose.Slides" title="Konwertuj FODP na SVG online" description="Bezpłatna aplikacja Aspose.Slides Conversion została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami FODP." button="Otwórz Aspose.Slides Conversion" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" upload="Upuść lub prześlij plik" saveAs="Zapisz jako" convert="Konwertuj" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides konwertuje pliki, zanim napiszesz kod.
- Prześlij pliki FODP i zapisz je jako SVG.
- Pobierz wynik lub przekonwertuj kolejne pliki.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować FODP na wiele innych formatów plików. Zobacz inne obsługiwane konwersje poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bitmapa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-emf/" name="FODP TO EMF" description="Ulepszony format metapliku" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="Graficzny format wymiany" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="hipertekstowy język znaczników" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Obraz JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="Format prezentacji OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="Standardowy format OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="format dokumentu przenośnego" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="Przenośna Grafika Sieciowa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Pokaz slajdów z obsługą makr" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Plik prezentacji z obsługą makr" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Otwórz format prezentacji XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Oznaczony format obrazu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="Specyfikacje papieru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
