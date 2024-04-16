---
title: Konwertuj PPT na JPG w Pythonie
url: /pl/python-java/conversion/ppt-to-jpg/
keywords: Konwersja prezentacji w Pythonie, konwersja prezentacji do Pythona, Python do prezentacji, Aspose.Slides Python, konwersja PPT do JPG, biblioteka prezentacji Python
description: Konwertuj PPT na JPG w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować pliki PPT na JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bez wysiłku przekonwertuj PPT na JPG za pomocą Pythona: Aspose.Slides na ratunek!" h2="Tchnij nowe życie w swoje prezentacje dzięki Pythonowi. Nasz przewodnik przeprowadzi Cię przez proces przekształcania istniejących slajdów programu PowerPoint w atrakcyjne prezentacje w języku Python." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PPT na JPG w Pythonie" %}}

Masz dość zmagania się ze złożonym oprogramowaniem do prezentacji? Nie szukaj dalej niż [**Aspose.Slides dla Pythona przez Javę**](https://products.aspose.com/slides/pl/python-java/)! Ta potężna biblioteka umożliwia łatwe tworzenie, edytowanie i konwertowanie prezentacji pomiędzy różnymi formatami. Chcesz przejść z PPT na JPG? Aspose.Slides sprawia, że ​​jest to proste i wymaga zaledwie kilku linijek kodu Pythona.

Jako najnowocześniejszy interfejs API do przetwarzania dokumentów, **Aspose.Slides dla Pythona za pośrednictwem Java** może pochwalić się błyskawiczną szybkością konwersji, zapewniając szybką transformację prezentacji PPT do formatu JPG. Pozbądź się ograniczeń tradycyjnych narzędzi — Aspose.Slides zapewnia elastyczność konwersji prezentacji z PPT nie tylko na JPG, ale także na szeroką gamę innych formatów, umożliwiając bezproblemowe dostosowanie prezentacji do każdej sytuacji.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PPT na JPG za pomocą Pythona" %}}
Aby przekonwertować plik PPT na JPG, musisz utworzyć prezentację z pliku PPT i zapisać ją jako JPG.

{{% blocks/products/pf/agp/code-block title="Samouczek Pythona dotyczący konwersji PPT na JPG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppt");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Samouczek Pythona. Jak przekonwertować PPT na JPG przy użyciu Aspose.Slides dla Pythona poprzez API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aby przekonwertować PPT na JPG przy użyciu Aspose.Slides dla Pythona za pośrednictwem Java, musisz zaimportować pakiet do skryptu Pythona i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla Pythona przez Javę**](https://products.aspose.com/slides/pl/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu w języku Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz pliki źródłowe PPT w Pythonie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PPT na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PPT i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}