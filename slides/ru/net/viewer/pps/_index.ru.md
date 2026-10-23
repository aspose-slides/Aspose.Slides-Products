---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Просмотр PPS на C#
keywords: Просмотр PPS, Открыть PPS, Просмотрщик PPS, PPS, PowerPoint, C# API, Библиотека .NET
weight: 7110
url: /ru/net/viewer/pps/ 
description: Просматривайте файлы PPS на C#. Открывайте файлы презентаций и сохраняйте их в HTML с помощью Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Просмотр PPS на C#" h2="C# API для открытия файлов PPS и сохранения их в адаптивный HTML."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Просмотр PPS с помощью Aspose.Slides" %}}

Для просмотра файлов PPS используйте [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — мощный, функциональный и простой в использовании API для C#. Откройте менеджер пакетов [NuGet](https://www.nuget.org/packages/aspose.slides.net), найдите **Aspose.Slides** и установите пакет. Также можно выполнить следующую команду в консоли диспетчера пакетов.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Команда консоли диспетчера пакетов" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

С помощью [**Aspose.Slides for .NET**](/slides/ru/net/) можно загрузить файл PPS и сохранить его в адаптивный HTML несколькими строками кода.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код C# для просмотра PPS" >}}
```cs
using var presentation = new Presentation("presentation.pps");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как просмотреть PPS на C#" intro="Aspose.Slides позволяет просматривать файлы PPS с помощью всего нескольких строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides for .NET**. См. [**Установка**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл `PPS` с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте объект `ResponsiveHtmlController` для адаптивного вывода HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте объект `HtmlOptions` и задайте свойство `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните файл PPS в формате HTML с помощью `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные требования" intro="Aspose.Slides for .NET поддерживает все основные операционные системы. Убедитесь, что выполнены следующие условия." %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Windows Azure, Mono или Xamarin
- Среда разработки, например Microsoft Visual Studio
- Ссылка на Aspose.Slides for .NET в вашем проекте

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Создано на основе Aspose.Slides" title="Просматривайте файлы PPS онлайн" description="Бесплатное приложение Aspose.Slides Viewer создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPS." button="Открыть Aspose.Slides Viewer" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides отображает ваши файлы, ещё до написания кода.
- Загрузите файл PPS и сразу просмотрите его слайды.
- Работает на компьютере и на телефоне, без PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Просмотр других файлов" subTitle="Вы также можете открывать и просматривать презентации в других форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/odp/" name="ODP" description="Презентация OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/otp/" name="OTP" description="Шаблон презентации OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/pot/" name="POT" description="Шаблон PowerPoint 97–2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/potm/" name="POTM" description="Шаблон PowerPoint с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/potx/" name="POTX" description="Шаблон PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/ppsm/" name="PPSM" description="Демонстрация PowerPoint с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/ppsx/" name="PPSX" description="Демонстрация PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/ppt/" name="PPT" description="Презентация PowerPoint 97–2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/pptm/" name="PPTM" description="Презентация PowerPoint с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/viewer/pptx/" name="PPTX" description="Презентация PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
