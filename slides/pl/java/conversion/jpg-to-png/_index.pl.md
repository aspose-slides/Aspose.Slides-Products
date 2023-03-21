---
title: Konwertuj JPG na PNG w Javie
url: /pl/java/conversion/jpg-to-png/
keywords: JPG do PNG, Konwersja JPG do PNG, Java API, Java Library, JPG, PNG
description: Konwertuj JPG na PNG w Javie. Użyj interfejsu API biblioteki Java, aby przekonwertować pliki JPG na pliki PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konwertuj JPG na PNG w Javie" h2="Szybka i wieloplatformowa biblioteka Java, która pomaga w tworzeniu aplikacji z możliwością tworzenia, scalania, sprawdzania lub konwertowania plików prezentacji Microsoft PowerPoint i OpenOffice bez użycia oprogramowania takiego jak Microsoft lub Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj JPG na PNG w Javie" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pl/java/) to potężna biblioteka Java do tworzenia i manipulowania plikami prezentacji. Ponadto zapewnia elastyczne sposoby konwersji JPG na PNG. Korzystając z **Aspose.Slides for Java**, każdy programista lub aplikacja może konwertować pliki JPG na PNG za pomocą zaledwie kilku wierszy kodu Java.

Jako nowoczesny interfejs API do przetwarzania dokumentów, Aspose.Slides dla Javy szybko eksportuje pliki JPG do formatów plików PNG. Biblioteka Aspose PowerPoint umożliwia konwersję JPG do PNG i wielu innych formatów plików

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj JPG na PNG za pomocą Javy" %}}
Aby przekonwertować JPG na PNG, musisz utworzyć Prezentację z pliku JPG i zapisać ją jako PNG.

{{% blocks/products/pf/agp/code-block title="Kod Java do konwersji JPG na PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak przekonwertować JPG na PNG przy użyciu Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować JPG na PNG w Javie." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zainstaluj [**Aspose.Slides dla Javy**](https://products.aspose.com/slides/pl/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dodaj odwołanie do biblioteki (zaimportuj bibliotekę) do swojego projektu Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otwórz źródłowe pliki JPG w Javie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapisz wynik jako plik PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Darmowy konwerter online" sectionDescription="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konwertuj JPG na inne obsługiwane formaty" subTitle="Możesz także przekonwertować JPG i zapisać do innych formatów plików. Zobacz wszystkie obsługiwane formaty poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}