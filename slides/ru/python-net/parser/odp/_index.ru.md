---
title: Извлечение текста и изображений из файлов ODP с помощью Python
url: /ru/python-net/parser/odp/
keywords: анализировать ODP с помощью Python, синтаксический анализатор ODP Python, извлекать данные из ODP в Python, извлекать текст из ODP с помощью Python, извлекать изображения из ODP с помощью Python
description: Исходный код Python для анализа презентации ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Извлечение текста и изображений из презентации ODP с помощью Python" h2="Создавайте собственные приложения Python для извлечения текста, изображений, видео- и аудиофайлов из PowerPoint с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Извлечь текст из презентации ODP через Python" %}}
Чтобы просмотреть текст всей презентации, используйте статический метод [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/), предоставляемый классом SlideUtil. Приведенный ниже код сканирует текст и информацию о форматировании из презентации, включая мастер-слайды.
{{% blocks/products/pf/agp/code-block title="Извлечение текста из презентации ODP с использованием Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a ODP file
with slides.Presentation("pres.odp") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the ODP
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как извлечь текст из ODP через Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для разбора файлов ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите ODP с экземпляром Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Получите массив объектов TextFrame со всех слайдов в ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Перебрать массив TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Перебирать абзацы в текущем TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Перебирать части в текущем абзаце
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Получить текст в текущей части
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы разбора" subTitle="Используя Python, Вы также можете сканировать следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}