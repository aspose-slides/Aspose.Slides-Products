---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Dodawanie znaku wodnego do plików prezentacji PPT w Javie
url: /pl/java/watermark/ppt/
description: Dodawaj tekstowe i graficzne znaki wodne do prezentacji PPT w Javie za pomocą Aspose.Slides for Java.
keywords: dodawanie znaku wodnego do PPT, tekstowy znak wodny PPT, graficzny znak wodny PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Dodawanie znaku wodnego do prezentacji PPT w Javie" h2="Twórz aplikacje Java, które za pomocą serwerowych API wstawiają tekstowe lub graficzne znaki wodne do plików prezentacji." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Dodawanie znaku wodnego do prezentacji PPT za pomocą Javy" variant="code" %}}

Dzięki [Aspose.Slides for Java](/slides/pl/java/) możesz dodawać tekstowe i graficzne znaki wodne do prezentacji PPT. Dodaj kształt znaku wodnego do wzorca slajdów, aby znak wodny pojawiał się na slajdach korzystających z tego wzorca.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie tekstowego znaku wodnego do PPT w Javie" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie graficznego znaku wodnego do prezentacji PPT w Javie" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak dodać znak wodny do PPT w Javie" intro="Wykonaj poniższe kroki, aby dodać tekstowy lub graficzny znak wodny do plików PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik `PPT` za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wybierz wzorzec slajdów za pomocą metody `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `addAutoShape`, aby dodać kształt znaku wodnego.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `addTextFrame`, aby dodać tekst znaku wodnego, lub użyj `addImage` dla graficznego znaku wodnego.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz prezentację ze znakiem wodnym w formacie PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Zbudowano z Aspose.Slides" title="Dodawaj znaki wodne do plików PPT online" description="Bezpłatna aplikacja Aspose.Slides Watermark została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Watermark" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides dodaje znaki wodne, zanim napiszesz kod.
- Dodaj tekstowy lub graficzny znak wodny do pliku PPT.
- Pobierz plik ze znakiem wodnym.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne formaty obsługujące znaki wodne" subTitle="W Javie możesz też dodawać znaki wodne do następujących formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
