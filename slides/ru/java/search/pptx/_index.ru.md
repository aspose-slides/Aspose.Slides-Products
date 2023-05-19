---
title: Поиск текста в файлах презентаций PPTX с использованием Java
url: /ru/java/search/pptx/
keywords: поиск слов в PPTX, поиск и замена текста в PPTX, поиск текста в PPTX Презентация
description: Исходный код Java для поиска текста в PPTX презентации.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Поиск текста PPTX с использованием Java" h2="Создавайте собственные приложения Java для поиска и замены текста в файлах презентаций с помощью серверных API. Узнайте, как найти все вхождения определенного слова или фразы в презентационных документах. Поиск текста по точному совпадению данных и регулярному выражению." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Поиск и замена текста PPTX Презентация через Java" %}}
Базовый поиск документа и замена текста в содержимом, комментариях, заметках к слайду или метаданных с помощью API Aspose.Slides for Java можно выполнить с помощью всего нескольких строк кода. Используйте сопоставление регулярных выражений и регистр символов для поиска текста в презентации. Поиск текста в заголовках, содержимом, нижнем колонтитуле или верхнем колонтитуле.
{{% blocks/products/pf/agp/code-block title="Поиск текста PPTX Презентация с использованием Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как искать текст в PPTX через Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для поиска текстовых файлов PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPTX экземпляром Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Используйте метод [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-), чтобы найти и заменить текст.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Онлайн PPTX Искать живые демонстрации" sectionDescription="Ищите и заменяйте текст в содержимом, комментариях или метаданных в документах PPTX прямо сейчас." >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы поиска" subTitle="Используя Java, Вы также можете искать текст в следующих форматах:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}