---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java'da HTML'yi düzenleyin
url: /tr/java/editor/html/
keywords: HTML, HTML, Java API, Java Kitaplığını Düzenle
description: Java'da HTML'yi düzenleyin. HTML dosyasını düzenlemek için Java kitaplığı API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java'da HTML'yi düzenleyin" h2="Java kodunu kullanarak HTML'yi düzenlemek için yüksek hızlı ve platformlar arası Java kitaplığı" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java'da HTML'yi düzenleyin" variant="code" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) kullanarak, yalnızca birkaç satır kodla bir HTML belgesine yeni bir metin satırı ekleyebilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML'yi düzenlemek için Java kodu" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak HTML'yi düzenleyin" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunumları, HTML belgelerini ve diğer dosyaları işlemek ve düzenlemek için kullanılan güçlü bir Java kitaplığıdır. Yeni bir metin satırı ekleyerek bir HTML belgesini düzenleyebilirsiniz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java'da HTML nasıl düzenlenir" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java**'yı kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Düzenlemek istediğiniz HTML belgesini yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yeni bir metin satırı ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen HTML dosyasını kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
