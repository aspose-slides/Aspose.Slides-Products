---
title: Java kullanarak PPTX Sunum Dosyalarına Filigran ekleyin
url: /tr/java/watermark/pptx/
keywords: Filigran Ekle PPTX, Metin Filigranı Ekle PPTX, Görüntü Filigranı Ekle PPTX
description: PPTX Sunumuna Filigran eklemek için Java kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java kullanarak PPTX Sunumuna Filigran ekleyin" h2="Sunucu tarafı API'lerini kullanarak PPT, PPTX veya ODP sunumuna metin veya resim filigranı eklemek için kendi Java uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java Aracılığıyla PPTX Sunumuna Filigran Ekleyin" %}}
Aspose.Slides for Java kullanarak, PPTX sunumuna filigran ekleyebilirsiniz. Filigranlar, herhangi bir sunumun önemli bir parçasıdır. Sunum içeriğinin kopyalanmasını veya izinsiz kullanılmasını önlemek için kullanılırlar. Filigran, sunumun üstüne yerleştirilen görünür veya görünmez bir resim veya metindir. Sunum sahibinin kimliğini tespit etmek ve izinsiz kullanımı önlemek için kullanılabilir. Sunuma profesyonel bir dokunuş eklemek ve daha gösterişli görünmesini sağlamak için filigranlar da kullanılabilir. 
{{% blocks/products/pf/agp/code-block title="Java kullanarak PPTX için Metin Filigranı ekleyin" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java kullanarak PPTX Sunumuna Resim Filigranı ekleyin" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java Aracılığıyla PPTX İçin Filigran Nasıl Eklenir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPTX dosyalarına metin filigranı ekleme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyasını bir Sunum örneğiyle yükleyin
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
Sonucu PPTX biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="Java kullanarak, Filigranı aşağıdaki biçimlere de ekleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}