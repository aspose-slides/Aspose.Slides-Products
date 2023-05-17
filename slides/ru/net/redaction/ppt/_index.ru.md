---
title: Редактировать файлы презентации PPT с помощью .NET
url: /ru/net/redaction/ppt/
keywords: Исправить PPT, найти и заменить текст в PPT, обновить презентацию PPT
description: Исходный код C# для поиска и замены текста в презентации PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Исправьте PPT, используя C#" h2="Создавайте собственные приложения .NET для поиска и замены текста в файлах презентаций с помощью серверных API. Узнайте, как искать и заменять текст в содержимом, комментариях или метаданных презентаций PPT." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Редактировать презентацию PPT через C#" %}}
Базовый поиск документа и замена текста в содержимом, комментариях, заметках к слайду или метаданных с помощью API Aspose.Slides for .NET можно выполнить с помощью всего нескольких строк кода. Поиск и замена текста в PowerPoint и OpenOffice. Редактируйте текст, комментарии, метаданные в презентации с помощью сопоставления данных регулярных выражений.
{{% blocks/products/pf/agp/code-block title="Редактировать презентацию PPT, используя C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как редактировать PPT через C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для редактирования файлов PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPT экземпляром Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Используйте метод [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/), чтобы найти и заменить текст.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-редакция PPT Демонстрации в реальном времени" sectionDescription="Ищите и заменяйте текст в содержимом, комментариях или метаданных в документах PPT прямо сейчас." >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы редактирования" subTitle="Используя C#, вы также можете редактировать следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}