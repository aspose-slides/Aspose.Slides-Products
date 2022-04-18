---
title: Konwertuj POTM na EMF w Pythonie
weight: 1120
url: /pl/python-net/conversion/potm-to-emf/ 
keywords: "Convert, PowerPoint, POTM, EMF, Presentation, Python"
description: Przykładowy kod do konwersji POTM do EMF Python. Użyj PowerPoint Python API do wsadowej konwersji plików POTM do plików EMF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj POTM na EMF w Pythonie" h2="Potężna biblioteka PowerPoint Python do konwersji POTM na EMF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konwertuj POTM na EMF w Pythonie" %}}

Chcesz programowo przekonwertować pliki POTM na EMF? Używając [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/python-net/) każdy programista może przekonwertować POTM na format EMF za pomocą zaledwie kilku linijek kodu Pythona.

Jako nowoczesny interfejs API do przetwarzania prezentacji, Aspose.Slides for Python szybko tworzy EMF z POTM. Przetestuj jakość konwersji POTM na EMF bezpośrednio w [przeglądarce](https://products.aspose.app/slides/conversion). Biblioteka Aspose PowerPoint PPTX umożliwia konwersję plików POTM do wielu popularnych formatów.

Możesz zainstalować bibliotekę z [PyPI](https://pypi.org/project/Aspose.Slides/) za pomocą następującego polecenia pip:

{{% blocks/products/pf/agp/code-block title="Konsola/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Jak przekonwertować POTM na EMF w Pythonie?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować plik POTM na EMF za pomocą Pythona." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj plik POTM z instancją klasy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wywołaj metodę `save` podczas określania ścieżki pliku wyjściowego i SaveFormat.EMF jako parametrów
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Plik POTM zostanie zapisany pod określoną ścieżką
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

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję POTM do EMF Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Zapisz POTM jako EMF w Pythonie" %}}
Skorzystaj z bezpłatnej aplikacji, aby zobaczyć demonstrację procesu konwersji POTM do EMF. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert POTM to EMF" sectionDescription="Check our live demos for [POTM to EMF conversion](https://products.aspose.app/slides/conversion/) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POTM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant EMF file." >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować POTM na wiele innych formatów plików. Zobacz inne obsługiwane konwersje poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmapa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-fodp/" name="POTM TO FODP" description="Prezentacja OpenDocument Flat XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-gif/" name="POTM TO GIF" description="Graficzny format wymiany" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-html/" name="POTM TO HTML" description="hipertekstowy język znaczników" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-jpg/" name="POTM TO JPG" description="Obraz JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-odp/" name="POTM TO ODP" description="Format prezentacji OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-otp/" name="POTM TO OTP" description="Standardowy format OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pdf/" name="POTM TO PDF" description="format dokumentu przenośnego" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-png/" name="POTM TO PNG" description="Przenośna Grafika Sieciowa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pot/" name="POTM TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-potx/" name="POTM TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pps/" name="POTM TO PPS" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Pokaz slajdów z obsługą makr" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Plik prezentacji z obsługą makr" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Otwórz format prezentacji XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-svg/" name="POTM TO SVG" description="Skalowalna Grafika wektorowa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-swf/" name="POTM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Oznaczony format obrazu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potm-to-xps/" name="POTM TO XPS" description="Specyfikacje papieru XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}