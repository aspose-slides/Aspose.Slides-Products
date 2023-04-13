---
title: Преобразование PPTX в Word на C++
url: /ru/cpp/conversion/pptx-to-word/
keywords: Преобразование PPTX в Word, PPTX в Word, PPTX в DOC, PowerPoint в Word, C++ API, C++ Library, CPP
description: Преобразование PPTX в Word на C++. Используйте API библиотеки C++ для преобразования PowerPoint в Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PPTX в Word на C++" h2="Мощный кроссплатформенный C++ API для преобразования PowerPoint в Word с использованием кода C++ без использования Microsoft PowerPoint или Office." >}}

{{% blocks/products/pf/feature-page-section h2="Конвертируйте PowerPoint в Word с помощью Aspose.Slides и Aspose.Words" %}}

[**Aspose.Slides для C++**](https://products.aspose.com/slides/ru/cpp/) и [**Aspose.Words для C++**](https://products.aspose.com/ words/cpp/) — это мощные библиотеки C++, используемые для управления и преобразования презентаций PowerPoint, документов Word и других файлов. Когда вы конвертируете PowerPoint в Word, вы, по сути, перемещаете содержимое слайдов презентации на страницы документа Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Преобразование PowerPoint в Word на C++" %}}
Вы можете быстро преобразовать PPTX в Word, написав всего несколько строк кода.

{{% blocks/products/pf/agp/code-block title="Код C++ для преобразования PowerPoint в Word" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PPTX в Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Установите **Aspose.Slides для C++** и **Aspose.Words для C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation и класса Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите презентацию PPTX, которую вы хотите преобразовать в Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создавайте изображения и тексты на основе содержимого слайдов.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохраните полученный документ Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Бесплатный онлайн-конвертер" sectionDescription="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PowerPoint в файлы других форматов." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}