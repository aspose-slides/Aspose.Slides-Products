---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile ODP sunu dosyalarına filigran ekleme
url: /tr/java/watermark/odp/
description: Aspose.Slides for Java ile Java'da ODP sunularına metin ve görüntü filigranları ekleyin.
keywords: ODP dosyasına filigran ekle, ODP dosyasına metin filigranı ekle, ODP dosyasına görüntü filigranı ekle
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile ODP sunusuna filigran ekleme" h2="Sunucu tarafı API'lerle sunu dosyalarına metin veya görüntü filigranı ekleyen Java uygulamaları geliştirin." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java aracılığıyla ODP sunusuna filigran ekleme" variant="code" %}}

[Aspose.Slides for Java](/slides/tr/java/) ile ODP sunularına metin ve görüntü filigranları ekleyebilirsiniz. Filigranın o asıl slaydı kullanan tüm slaytlarda görünmesi için bir asıl slayda filigran şekli ekleyin.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java ile ODP dosyasına metin filigranı ekleme" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java ile ODP sunusuna görüntü filigranı ekleme" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile ODP dosyasına filigran nasıl eklenir" intro="ODP dosyalarına metin veya görüntü filigranı eklemek için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ODP` dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getMasters` yöntemiyle bir asıl slayt seçin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Bir filigran şekli eklemek için `addAutoShape` yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filigran metni eklemek için `addTextFrame` yöntemini çağırın veya görüntü filigranı için `addImage` kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filigranlı sunuyu ODP biçiminde kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides ile geliştirildi" title="ODP dosyalarına çevrimiçi filigran ekleyin" description="Ücretsiz Aspose.Slides Watermark uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Watermark uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın filigranları nasıl eklediğini görün.
- ODP dosyanıza metin veya görüntü filigranı ekleyin.
- Filigranlı dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Filigranı destekleyen diğer biçimler" subTitle="Java ile aşağıdaki biçimlere de filigran ekleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
