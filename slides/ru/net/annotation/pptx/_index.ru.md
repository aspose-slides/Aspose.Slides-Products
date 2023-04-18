---
title: Удалить аннотацию PPTX с помощью .NET
weight: 4380
url: /ru/net/annotation/pptx/ 
description: Исходный код C# для удаления аннотаций формата PPTX на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Удалить комментарии и авторов комментариев из PPTX в C#" h2="Создавайте собственные приложения .NET для управления комментариями и авторами в файлах документов с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Удалить комментарии из PPTX через C#" %}}
Чтобы удалить аннотации из файла PPTX, мы будем использовать API [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net), который является многофункциональным, мощным и простым в использовании. API для работы с документами для платформы C#.
{{% blocks/products/pf/agp/code-block title="Удалить аннотации из PPTX — C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Как удалить комментарии из PPTX через C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для .NET**. См. [**Установка**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPTX с экземпляром класса Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Перебрать всех авторов загруженного PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Удалить все комментарии автора
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Удалить всех авторов в конце
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы аннотаций" subTitle="Используя C#, можно легко аннотировать другие форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}