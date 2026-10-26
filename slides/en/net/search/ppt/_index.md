---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Search Text in PPT Presentation Files using .NET
url: /net/search/ppt/
keywords: Search Text in PPT, Find Text in PPT, Search PPT Presentation Text
description: C# source code to search text in PPT presentations.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Search Text in PPT Files using C#" h2="Build .NET apps that find text in presentations with server-side APIs." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Search Text in a PPT Presentation using C#" variant="code" %}}

With [Aspose.Slides for .NET](/slides/net/), you can search text in a PPT presentation. Retrieve text frames from a slide with `SlideUtil.GetAllTextBoxes`, then inspect their `Text` values for the required phrase.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Search Text in a PPT Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Search Text in a PPT Presentation using C#" intro="Follow these steps to search text in a PPT presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Get the required slide from `Presentation.Slides` and assign it to a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Retrieve its text frames with [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Check the `Text` value of each frame for the required phrase.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Search Formats" subTitle="Using C#, you can also search text in the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
