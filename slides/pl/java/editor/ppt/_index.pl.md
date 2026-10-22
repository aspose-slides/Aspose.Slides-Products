---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edytuj PPT w Javie
url: /pl/java/editor/ppt/
keywords: Edytuj PPT, edytuj PowerPoint, PPT, PowerPoint, Java API, Java Library
description: Edytuj PPT w Javie. Użyj API biblioteki Java do edycji prezentacji PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edytuj PPT w Javie" h2="Szybka i wieloplatformowa biblioteka Java do edycji PPT przy użyciu kodu Java" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edytuj PPT w Javie" variant="code" %}}

Korzystając z [**Aspose.Slides for Java**](https://products.aspose.com/slides/pl/java/), możesz dodać nowy wiersz tekstu do dokumentu PPT za pomocą zaledwie kilku wierszy kodu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod Java do edycji PPT" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edytuj PPT za pomocą Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/pl/java/) to potężna biblioteka Java używana do manipulowania i edytowania prezentacji. Możesz edytować prezentację PPT, dodając do niej nowy wiersz tekstu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak edytować PPT w Javie" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla Javy**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj bibliotekę jako odniesienie w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz wystąpienie klasy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj prezentację PPT, którą chcesz edytować.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj nowy wiersz tekstu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zmieniony plik programu PowerPoint.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edytuj inne pliki" subTitle="Możesz także edytować pliki w innych formatach" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
