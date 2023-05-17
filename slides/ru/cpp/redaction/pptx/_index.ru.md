---
title: Редактировать файлы презентации PPTX с помощью C++
url: /ru/cpp/redaction/pptx/
keywords: Исправить PPTX, найти и заменить текст в PPTX, обновить презентацию PPTX
description: Исходный код C++ для поиска и замены текста в презентации PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Исправьте PPTX, используя C++" h2="Создавайте собственные приложения C++ для поиска и замены текста в файлах презентаций с помощью серверных API. Узнайте, как искать и заменять текст в содержимом, комментариях или метаданных презентаций PPTX." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Редактировать презентацию PPTX через C++" %}}
Базовый поиск документа и замена текста в содержимом, комментариях, заметках к слайду или метаданных с помощью API Aspose.Slides for C++ можно выполнить с помощью всего нескольких строк кода. Поиск и замена текста в PowerPoint и OpenOffice. Редактируйте текст, комментарии, метаданные в презентации с помощью сопоставления данных регулярных выражений.
{{% blocks/products/pf/agp/code-block title="Редактировать презентацию PPTX, используя C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как редактировать PPTX через C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для редактирования файлов PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPTX экземпляром Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Используйте метод [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/), чтобы найти и заменить текст.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-редакция PPTX Демонстрации в реальном времени" sectionDescription="Ищите и заменяйте текст в содержимом, комментариях или метаданных в документах PPTX прямо сейчас." >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы редактирования" subTitle="Используя C++, вы также можете редактировать следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}