---
title: Konwertuj PDF na JPG w Javie
url: /pl/java/conversion/pdf-to-jpg/
keywords: PDF do JPG, Konwersja PDF do JPG, Java API, Java Library, PDF, JPG
description: Konwertuj PDF na JPG w Javie. Użyj interfejsu API biblioteki Java, aby przekonwertować pliki PDF na pliki JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj PDF na JPG w Javie" h2="Szybka i wieloplatformowa biblioteka Java, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj PDF na JPG w Javie" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pl/java/) to potężna biblioteka Java do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji PDF na JPG. Korzystając z **Aspose.Slides for Java**, każdy programista lub aplikacja może konwertować pliki PDF na JPG za pomocą zaledwie kilku wierszy kodu Java.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Javy szybko eksportuje pliki PDF do formatów plików JPG. Biblioteka Aspose PowerPoint umożliwia konwersję PDF do JPG i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PDF na JPG za pomocą Javy" %}}
Aby przekonwertować PDF na JPG, musisz utworzyć Prezentację z pliku PDF i zapisać ją jako JPG.

{{% blocks/products/pf/agp/code-block title="Kod Java do konwersji PDF na JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    pres.getSlides().addFromPdf("InputPDF.pdf");
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować PDF na JPG przy użyciu Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować PDF na JPG w Javie." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla Javy**](https://products.aspose.com/slides/pl/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki PDF w Javie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj PDF na inne obsługiwane formaty" subTitle="Możesz także przekonwertować PDF i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}