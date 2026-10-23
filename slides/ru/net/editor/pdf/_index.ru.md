---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Редактировать PDF в C#
url: /ru/net/editor/pdf/
keywords: Редактировать PDF, PDF, API C#, библиотеку .NET
description: Редактировать PDF на C#. Используйте API библиотеки .NET для редактирования PDF-документа
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Редактировать PDF в C#" h2="Мощный кроссплатформенный .NET API для редактирования PDF с использованием кода C# на платформах NET Framework, .NET Core, Windows Azure, Mono или Xamarin." related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Редактировать PDF в C#" variant="code" %}}

Используя [**Aspose.Slides для .NET**](https://products.aspose.com/slides/ru/net/), вы можете добавить новую строку текста в документ PDF, написав всего несколько строк кода.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код C# для редактирования PDF" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Редактируйте PDF с помощью Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ru/net/) — это мощная библиотека .NET, используемая для управления и редактирования презентаций, документов PDF и других файлов. Вы можете редактировать PDF-документ, добавляя в него новую строку текста.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как редактировать PDF в С#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите **Aspose.Slides для .NET**. См. [**Установка**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте библиотеку в качестве ссылки в свой проект.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Создайте экземпляр класса Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите документ PDF, который вы хотите отредактировать.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте новую строку текста.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните измененный файл PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Создано на основе Aspose.Slides" title="Редактируйте файлы PPTX онлайн" description="Бесплатное приложение Aspose.Slides Editor создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Editor" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides обрабатывает ваши файлы, ещё до написания кода.
- Загрузите файлы PPTX и сразу редактируйте их.
- Сохраните и скачайте отредактированный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Редактировать другие файлы" subTitle="Вы также можете редактировать файлы в других форматах" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
