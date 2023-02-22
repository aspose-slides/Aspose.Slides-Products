---
title: Преобразование изображения в PPT на C#
url: /ru/net/conversion/image-to-ppt/
keywords: Преобразование изображения в PPT, изображение в PPT, PowerPoint, изображение, PPT, C# API, библиотека .NET.
description: Преобразование изображения в PPT на C#. Используйте API библиотеки .NET для преобразования изображения в PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование изображения в PPT на C#" h2="Мощный кроссплатформенный .NET API для преобразования изображения в PPT с использованием кода C# на платформах NET Framework, .NET Core, Windows Azure, Mono или Xamarin." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование изображения в формат PPT с помощью Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ru/net/) — мощная библиотека .NET, используемая для создания, преобразования и управления презентациями PowerPoint, PDF-файлами, HTML-документами, и другие файлы. Когда вы конвертируете изображение в формат PPT, вы, по сути, создаете презентацию PowerPoint, содержащую слайды на основе этих изображений.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Преобразование изображения в PPT на C#" %}}
Используя [**Aspose.Slides for .NET**](https://products.aspose.com/slides/ru/net/), вы можете преобразовать изображение в презентацию PowerPoint всего несколькими строками кода:

{{% blocks/products/pf/agp/code-block title="Код С# для преобразования изображения в PPT" offSpacer="true" %}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как преобразовать изображение в PPT на С#" >}}


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
Загрузите изображение, которое вы хотите преобразовать в формат PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученный файл как презентацию PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования PowerPoint" subTitle="Вы также можете конвертировать файлы в других форматах в PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}