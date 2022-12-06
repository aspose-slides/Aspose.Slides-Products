---
title: Объединение изображений PNG в C#
url: /ru/net/merger/png-to-png/
keywords: Объединение PNG, PNG в PNG, объединение PNG, объединение PNG, API C#, библиотека .NET
description: Слияние PNG с PNG в C#. Используйте API библиотеки .NET для объединения файлов PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Объединить PNG в C#" h2="Мощный кроссплатформенный .NET API для объединения изображений PNG с использованием кода C# на платформах NET Framework, .NET Core, Windows Azure, Mono или Xamarin." >}}

{{% blocks/products/pf/feature-page-section h2="Объединение PNG в PNG с помощью Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ru/net/) — мощная библиотека .NET, используемая для объединения презентаций, изображений и других файлов и управления ими. Когда вы объединяете PNG в PNG, вы эффективно объединяете два изображения, чтобы получить одно изображение.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Объединить PNG в PNG в C#" %}}
Используя [**Aspose.Slides для .NET**](https://products.aspose.com/slides/ru/net/), вы можете быстро объединять файлы PNG всего несколькими строками кода.

{{% blocks/products/pf/agp/code-block title="Код С# для объединения PNG в PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save($"merged-image.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как объединить PNG в C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для .NET**. См. [**Установка**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте библиотеку в качестве ссылки в свой проект.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите файлы PNG, которые вы хотите объединить в качестве рамок для картин.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученное изображение в формате PNG.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Объединить другие файлы" subTitle="Вы также можете комбинировать файлы в других форматах, чтобы получить один файл." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/png-to-pdf/" name="PNG TO PDF" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}