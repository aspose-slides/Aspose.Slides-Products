---
title: Konwertuj PPSX na JPG w Pythonie
url: /pl/python-java/conversion/ppsx-to-jpg/
keywords: Konwersja prezentacji w Pythonie, konwersja prezentacji do Pythona, Python do prezentacji, Aspose.Slides Python, konwersja PPSX do JPG, biblioteka prezentacji Python
description: Konwertuj PPSX na JPG w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować pliki PPSX na JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bez wysiłku przekonwertuj PPSX na JPG za pomocą Pythona: Aspose.Slides na ratunek!" h2="Tchnij nowe życie w swoje prezentacje dzięki Pythonowi. Nasz przewodnik przeprowadzi Cię przez proces przekształcania istniejących slajdów programu PowerPoint w atrakcyjne prezentacje w języku Python." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PPSX na JPG w Pythonie" %}}

Masz dość zmagania się ze złożonym oprogramowaniem do prezentacji? Nie szukaj dalej niż [**Aspose.Slides dla Pythona przez Javę**](https://products.aspose.com/slides/pl/python-java/)! Ta potężna biblioteka umożliwia łatwe tworzenie, edytowanie i konwertowanie prezentacji pomiędzy różnymi formatami. Chcesz przejść z PPSX na JPG? Aspose.Slides sprawia, że ​​jest to proste i wymaga zaledwie kilku linijek kodu Pythona.

Jako najnowocześniejszy interfejs API do przetwarzania dokumentów, **Aspose.Slides dla Pythona za pośrednictwem Java** może pochwalić się błyskawiczną szybkością konwersji, zapewniając szybką transformację prezentacji PPSX do formatu JPG. Pozbądź się ograniczeń tradycyjnych narzędzi — Aspose.Slides zapewnia elastyczność konwersji prezentacji z PPSX nie tylko na JPG, ale także na szeroką gamę innych formatów, umożliwiając bezproblemowe dostosowanie prezentacji do każdej sytuacji.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PPSX na JPG za pomocą Pythona" %}}
Aby przekonwertować plik PPSX na JPG, musisz utworzyć prezentację z pliku PPSX i zapisać ją jako JPG.

{{% blocks/products/pf/agp/code-block title="Samouczek Pythona dotyczący konwersji PPSX na JPG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppsx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Samouczek Pythona. Jak przekonwertować PPSX na JPG przy użyciu Aspose.Slides dla Pythona poprzez API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aby przekonwertować PPSX na JPG przy użyciu Aspose.Slides dla Pythona za pośrednictwem Java, musisz zaimportować pakiet do skryptu Pythona i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla Pythona przez Javę**](https://products.aspose.com/slides/pl/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu w języku Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz pliki źródłowe PPSX w Pythonie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PPSX na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PPSX i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}