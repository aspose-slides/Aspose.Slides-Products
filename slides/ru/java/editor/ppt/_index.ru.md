---
title: Редактировать PPT в Java
url: /ru/java/editor/ppt/
keywords: Редактировать PPT, Редактировать PowerPoint, PPT, PowerPoint, API Java, библиотеку Java
description: Редактировать PPT в Java. Используйте API библиотеки Java для редактирования презентации PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Редактировать PPT в Java" h2="Высокоскоростная и кроссплатформенная библиотека Java для редактирования PPT с использованием кода Java." >}}

{{% blocks/products/pf/feature-page-section h2="Редактировать PPT с помощью Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/) — это мощная библиотека Java, используемая для управления и редактирования презентаций. Вы можете отредактировать презентацию PPT, добавив в нее новую строку текста. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Редактировать PPT в Java" %}}
Используя [**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/), вы можете добавить новую строку текста в документ PPT, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код Java для редактирования PPT" offSpacer="true" %}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как редактировать PPT в Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для Java**. См. [**Установка**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте библиотеку в качестве ссылки в свой проект.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите презентацию PPT, которую хотите отредактировать.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте новую строку текста.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните измененный файл PowerPoint.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Редактировать другие файлы" subTitle="Вы также можете редактировать файлы в других форматах" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}