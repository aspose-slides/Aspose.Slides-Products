---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование HTML в PPTX на C++
url: /ru/cpp/conversion/html-to-pptx/
keywords: Преобразование HTML в PPTX, HTML в PPTX, PowerPoint, HTML, PPTX, C++ API, C++ Library
description: Преобразование HTML в PPTX на C++. Используйте API библиотеки C++ для преобразования HTML в PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование HTML в PPTX на C++" h2="Мощный кроссплатформенный C++ API для преобразования HTML в PPTX с использованием кода C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование HTML в PPTX на C++" variant="code" %}}

Используя [**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/), вы можете преобразовать HTML-документ в презентацию PowerPoint всего несколькими строками кода:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код C++ для преобразования HTML в PPTX" >}}
```cpp
auto presentation = System::MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование HTML в PPTX с помощью Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — это мощная библиотека C++, используемая для создания, преобразования и управления презентациями PowerPoint, PDF-файлами, HTML-документами и другими документами. файлы. Когда вы конвертируете HTML в PPTX, вы, по сути, перемещаете содержимое HTML-документа на слайды презентации PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как конвертировать HTML в PPTX на C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides для C++**. См. [**Установка**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте библиотеку в качестве ссылки в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите документ HTML, который вы хотите преобразовать в PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните полученный файл как презентацию PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатный онлайн-конвертер"
  description="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования PowerPoint" subTitle="Вы также можете конвертировать файлы в других форматах в PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
