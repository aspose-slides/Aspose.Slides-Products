---
title: Преобразование PNG в PDF в C++
url: /ru/cpp/conversion/png-to-pdf/
keywords: PNG в PDF, преобразовать PNG в PDF, API C++, библиотеку C++, PNG, PDF
description: Преобразование PNG в PDF в C++. Используйте API библиотеки C++ для преобразования файлов PNG в файлы PDF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PNG в PDF в C++" h2="Высокоскоростная и кроссплатформенная библиотека C++, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование PNG в PDF в C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — мощная библиотека C++ для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования PNG в PDF. Используя **Aspose.Slides for C++**, любой разработчик или приложение может преобразовать файлы PNG в PDF всего несколькими строками кода C++.

Как современный API обработки документов, Aspose.Slides для C++ быстро экспортирует файлы PNG в форматы файлов PDF. Библиотека Aspose PowerPoint позволяет конвертировать PNG в PDF и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PNG в PDF с помощью C++" %}}
Чтобы преобразовать PNG в PDF, вам нужно будет создать презентацию из файла PNG и сохранить его как PDF.

{{% blocks/products/pf/agp/code-block title="Код C++ для преобразования PNG в PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PNG в PDF с помощью Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования PNG в PDF в C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для C++**](https://products.aspose.com/slides/ru/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы PNG в C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать PNG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PNG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}