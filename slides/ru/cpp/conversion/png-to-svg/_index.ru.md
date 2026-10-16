---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PNG в SVG в C++
url: /ru/cpp/conversion/png-to-svg/
keywords: PNG в SVG, преобразовать PNG в SVG, API C++, библиотеку C++, PNG, SVG
description: Преобразование PNG в SVG в C++. Используйте API библиотеки C++ для преобразования файлов PNG в файлы SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PNG в SVG в C++" h2="Высокоскоростная и кроссплатформенная библиотека C++, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PNG в SVG с помощью C++" variant="code" %}}

Чтобы преобразовать PNG в SVG, вам нужно будет создать презентацию из файла PNG и сохранить его как SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код C++ для преобразования PNG в SVG" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = pres->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PNG в SVG в C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — мощная библиотека C++ для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования PNG в SVG. Используя **Aspose.Slides for C++**, любой разработчик или приложение может преобразовать файлы PNG в SVG всего несколькими строками кода C++.

Как современный API обработки документов, Aspose.Slides для C++ быстро экспортирует файлы PNG в форматы файлов SVG. Библиотека Aspose PowerPoint позволяет конвертировать PNG в SVG и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать PNG в SVG с помощью Aspose.Slides for C++ API" intro="Это шаги для преобразования PNG в SVG в C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides для C++**](https://products.aspose.com/slides/ru/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы PNG в C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатный онлайн-конвертер"
  description="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Конвертировать PNG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PNG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
