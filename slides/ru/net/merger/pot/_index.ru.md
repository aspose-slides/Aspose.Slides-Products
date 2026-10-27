---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Слияние файлов POT через .NET
weight: 7360
url: /ru/net/merger/pot/ 
description: Исходный код C# для объединения документов POT на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Объединение форматов POT в C#" h2="Нативное и высокопроизводительное слияние документов POT с использованием серверных API-интерфейсов Aspose.Slides для .NET без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Как объединить файл POT с помощью C#" %}}

Чтобы объединить файл POT, мы будем использовать
 [Aspose.Slides для .NET](https://products.aspose.com/slides/ru/net)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для работы с документами и слияния для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 менеджер пакетов, поиск
 **Aspose.Slides**
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Команда" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Объединение файлов POT — C#" >}}
```cs
var ps1 = new Presentation("presen1.pot");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first POT presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Шаги по слиянию файлов POT в C#" intro="Базовое слияние и объединение документов с помощью API [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net) можно выполнить с помощью всего нескольких строк кода." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите все файлы POT с полным путем.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сделайте один документ в качестве базового файла{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите соответствующий метод для объединения и объединения файлов один за другим.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите метод Save() и передайте имя файла (полный путь) и формат (POT) в качестве параметра.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Теперь вы можете открыть и использовать файл POT в Microsoft Office, Adobe PDF или любой другой совместимой программе.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Системные Требования" intro="Наши API поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе выполнены следующие предварительные условия." %}}

- Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
- Среда разработки, такая как Microsoft Visual Studio
- Aspose.Slides для .NET DLL, на которую ссылается ваш проект - Установите из NuGet, используя кнопку «Загрузить» выше

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Объединить PDF-файлы онлайн"
  description="[Как объединить PDF в Python](https://products.aspose.com/slides/ru/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

Файлы с расширением .POT — это двоичные шаблоны презентаций Microsoft PowerPoint. Формат относится к семейству форматов файлов PowerPoint 97-2003. Файлы POT хранят макеты слайдов, темы, стили, фоны, цветовые схемы, шрифты и другое форматирование для повторного использования при создании новых презентаций.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы слияния" subTitle="Используя C#, можно также объединять многие другие форматы файлов, в том числе." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/odp/" name="ODP" description="Формат презентации OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/otp/" name="OTP" description="Стандартный формат OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/potm/" name="POTM" description="Файл шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/potx/" name="POTX" description="Презентация шаблона Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/pps/" name="PPS" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/ppsm/" name="PPSM" description="Слайд-шоу с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/ppsx/" name="PPSX" description="Слайд-шоу PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/pptm/" name="PPTM" description="Файл презентации с поддержкой макросов" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/merger/pptx/" name="PPTX" description="Формат презентации Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
