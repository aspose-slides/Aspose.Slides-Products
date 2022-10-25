---
title: Слияние PDF, PPT, PPTX и многих других форматов файлов с помощью C++
url: /ru/cpp/merger/
keywords: Слияние, объединение, PowerPoint, презентация, C++, Aspose
description: Объединяйте несколько файлов в форматах C++ PPT, PPTX, ODP, PDF, PNG, JPG и многих других.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Объединяйте Powerpoint, PDF, PPT или другие документы вместе на C++" h2="Высокоскоростная библиотека C++ для объединения PPT, PPTX, PDF, PNG, JPEG и других форматов." >}}

{{% blocks/products/pf/feature-page-section h2="Слияние PPT, PPTX, PDF с помощью C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — мощная библиотека C++ для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы объединения нескольких презентаций PPT/PPTX. Когда вы объединяете одну презентацию с другой, вы эффективно объединяете их слайды в одну презентацию, чтобы получить один файл. Aspose.Slides позволяет объединять две презентации разными способами. Вы можете объединять презентации со всеми их формами, стилями, текстами, форматированием, комментариями, анимацией и т. д., не беспокоясь о потере качества или данных.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Объединение презентаций PowerPoint в C++" %}}
Чтобы объединить презентации PowerPoint, вам нужно клонировать слайды из одной презентации в другую.

{{% blocks/products/pf/agp/code-block title="Слияние файлов PPTX с помощью C++" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Объединение презентаций с образцом слайдов с помощью C++" %}}
Этот код C++ демонстрирует, как объединить несколько презентаций в одну и применить стили из шаблона презентации образца слайдов. Таким образом, итоговая презентация сохранит исходное форматирование и будет содержать форматирование из мастер-слайда другой презентации.

{{% blocks/products/pf/agp/code-block title="Объединить несколько PPT в один в C++" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как объединить презентации с помощью Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для объединения двух файлов PPTX и сохранения результата в формате PDF на C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для C++**](https://docs.aspose.com/slides/cpp/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы PPTX на C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Объедините файлы PPTX, используя метод **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните презентацию и получите результат в виде одного PDF-файла.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы для слияния" subTitle="Вы также можете комбинировать другие форматы файлов. См. другие поддерживаемые форматы ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}