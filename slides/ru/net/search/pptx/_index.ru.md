---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Поиск текста в файлах презентаций PPTX с помощью .NET
url: /ru/net/search/pptx/
description: Исходный код C# для поиска текста в презентациях PPTX.
keywords: Поиск текста в PPTX, найти текст в PPTX, поиск по тексту презентации PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Поиск текста в файлах PPTX с помощью C#" h2="Создавайте приложения .NET, которые находят текст в презентациях с помощью серверных API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Поиск текста в презентации PPTX с помощью C#" variant="code" %}}

С [Aspose.Slides for .NET](/slides/ru/net/) можно искать текст в презентации PPTX. Получите текстовые рамки слайда с помощью `SlideUtil.GetAllTextBoxes`, а затем проверьте их значения `Text` на наличие нужной фразы.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Поиск текста в презентации PPTX с помощью C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как найти текст в презентации PPTX с помощью C#" intro="Выполните следующие шаги, чтобы найти текст в презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Получите нужный слайд из `Presentation.Slides` и присвойте его переменной.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Получите его текстовые рамки с помощью [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Проверьте, содержит ли значение `Text` каждой рамки нужную фразу.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Создано на основе Aspose.Slides" title="Поиск текста в файлах PPTX онлайн" description="Бесплатное приложение Aspose.Slides Search создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Search" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит текст, ещё до написания кода.
- Ищите в файле PPTX обычный текст или регулярные выражения.
- Скачайте найденные совпадения в виде текстового файла.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для поиска" subTitle="С помощью C# можно также искать текст в следующих форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
