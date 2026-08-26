---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# .NET PowerPoint Processing API | Aspose.Slides
weight: 1890
slidesIndexRebuild: true
url: /net/
description: Aspose.Slides for .NET is a C# PowerPoint API for creating, editing, converting, and processing presentations programmatically.
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR .NET · ON-PREMISES LIBRARY · NO MICROSOFT OFFICE REQUIRED"
  h1="PowerPoint files, from C#."
  sub="Aspose.Slides for .NET creates, edits, converts and renders PowerPoint and OpenDocument presentations from managed code. One NuGet package, running in your own process on Windows, Linux, macOS or a container — no Office install, no COM automation, no display server."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/net/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/net/"
  note="Full API on trial · watermark on output"
  moreText="Java, Python, C++, Node.js, Android and more" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn=".NET Framework, .NET Core and later, Mono and Xamarin.Android. Callable over COM interop from PHP, VBScript, Delphi and C++ on Windows. No Office, no GDI, no display server."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/net/)."
>}}

| Label | Install |
|---|---|
| CLI | dotnet add package Aspose.Slides.NET |
| Console | Install-Package Aspose.Slides.NET |
| Assembly | Aspose.Slides.dll |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 → 12 | Presentation formats read and written, including the pre-2007 binary `.ppt` container and OpenDocument `.odp`, plus 9 further export targets. |
| 1 | NuGet package. No native prerequisites to install alongside it. |
| 0 | Microsoft Office installs, GDI dependencies and X displays needed. A small Linux container is enough. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, C# as shipped. Pick the job on the left."
  lang="C#"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-.NET"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | One load, many output formats | PPTX → PDF / HTML / TIFF | The rendering engine ships with the library. | https://docs.aspose.com/slides/net/convert-powerpoint-ppt-and-pptx/ |
| Slide thumbnails | Images for a viewer or an index | PPTX → PNG | The scale factor controls output resolution. | https://docs.aspose.com/slides/net/create-slides-thumbnail-images/ |
| Charts from data | A real chart, still editable in PowerPoint | DATA → PPTX | Chart data lives in an embedded workbook. 82 chart types. | https://docs.aspose.com/slides/net/create-chart/ |
| Protect | Encrypt the deck and the PDF you hand out | PPTX → ENCRYPTED PPTX / PDF | The password applies to the deck and to the export. | https://docs.aspose.com/slides/net/password-protected-presentation/ |
| Merge | Clone slides between decks, layouts intact | PPTX + PPTX → PPTX | Layouts and masters travel with the cloned slide. | https://docs.aspose.com/slides/net/clone-slides/ |

```
using Aspose.Slides;
using Aspose.Slides.Export;

using var presentation = new Presentation("quarterly-review.pptx");

presentation.Save("review.pdf", SaveFormat.Pdf);
presentation.Save("review.html", SaveFormat.Html);
presentation.Save("review.tiff", SaveFormat.Tiff);
```

```
using var presentation = new Presentation("deck.pptx");

foreach (var slide in presentation.Slides)
{
    using var image = slide.GetImage(2f, 2f);
    image.Save($"slide-{slide.SlideNumber}.png", ImageFormat.Png);
}
```

```
using Aspose.Slides.Charts;

using var presentation = new Presentation();
var slide = presentation.Slides[0];

var chart = slide.Shapes.AddChart(ChartType.ClusteredColumn, 60, 60, 620, 400);
var cells = chart.ChartData.ChartDataWorkbook;

chart.ChartData.Categories.Add(cells.GetCell(0, 1, 0, "Q1"));
chart.ChartData.Categories.Add(cells.GetCell(0, 2, 0, "Q2"));
chart.ChartData.Series.Add(cells.GetCell(0, 0, 1, "Revenue"), chart.Type);

presentation.Save("report.pptx", SaveFormat.Pptx);
```

```
using var presentation = new Presentation("board-deck.pptx");

presentation.ProtectionManager.Encrypt("s3cret");

var options = new PdfOptions { Password = "s3cret" };
presentation.Save("board-deck.pdf", SaveFormat.Pdf, options);
```

```
using var target = new Presentation("master.pptx");
using var source = new Presentation("appendix.pptx");

foreach (var slide in source.Slides)
    target.Slides.AddClone(slide);

target.Save("combined.pptx", SaveFormat.Pptx);
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything here is supported in the .NET build. Where a grey note follows, the capability is delivered through a separate product or comes with a stated limit." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Managed code and one package, so the library deploys with the application — onto build agents, containers and servers unchanged."
  footText="Same object model on other platforms: Java, Python, C++, Node.js, Android, PHP, SharePoint and JasperReports."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| .NET Framework | Classic desktop, ASP.NET and Windows service workloads. | WINDOWS |
| .NET Core and .NET 5+ | Cross-platform applications, containers and cloud functions. | WINDOWS · LINUX · MACOS |
| Mono | Supported for non-Windows runtimes where Mono hosts the application. | LINUX · MACOS |
| Xamarin.Android | Presentation handling inside mobile applications. | ANDROID |
| COM interop | Callable from PHP, VBScript, Delphi and C++ on Windows. | WINDOWS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/net/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR .NET · PRODUCTS.ASPOSE.COM"
  barRight="POWERPOINT AUTOMATION WITHOUT MICROSOFT OFFICE"
>}}

## If you don't want a library

Aspose.Slides Cloud is a hosted REST API for loading, creating, editing and converting presentations.

- [cURL](https://products.aspose.cloud/slides/curl/)
- [.NET SDK](https://products.aspose.cloud/slides/net/)
- [Java SDK](https://products.aspose.cloud/slides/java/)
- [All low-code APIs →](https://products.aspose.cloud/slides/family/)

## No-code apps

- [Viewer](https://products.aspose.app/slides/viewer)
- [Conversion](https://products.aspose.app/slides/conversion)
- [Annotation](https://products.aspose.app/slides/annotation)
- [All apps →](https://products.aspose.app/slides/family)

## Resources

- [Documentation](https://docs.aspose.com/slides/net/)
- [API reference](https://reference.aspose.com/slides/net/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/net/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
