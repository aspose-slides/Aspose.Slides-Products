---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PNG na PPTX w Javie
url: /pl/java/conversion/png-to-pptx/
keywords: Konwertuj PNG na PPTX, PNG na PPTX, PowerPoint, PNG, PPTX, Java API, Java Library
description: Konwertuj PNG na PPTX w Javie. Użyj API biblioteki Java, aby przekonwertować obrazy PNG na PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PNG na PPTX w Javie" h2="Potężny wieloplatformowy Java API do konwersji PNG na PPTX przy użyciu kodu Java" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PNG na PPTX w Javie" variant="code" %}}

Używając [**Aspose.Slides for Java**](https://products.aspose.com/slides/pl/java/), możesz przekonwertować obraz PNG na prezentację PowerPoint za pomocą zaledwie kilku linijek kodu:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Java do konwersji PNG na PPTX" >}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PNG na PPTX za pomocą Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pl/java/) to potężna biblioteka Java używana do tworzenia, konwertowania i manipulowania prezentacjami programu PowerPoint, plikami PDF, dokumentami HTML i innymi akta. Kiedy konwertujesz PNG na PPTX, zasadniczo tworzysz prezentację PowerPoint zawierającą slajdy oparte na obrazach PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PNG na PPTX w Javie" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla Javy**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj bibliotekę jako odniesienie w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz wystąpienie klasy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj obraz PNG, który chcesz przekonwertować na PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynikowy plik jako prezentację PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Darmowy konwerter online"
  description="[Jak przekonwertować PPT na HTML w Pythonie](https://products.aspose.com/slides/pl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje programu PowerPoint" subTitle="Możesz także konwertować pliki w innych formatach do programu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
