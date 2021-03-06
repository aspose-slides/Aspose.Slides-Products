---
title: Konwertuj PDF na JPG w Pythonie
weight: 720
url: /pl/python-net/conversion/pdf-to-jpg/ 
keywords: "Convert, PowerPoint, PDF, JPG, Presentation, Python"
description: Przykładowy kod do konwersji PDF na JPG Python. Użyj PowerPoint Python API do wsadowej konwersji plików PDF na pliki JPG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj PDF na JPG w Pythonie" h2="Potężna biblioteka PowerPoint Python do konwersji plików PDF na JPG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konwertuj PDF na JPG w Pythonie" %}}

Chcesz programowo przekonwertować pliki PDF na JPG? Używając [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/pl/python-net/) każdy programista może przekonwertować PDF na format JPG za pomocą zaledwie kilku linijek kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania prezentacji, Aspose.Slides for Python szybko tworzy JPG z pliku PDF. Przetestuj jakość konwersji plików PDF na JPG bezpośrednio w [przeglądarce](https://products.aspose.app/slides/conversion/ppt-to-jpg). Biblioteka Aspose PowerPoint PPTX umożliwia konwersję plików PDF do wielu popularnych formatów.

Możesz zainstalować bibliotekę z [PyPI](https://pypi.org/project/Aspose.Slides/) za pomocą następującego polecenia pip:

{{% blocks/products/pf/agp/code-block title="Konsola/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Jak przekonwertować plik PDF na JPG w Pythonie?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować plik PDF na JPG za pomocą Pythona." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj plik PDF z instancją klasy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wywołaj metodę `save` podczas określania ścieżki pliku wyjściowego i SaveFormat.JPG jako parametrów
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Plik PDF zostanie zapisany pod określoną ścieżką
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu źródłowego konwersji w języku Python upewnij się, że spełnione są następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- System operacyjny Microsoft Windows lub Linux (zobacz [więcej](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 lub nowszy
- Aspose.Slides dla Pythona, do którego odwołuje się Twój projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję PDF do JPG w Pythonie" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Zapisz PDF jako JPG w Pythonie" %}}
Skorzystaj z bezpłatnej aplikacji, aby zobaczyć demonstrację procesu konwersji plików PDF do JPG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Darmowa aplikacja do konwersji PDF do JPG" 
        sectionDescription="[Wypróbuj naszą bezpłatną aplikację, aby przekonwertować PDF na JPG](https://products.aspose.app/slides/import/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także konwertować pliki PDF na wiele innych formatów plików. Zobacz inne obsługiwane konwersje poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Bitmapa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Ulepszony format metapliku" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Prezentacja OpenDocument Flat XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Graficzny format wymiany" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="hipertekstowy język znaczników" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="Format prezentacji OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="Standardowy format OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Przenośna Grafika Sieciowa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Pokaz slajdów z obsługą makr" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Plik prezentacji z obsługą makr" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Otwórz format prezentacji XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Skalowalna Grafika wektorowa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Oznaczony format obrazu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="Specyfikacje papieru XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}