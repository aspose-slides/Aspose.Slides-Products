---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Скрытие данных в файлах презентаций PPT с помощью .NET
url: /ru/net/redaction/ppt/
description: Исходный код C# для поиска и замены текста в презентациях PPT.
keywords: Скрыть данные в PPT, найти и заменить текст в PPT, обновить презентацию PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Скрытие данных в файлах PPT с помощью C#" h2="Создавайте приложения .NET, которые находят и заменяют текст в презентациях с помощью серверных API." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Скрытие данных в презентации PPT с помощью C#" variant="code" %}}

С [Aspose.Slides for .NET](/slides/ru/net/) можно находить и заменять текст в презентации PPT. Используйте `Presentation.ReplaceText` с `TextSearchOptions`, чтобы управлять поиском, а затем сохраните изменённую презентацию.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Скрытие данных в презентации PPT с помощью C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как скрыть данные в презентации PPT с помощью C#" intro="Выполните следующие шаги, чтобы заменить текст в презентации PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPT с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) с `TextSearchOptions`, чтобы заменить нужный текст.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните изменённую презентацию с `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Создано на основе Aspose.Slides" title="Скрытие данных в файлах PPT онлайн" description="Бесплатное приложение Aspose.Slides Redaction создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Redaction" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит и заменяет текст, ещё до написания кода.
- Находите и заменяйте текст в файле PPT, в том числе с помощью регулярных выражений.
- Скачайте обработанный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для скрытия данных" subTitle="С помощью C# можно также скрывать данные в следующих форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
