---
title: Java kullanarak PPT Sunum Dosyalarına Filigran ekleyin
url: /tr/java/watermark/ppt/
keywords: Filigran Ekle PPT, Metin Filigranı Ekle PPT, Görüntü Filigranı Ekle PPT
description: PPT Sunumuna Filigran eklemek için Java kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java kullanarak PPT Sunumuna Filigran ekleyin" h2="Sunucu tarafı API'lerini kullanarak PPT, PPTX veya ODP sunumuna metin veya resim filigranı eklemek için kendi Java uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java Aracılığıyla PPT Sunumuna Filigran Ekleyin" %}}
Aspose.Slides for Java kullanarak, PPT sunumuna filigran ekleyebilirsiniz. Filigranlar, herhangi bir sunumun önemli bir parçasıdır. Sunum içeriğinin kopyalanmasını veya izinsiz kullanılmasını önlemek için kullanılırlar. Filigran, sunumun üstüne yerleştirilen görünür veya görünmez bir resim veya metindir. Sunum sahibinin kimliğini tespit etmek ve izinsiz kullanımı önlemek için kullanılabilir. Sunuma profesyonel bir dokunuş eklemek ve daha gösterişli görünmesini sağlamak için filigranlar da kullanılabilir. 
{{% blocks/products/pf/agp/code-block title="Java kullanarak PPT için Metin Filigranı ekleyin" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java kullanarak PPT Sunumuna Resim Filigranı ekleyin" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java Aracılığıyla PPT İçin Filigran Nasıl Eklenir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPT dosyalarına metin filigranı ekleme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ana sunumu seçin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape yöntemini kullanarak şekil türü ekleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame yöntemini kullanarak filigran metni ekleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPT biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="Java kullanarak, Filigranı aşağıdaki biçimlere de ekleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}