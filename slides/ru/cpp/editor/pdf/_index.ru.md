---
title: Редактировать PDF на С++
url: /ru/cpp/editor/pdf/
keywords: Редактировать PDF, PDF, API C++, библиотеку C++
description: Редактировать PDF на С++. Используйте API библиотеки C++ для редактирования PDF-документа
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Редактировать PDF на С++" h2="Высокоскоростная и кроссплатформенная библиотека C++ для редактирования PDF с использованием кода C++." >}}

{{% blocks/products/pf/feature-page-section h2="Редактируйте PDF с помощью Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — это мощная библиотека C++, используемая для управления и редактирования презентаций, документов PDF и других файлов. Вы можете редактировать PDF-документ, добавляя в него новую строку текста. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Редактировать PDF на С++" %}}
Используя [**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/), вы можете добавить новую строку текста в документ PDF, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код C++ для редактирования PDF" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как редактировать PDF на С++" >}}


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
Загрузите документ PDF, который вы хотите отредактировать.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте новую строку текста.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните измененный файл PDF.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Редактировать другие файлы" subTitle="Вы также можете редактировать файлы в других форматах" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}