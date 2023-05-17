---
title: Редактировать файлы презентации ODP с помощью .NET
url: /ru/net/redaction/odp/
keywords: Исправить ODP, найти и заменить текст в ODP, обновить презентацию ODP
description: Исходный код C# для поиска и замены текста в презентации ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Исправьте ODP, используя C#" h2="Создавайте собственные приложения .NET для поиска и замены текста в файлах презентаций с помощью серверных API. Узнайте, как искать и заменять текст в содержимом, комментариях или метаданных презентаций ODP." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Редактировать презентацию ODP через C#" %}}
Базовый поиск документа и замена текста в содержимом, комментариях, заметках к слайду или метаданных с помощью API Aspose.Slides for .NET можно выполнить с помощью всего нескольких строк кода. Поиск и замена текста в PowerPoint и OpenOffice. Редактируйте текст, комментарии, метаданные в презентации с помощью сопоставления данных регулярных выражений.
{{% blocks/products/pf/agp/code-block title="Редактировать презентацию ODP, используя C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как редактировать ODP через C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для редактирования файлов ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите ODP экземпляром Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Используйте метод [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/), чтобы найти и заменить текст.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-редакция ODP Демонстрации в реальном времени" sectionDescription="Ищите и заменяйте текст в содержимом, комментариях или метаданных в документах ODP прямо сейчас." >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы редактирования" subTitle="Используя C#, вы также можете редактировать следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}