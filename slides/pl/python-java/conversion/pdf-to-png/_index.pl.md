---
title: Konwertuj PDF na PNG w Pythonie
url: /pl/python-java/conversion/pdf-to-png/
keywords: Konwersja prezentacji w Pythonie, konwersja prezentacji do Pythona, Python do prezentacji, Aspose.Slides Python, konwersja PDF do PNG, biblioteka prezentacji Python
description: Konwertuj PDF na PNG w Pythonie. Użyj interfejsu API biblioteki Pythona, aby przekonwertować pliki PDF na PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bez wysiłku przekonwertuj PDF na PNG za pomocą Pythona: Aspose.Slides na ratunek!" h2="Tchnij nowe życie w swoje prezentacje dzięki Pythonowi. Nasz przewodnik przeprowadzi Cię przez proces przekształcania istniejących slajdów programu PowerPoint w atrakcyjne prezentacje w języku Python." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PDF na PNG w Pythonie" %}}

Masz dość zmagania się ze złożonym oprogramowaniem do prezentacji? Nie szukaj dalej niż [**Aspose.Slides dla Pythona przez Javę**](https://products.aspose.com/slides/pl/python-java/)! Ta potężna biblioteka umożliwia łatwe tworzenie, edytowanie i konwertowanie prezentacji pomiędzy różnymi formatami. Chcesz przejść z PDF na PNG? Aspose.Slides sprawia, że ​​jest to proste i wymaga zaledwie kilku linijek kodu Pythona.

Jako najnowocześniejszy interfejs API do przetwarzania dokumentów, **Aspose.Slides dla Pythona za pośrednictwem Java** może pochwalić się błyskawiczną szybkością konwersji, zapewniając szybką transformację prezentacji PDF do formatu PNG. Pozbądź się ograniczeń tradycyjnych narzędzi — Aspose.Slides zapewnia elastyczność konwersji prezentacji z PDF nie tylko na PNG, ale także na szeroką gamę innych formatów, umożliwiając bezproblemowe dostosowanie prezentacji do każdej sytuacji.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PDF na PNG za pomocą Pythona" %}}
Aby przekonwertować plik PDF na PNG, musisz utworzyć prezentację z pliku PDF i zapisać ją jako PNG.

{{% blocks/products/pf/agp/code-block title="Samouczek Pythona dotyczący konwersji PDF na PNG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Samouczek Pythona. Jak przekonwertować PDF na PNG przy użyciu Aspose.Slides dla Pythona poprzez API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aby przekonwertować PDF na PNG przy użyciu Aspose.Slides dla Pythona za pośrednictwem Java, musisz zaimportować pakiet do skryptu Pythona i utworzyć instancję klasy Prezentacja. Klasa Prezentacja reprezentuje dokument programu PowerPoint i udostępnia metody uzyskiwania dostępu do jego elementów oraz manipulowania nimi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla Pythona przez Javę**](https://products.aspose.com/slides/pl/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu w języku Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz pliki źródłowe PDF w Pythonie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PDF na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PDF i zapisać w innych formatach plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}