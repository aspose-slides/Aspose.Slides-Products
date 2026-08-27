---
lastmod: 2026-08-28
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Python PowerPoint API for PPT, PPTX, and ODP Presentations"
weight: 5890
slidesIndexRebuild: true
url: /python-java/
description: "Aspose.Slides for Python via Java is a Python PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Python."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR PYTHON VIA JAVA · ON-PREMISES LIBRARY · NEEDS A JRE, NOT MICROSOFT OFFICE"
  h1="PowerPoint files, from Python on a JVM."
  sub="Aspose.Slides for Python via Java creates, edits, converts and renders PowerPoint and OpenDocument presentations from ordinary Python code. It is a binding over the Aspose.Slides Java engine: pip installs the wheel and the JPype1 bridge, and JPype starts a JVM inside your own process — there is no server, no socket and no native extension of ours to build. You supply a JRE 8 or newer on Windows, Linux or macOS; no Microsoft Office install and no COM automation."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/python-java/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/python-java/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Operations|#operations, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows, Linux and macOS, wherever CPython 3.7 or newer and a JRE 8 or newer are both installed. JPype1 loads the JVM into the Python process itself — no separate service, no socket, no COM. A headless server or a small container is enough; Microsoft Office and PowerPoint are not needed anywhere."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| pip | pip install aspose-slides-java |
| Prerequisite | JRE 8 or newer, JAVA_HOME set |
| Module | asposeslides |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 2 | Python packages pip installs: the Aspose.Slides wheel and the JPype1 bridge it pulls in with it. |
| 1 | Java runtime you provide yourself. JRE 8 or newer, headless is fine, and no Microsoft Office anywhere. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Python as shipped. Pick the job on the left."
  lang="PYTHON"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-Python-via-Java"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | One load, many output formats | PPTX -> PDF / HTML / TIFF | The rendering engine is inside the package. Nothing else to install. | https://docs.aspose.com/slides/java/converting-a-presentation/ |
| Slide thumbnails | Images for a viewer or an index | PPTX -> PNG | getImage returns an IImage. The scale factors set the output resolution. | https://docs.aspose.com/slides/python-java/modern-api/ |
| Charts from data | A real chart, still editable in PowerPoint | DATA -> PPTX | Chart data lives in an embedded workbook. 82 chart types. | https://docs.aspose.com/slides/java/create-chart/ |
| Protect | Encrypt the deck and the PDF you hand out | PPTX -> ENCRYPTED PPTX / PDF | The password applies to the deck and to the export. | https://docs.aspose.com/slides/java/password-protected-presentation/ |
| Merge | Clone slides between decks, layouts intact | PPTX + PPTX -> PPTX | Layouts and masters travel with the cloned slide. | https://docs.aspose.com/slides/java/merge-presentation/ |

```
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

pres = Presentation("quarterly-review.pptx")

pres.save("review.pdf", SaveFormat.Pdf)
pres.save("review.html", SaveFormat.Html)
pres.save("review.tiff", SaveFormat.Tiff)

pres.dispose()

jpype.shutdownJVM()
```

```
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, ImageFormat

pres = Presentation("deck.pptx")

for index in range(pres.getSlides().size()):
    slide = pres.getSlides().get_Item(index)
    image = slide.getImage(2.0, 2.0)
    image.save("slide-%d.png" % (index + 1), ImageFormat.Png)
    image.dispose()

pres.dispose()

jpype.shutdownJVM()
```

```
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, ChartType, SaveFormat

pres = Presentation()
slide = pres.getSlides().get_Item(0)

chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 60, 60, 620, 400)
book = chart.getChartData().getChartDataWorkbook()

chart.getChartData().getSeries().clear()
chart.getChartData().getCategories().clear()

chart.getChartData().getCategories().add(book.getCell(0, 1, 0, "Q1"))
chart.getChartData().getCategories().add(book.getCell(0, 2, 0, "Q2"))
chart.getChartData().getSeries().add(book.getCell(0, 0, 1, "Revenue"), chart.getType())

series = chart.getChartData().getSeries().get_Item(0)
series.getDataPoints().addDataPointForBarSeries(book.getCell(0, 1, 1, 120))
series.getDataPoints().addDataPointForBarSeries(book.getCell(0, 2, 1, 165))

pres.save("report.pptx", SaveFormat.Pptx)
pres.dispose()

jpype.shutdownJVM()
```

```
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, PdfOptions, SaveFormat

pres = Presentation("board-deck.pptx")

pres.getProtectionManager().encrypt("s3cret")
pres.save("board-deck-encrypted.pptx", SaveFormat.Pptx)

pdf_options = PdfOptions()
pdf_options.setPassword("s3cret")
pres.save("board-deck.pdf", SaveFormat.Pdf, pdf_options)

pres.dispose()

jpype.shutdownJVM()
```

```
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

target = Presentation("master.pptx")
source = Presentation("appendix.pptx")

for index in range(source.getSlides().size()):
    target.getSlides().addClone(source.getSlides().get_Item(index))

target.save("combined.pptx", SaveFormat.Pptx)

source.dispose()
target.dispose()

jpype.shutdownJVM()
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-solution-platforms
  id="operations"
  title="Browse by operation"
  lede="Each operation has its own page, listing the formats it covers with a code sample for each."
>}}

| Operation | Href | Note | Language | Icon |
|---|---|---|---|---|
| Conversion | /slides/python-java/conversion/ | Convert between presentation, document and image formats. | Python | conversion |

{{< /blocks/products/pf/slides-solution-platforms >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything here is supported in the Python via Java build, which drives the same Java engine through the JPype1 bridge. Where a grey note follows, the capability is delivered through a separate product or comes with a stated limit." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="Same object model on other platforms: .NET, Java, C++, Node.js, Android, PHP, SharePoint and JasperReports."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| CPython 3.7 to 3.14 | The interpreter range the wheel declares on PyPI. | WINDOWS · LINUX · MACOS |
| JRE 8 or newer | The engine is Java, so a Java runtime hosts it. Any JRE from 8 up, current LTS releases included. | WINDOWS · LINUX · MACOS |
| JPype1 bridge | Installed with the package. It starts the JVM inside your Python process, so there is no server and no socket. | IN-PROCESS |
| Containers | A base image with Python and a headless JRE is the whole dependency list. | DOCKER · LINUX |
| Server frameworks and workers | Django, Flask, FastAPI and queue workers, with one JVM per process. | LINUX · WINDOWS · MACOS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/python-java/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR PYTHON VIA JAVA · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/python-java/)
- [API reference](https://docs.aspose.com/slides/python-java/api-reference/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/python-java/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
