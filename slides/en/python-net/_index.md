---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Aspose.Slides for Python: PowerPoint API for PPTX and PPT"
weight: 5860
slidesIndexRebuild: true
url: /python-net/
description: "Python library for creating, editing, converting, and processing presentations in formats such as PPT, PPTX, PPS, POT, PPSX, PPTM, PPSM, POTX, POTM, and ODP, with support for PDF output."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR PYTHON VIA .NET · ON-PREMISES LIBRARY · NO MICROSOFT OFFICE REQUIRED"
  h1="PowerPoint files, from Python."
  sub="Aspose.Slides for Python via .NET creates, edits, converts and renders PowerPoint and OpenDocument presentations from ordinary Python code. It is a binding over the Aspose.Slides .NET engine, not a pure-Python rewrite: one wheel from PyPI carries the compiled engine and the .NET runtime it needs, so there is no .NET SDK to install and no JVM anywhere in the stack. Python 3.5 or later on Windows, Linux or macOS, running in your own process - on Linux and macOS the wheel also wants libgdiplus and the native dependencies of the .NET Core runtime."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/python-net/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/python-net/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows, Linux and macOS on CPython 3.5 or later. The wheel is a compiled binding rather than pure Python, and it ships the .NET runtime it needs inside the package, so there is no .NET SDK to install and no JVM in the stack. Linux and macOS additionally need libgdiplus (apt-get install libgdiplus, or brew install mono-libgdiplus), the native dependencies of the .NET Core runtime and a Python built with a shared libpython; on Windows the wheel alone is enough. Containers are fine, and a minimal image should add libgdiplus and at least one font package."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| CLI | pip install aspose-slides |
| Import | import aspose.slides as slides |
| Linux | apt-get install -y libgdiplus |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 1 | PyPI wheel, aspose-slides. It carries the compiled .NET engine inside it, so there is no .NET SDK to install and no JVM to run. |
| 0 / 1 | Microsoft Office installs needed, and one native package on Linux and macOS: libgdiplus. On Windows the wheel alone is enough. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Python as shipped. Pick the job on the left."
  lang="PYTHON"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-Python-via-.NET"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Load a deck and write it out in another format, in three lines. | PPTX -> PDF / HTML / TIFF | The bundled engine does the rendering, so the same input produces the same output on Windows, Linux and macOS. | https://docs.aspose.com/slides/python-net/convert-powerpoint-to-pdf/ |
| Slide thumbnails | Render every slide to a raster image at whatever scale you ask for. | PPTX -> one PNG per slide | get_image returns a Modern API image and closes as a context manager, so aspose.pydrawing never enters your code. | https://docs.aspose.com/slides/python-net/presentation-viewer/ |
| Charts from data | Build a native PowerPoint chart from Python values, not a pasted picture. | Python lists -> native chart | The chart keeps its own data workbook, so whoever opens the deck can edit the numbers in PowerPoint. | https://docs.aspose.com/slides/python-net/create-chart/ |
| Protect | Encrypt a deck with an opening password and mark it read-only. | PPTX -> encrypted PPTX | This is real document encryption, so PowerPoint asks for the password itself and the file is unreadable without it. | https://docs.aspose.com/slides/python-net/password-protected-presentation/ |
| Merge | Clone slides out of several decks into one, resizing anything that does not fit. | N decks -> 1 deck | add_clone brings the layout and master across with the slide, so source formatting survives the move. | https://docs.aspose.com/slides/python-net/merge-presentation/ |

```
import aspose.slides as slides

with slides.Presentation("quarterly-review.pptx") as presentation:
    presentation.save("quarterly-review.pdf", slides.export.SaveFormat.PDF)
    presentation.save("quarterly-review.html", slides.export.SaveFormat.HTML)

    tiff_options = slides.export.TiffOptions()
    tiff_options.dpi_x = 300
    tiff_options.dpi_y = 300
    tiff_options.compression_type = slides.export.TiffCompressionTypes.LZW
    presentation.save("quarterly-review.tiff", slides.export.SaveFormat.TIFF, tiff_options)
```

```
import aspose.slides as slides

with slides.Presentation("quarterly-review.pptx") as presentation:
    for index, slide in enumerate(presentation.slides, start=1):
        with slide.get_image(2.0, 2.0) as image:
            image.save(f"slide-{index}.png", slides.ImageFormat.PNG)
```

```
import aspose.slides as slides
import aspose.slides.charts as charts

quarters = ["Q1", "Q2", "Q3", "Q4"]
revenue = [128.4, 141.9, 137.2, 168.5]

with slides.Presentation() as presentation:
    slide = presentation.slides[0]
    chart = slide.shapes.add_chart(charts.ChartType.CLUSTERED_COLUMN, 50, 50, 620, 400)
    chart.has_title = True
    chart.chart_title.add_text_frame_for_overriding("Revenue by quarter")

    workbook = chart.chart_data.chart_data_workbook
    chart.chart_data.series.clear()
    chart.chart_data.categories.clear()

    for row, quarter in enumerate(quarters, start=1):
        chart.chart_data.categories.add(workbook.get_cell(0, row, 0, quarter))

    series = chart.chart_data.series.add(workbook.get_cell(0, 0, 1, "Revenue"), chart.type)
    for row, value in enumerate(revenue, start=1):
        series.data_points.add_data_point_for_bar_series(workbook.get_cell(0, row, 1, value))

    presentation.save("revenue.pptx", slides.export.SaveFormat.PPTX)
```

```
import aspose.slides as slides

with slides.Presentation("quarterly-review.pptx") as presentation:
    presentation.protection_manager.encrypt("open-sesame")
    presentation.protection_manager.set_write_protection("edit-me")
    presentation.save("quarterly-review-locked.pptx", slides.export.SaveFormat.PPTX)

load_options = slides.LoadOptions()
load_options.password = "open-sesame"

with slides.Presentation("quarterly-review-locked.pptx", load_options) as presentation:
    print(presentation.protection_manager.is_encrypted)
    print(presentation.protection_manager.is_write_protected)
```

```
import aspose.slides as slides

parts = ["intro.pptx", "results.pptx", "appendix.pptx"]

with slides.Presentation(parts[0]) as deck:
    for part in parts[1:]:
        with slides.Presentation(part) as source:
            if (source.slide_size.size.width != deck.slide_size.size.width
                    or source.slide_size.size.height != deck.slide_size.size.height):
                source.slide_size.set_size(
                    deck.slide_size.size.width,
                    deck.slide_size.size.height,
                    slides.SlideSizeScaleType.ENSURE_FIT)

            for slide in source.slides:
                deck.slides.add_clone(slide)

    deck.save("handbook.pptx", slides.export.SaveFormat.PPTX)
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="One object model covers the whole file - slides, layouts and masters, shapes and text, tables, charts, SmartArt, animation, media, comments and speaker notes - all of it reachable as ordinary Python objects." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model on other platforms: .NET, Java, C++, Node.js and PHP, reading and writing the same formats and producing the same output."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| Aspose.Slides for .NET | The engine this binding wraps, used directly from C#, VB.NET or F# as a NuGet package. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Java | A separate pure-Java build of the same object model. It runs on a JVM rather than on the .NET runtime. | JAVA SE 8 OR LATER |
| Aspose.Slides for C++ | Native headers and libraries for C++ projects, with no managed runtime in the process at all. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Node.js via .NET | The same bundled .NET engine behind a JavaScript binding, installed from npm. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for PHP via Java | A PHP binding over the Java build, so it needs a JVM and the PHP-Java bridge alongside PHP. | JVM REQUIRED |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/python-net/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR PYTHON VIA .NET · PRODUCTS.ASPOSE.COM"
  barRight="PRESENTATION AUTOMATION WITHOUT MICROSOFT OFFICE"
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

- [Documentation](https://docs.aspose.com/slides/python-net/)
- [API reference](https://reference.aspose.com/slides/python-net/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/python-net/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
