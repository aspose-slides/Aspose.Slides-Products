---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование JPG в PPT на C++
url: /ru/cpp/conversion/jpg-to-ppt/
keywords: Преобразование JPG в PPT, JPG в PPT, PowerPoint, JPG, PPT, API C++, библиотеку C++
description: Конвертируйте JPG в PPT на C++. Используйте API библиотеки C++ для преобразования изображений JPG в PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование JPG в PPT на C++" h2="Мощный кроссплатформенный C++ API для преобразования JPG в PPT с использованием кода C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование JPG в PPT на C++" variant="code" %}}

Используя [**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/), вы можете преобразовать изображение JPG в презентацию PowerPoint, написав всего несколько строк кода:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код C++ для преобразования JPG в PPT" >}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Конвертируйте JPG в PPT с помощью Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — это мощная библиотека C++, используемая для создания, преобразования и управления презентациями PowerPoint, PDF-файлами, HTML-документами и другими документами. файлы. Когда вы конвертируете JPG в PPT, вы, по сути, создаете презентацию PowerPoint, содержащую слайды на основе изображений JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как конвертировать JPG в PPT на С++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides для C++**. См. [**Установка**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте библиотеку в качестве ссылки в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите изображение JPG, которое вы хотите преобразовать в PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните полученный файл как презентацию PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Создано на основе Aspose.Slides" title="Конвертировать JPG в PPT онлайн" description="Бесплатное приложение Aspose.Slides Conversion создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами JPG." button="Открыть Aspose.Slides Conversion" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" upload="Перетащите или загрузите файл" saveAs="Сохранить как" convert="Конвертировать" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides конвертирует файлы, прежде чем писать код.
- Загрузите файлы JPG и сохраните их в PPT.
- Скачайте результат или конвертируйте другие файлы.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования PowerPoint" subTitle="Вы также можете конвертировать файлы в других форматах в PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
