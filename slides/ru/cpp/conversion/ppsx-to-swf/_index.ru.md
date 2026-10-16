---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PPSX в SWF через приложение C++
url: /ru/cpp/conversion/ppsx-to-swf/ 
description: Пример кода преобразования C++ для документа PPSX в формат SWF. Используйте пример кода для пакетного преобразования PPSX в SWF в любом приложении C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PPSX в SWF через C++" h2="Высокопроизводительное преобразование PPSX в SWF с использованием библиотеки C++ без необходимости установки Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Как конвертировать PPSX в SWF с помощью C++" %}}

Чтобы преобразовать PPSX в SWF, мы будем использовать <a href="https://products.aspose.com/slides/ru/cpp">Aspose.Slides for C++</a> API, который представляет собой многофункциональный, мощный и простой в использовании API для работы с документами и преобразования для платформы C++. Вы можете загрузить его последнюю версию напрямую, просто открыв <a href="https://www.nuget.org/packages/aspose.slides">диспетчер пакетов NuGet</a>, найдите <b>Aspose.Slides.Cpp. </b> и установите. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Команда" >}}
```cs

PM> Install-Package Aspose.SLIDES.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Исходный код преобразования PPSX в SWF C++" >}}
```cs
// Load the PPSX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Шаги по преобразованию PPSX в SWF через C++" intro="API Aspose.SLIDES позволяет разработчикам легко конвертировать файл PPSX в SWF всего за несколько строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPSX с Aspose.Slides for C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод Сохранить().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Передайте путь к выходному файлу с расширением (SWF).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}SWF-файл будет сохранен по указанному пути.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте SWF-файл в совместимой программе.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Aspose.SLIDES for C++ поддерживается на всех основных платформах и операционных системах. Пожалуйста, убедитесь, что у вас есть следующие предпосылки." %}}

- Microsoft Windows или совместимая ОС со средой выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
- Aspose.Slides for C++ DLL, на которые есть ссылки в вашем проекте.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Бесплатное приложение для преобразования PPSX в SWF"
  description="[Попробуйте наше бесплатное приложение Text To Gif](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PPSX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint Template Presentation" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Open XML presentation Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Спецификации XML-бумаги" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
