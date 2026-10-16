---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование ODP в PPT через приложение C++
weight: 6230
url: /ru/cpp/conversion/odp-to-ppt/ 
description: Пример кода преобразования C++ для документа ODP в формат PPT. Используйте пример кода для пакетного преобразования ODP в PPT в любом приложении C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование ODP в PPT через C++" h2="Высокопроизводительное преобразование ODP в PPT с использованием библиотеки C++ без необходимости установки Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Как преобразовать ODP в PPT с помощью C++" %}}

Чтобы преобразовать ODP в PPT, мы будем использовать
 [Aspose.Slides для C++](https://products.aspose.com/slides/cpp/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C++. Вы можете загрузить его последнюю версию напрямую, просто открыв
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 менеджер пакетов, поиск
 Aspose.Slides.Cpp
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Команда" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Исходный код преобразования ODP в PPT C++" >}}
```cs
// Load the ODP.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.odp");
// Save in PPT format.
prs->Save(u"convertedFile.ppt", Aspose::Slides::Export::SaveFormat::Ppt);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Шаги по преобразованию ODP в PPT через C++" intro="Разработчики C++ могут легко преобразовать файл ODP в PPT, написав всего несколько строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл ODP с Aspose.Slides for C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод Сохранить().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Передайте путь к выходному файлу с расширением (PPT).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Файл PPT будет сохранен по указанному пути.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл PPT в совместимой программе.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Перед запуском кода примера преобразования C++ убедитесь, что выполнены следующие предварительные условия." %}}

- Microsoft Windows или совместимая ОС со средой выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
- Aspose.Slides for C++ DLL, на которые есть ссылки в вашем проекте.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="odp-to-ppt"
  title="Бесплатное приложение для преобразования ODP в PPT"
  description="[Попробуйте наше бесплатное приложение MP4 To MP3](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать ODP во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-bmp/" name="ODP TO BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-emf/" name="ODP TO EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-gif/" name="ODP TO GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-html/" name="ODP TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-otp/" name="ODP TO OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pdf/" name="ODP TO PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-png/" name="ODP TO PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pot/" name="ODP TO POT" description="Файлы шаблонов Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-potm/" name="ODP TO POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-potx/" name="ODP TO POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pps/" name="ODP TO PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Формат презентации Open XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-svg/" name="ODP TO SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-xml/" name="ODP TO XML" description="расширяемый язык разметки" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cpp/conversion/odp-to-xps/" name="ODP TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
