---
title: Редактировать PPT в C++
url: /ru/cpp/editor/ppt/
keywords: Редактировать PPT, Редактировать PowerPoint, PPT, PowerPoint, C++ API, C++ Library
description: Редактировать PPT в C++. Используйте API библиотеки C++ для редактирования презентации PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Редактировать PPT в C++" h2="Высокоскоростная кроссплатформенная библиотека C++ для редактирования PPT с использованием кода C++." >}}

{{% blocks/products/pf/feature-page-section h2="Редактировать PPT с помощью Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — это мощная библиотека C++, используемая для управления и редактирования презентаций. Вы можете отредактировать презентацию PPT, добавив в нее новую строку текста. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Редактировать PPT в C++" %}}
Используя [**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/), вы можете добавить новую строку текста в документ PPT, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код C++ для редактирования PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как редактировать PPT в C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для C++**. См. [**Установка**](https://docs.aspose.com/slides/cpp/installation/).
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}