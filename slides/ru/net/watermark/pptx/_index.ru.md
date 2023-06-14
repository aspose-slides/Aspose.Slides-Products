---
title: Добавьте водяной знак в файлы презентаций PPTX с помощью .NET
url: /ru/net/watermark/pptx/
keywords: Добавить водяной знак PPTX, Добавить текстовый водяной знак PPTX, Добавить водяной знак изображения PPTX
description: Исходный код C# для добавления водяного знака в презентацию PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Добавьте водяной знак в презентацию PPTX, используя C#" h2="Создавайте собственные приложения .NET, чтобы вставлять текстовые или графические водяные знаки в презентации PPT, PPTX или ODP с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Добавить водяной знак в презентацию PPTX через C#" %}}
Используя Aspose.Slides for .NET, вы можете добавить водяной знак в презентацию PPTX. Водяные знаки являются неотъемлемой частью любой презентации. Они используются для защиты содержимого презентации от копирования или использования без разрешения. Водяной знак — это видимое или невидимое изображение или текст, которые размещаются поверх презентации. Его можно использовать для идентификации владельца презентации и предотвращения несанкционированного использования. Водяные знаки также можно использовать, чтобы придать презентации профессиональный вид и сделать ее более изысканной. 
{{% blocks/products/pf/agp/code-block title="Добавьте текстовый водяной знак в PPTX, используя C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Добавьте водяной знак изображения в презентацию PPTX, используя C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как добавить водяной знак в PPTX через C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для добавления текстового водяного знака в файлы PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPTX с экземпляром Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Выберите основную презентацию
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте тип фигуры с помощью метода AddAutoShape.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте текст водяного знака, используя метод AddTextFrame.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы" subTitle="Используя C#, вы также можете добавить водяной знак в следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}