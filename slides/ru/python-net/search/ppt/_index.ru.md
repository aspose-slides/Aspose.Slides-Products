---
title: Поиск текста в файлах презентаций PPT с использованием Python
url: /ru/python-net/search/ppt/
keywords: поиск слов в PPT, поиск и замена текста в PPT, поиск текста в PPT Презентация
description: Исходный код Python для поиска текста в PPT презентации.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Поиск текста PPT с использованием Python" h2="Создавайте собственные приложения Python для поиска и замены текста в файлах презентаций с помощью серверных API. Узнайте, как найти все вхождения определенного слова или фразы в презентационных документах. Поиск текста по точному совпадению данных и регулярному выражению." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Поиск и замена текста PPT Презентация через Python" %}}
Базовый поиск документа и замена текста в содержимом, комментариях, заметках к слайду или метаданных с помощью API Aspose.Slides for Python via .NET можно выполнить с помощью всего нескольких строк кода. Используйте сопоставление регулярных выражений и регистр символов для поиска текста в презентации. Поиск текста в заголовках, содержимом, нижнем колонтитуле или верхнем колонтитуле.
{{% blocks/products/pf/agp/code-block title="Поиск текста PPT Презентация с использованием Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как искать текст в PPT через Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для поиска текстовых файлов PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPT экземпляром Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Используйте метод [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/), чтобы найти и заменить текст.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Онлайн PPT Искать живые демонстрации" sectionDescription="Ищите и заменяйте текст в содержимом, комментариях или метаданных в документах PPT прямо сейчас." >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы поиска" subTitle="Используя Python, Вы также можете искать текст в следующих форматах:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}