---
title: Java'da PPT'yi düzenleyin
url: /tr/java/editor/ppt/
keywords: PPT'yi Düzenle, PowerPoint'i Düzenle, PPT, PowerPoint, Java API, Java Kitaplığı
description: Java'da PPT'yi düzenleyin. PowerPoint sunumunu düzenlemek için Java kitaplığı API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java'da PPT'yi düzenleyin" h2="Java kodunu kullanarak PPT'yi düzenlemek için yüksek hızlı ve platformlar arası Java kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PPT'yi düzenleyin" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunumları işlemek ve düzenlemek için kullanılan güçlü bir Java kitaplığıdır. Yeni bir metin satırı ekleyerek bir PPT sunumunu düzenleyebilirsiniz. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Java'da PPT'yi düzenleyin" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) kullanarak, yalnızca birkaç satır kodla bir PPT belgesine yeni bir metin satırı ekleyebilirsiniz.

{{% blocks/products/pf/agp/code-block title="PPT'yi düzenlemek için Java kodu" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Java'da PPT nasıl düzenlenir" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java**'yı kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Düzenlemek istediğiniz PPT sunumunu yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yeni bir metin satırı ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Değiştirilen PowerPoint dosyasını kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}