---
lastmod: 2026-08-28
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Create, Edit, and Convert PowerPoint Presentations with Aspose.Slides for C++"
weight: 6580
slidesIndexRebuild: true
url: /cpp/
description: "Aspose.Slides for C++ is a powerful library for creating, editing, and converting PowerPoint presentations in C++."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR C++ · NATIVE ON-PREMISES LIBRARY · NO MICROSOFT OFFICE REQUIRED"
  h1="PowerPoint files, from C++."
  sub="Aspose.Slides for C++ creates, edits, converts and renders PowerPoint and OpenDocument presentations from native C++. It compiles and links straight into your own binary - no .NET runtime, no JVM, no bridge process, no Office install, no COM automation, no display server. Prebuilt libraries ship for Windows on MSVC 2017 or later, Linux on GCC 6.1 or Clang 3.9, and macOS on Xcode 13.4."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/cpp/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/cpp/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Operations|#operations, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows with Visual Studio 2017 or later. Linux with GCC 6.1 or Clang 3.9 on glibc 2.23 or later, which covers Ubuntu 16.04, CentOS 8, Fedora 24 and anything newer. macOS Monterey 12.1 or later with Xcode 13.4. CMake 3.18 or later anywhere outside Visual Studio. Prebuilt x86_64 binaries on all three platforms, arm64 as well on macOS, and a separate package for 32-bit Windows. No .NET runtime and no JVM anywhere in the chain. On a minimal Linux or macOS image install a common font package, or rendered text falls back to whatever happens to be present and the metrics shift."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| Console | Install-Package Aspose.Slides.Cpp |
| 32-bit | Install-Package Aspose.Slides.Cpp.x86 |
| Header | DOM/Presentation.h |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 1 | NuGet package for Visual Studio, headers and prebuilt libraries in the box. On Linux and macOS the same build ships as one archive you point CMake at. |
| 0 | Microsoft Office installs, .NET runtimes and JVMs needed. It is native code linked into your own process, so a small Linux container plus a font package is enough. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, C++ as shipped. Pick the job on the left."
  lang="C++"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-C"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Load a deck once and write it out in as many formats as you need. | PPTX -> PDF / HTML / TIFF | One Save call per target. PdfOptions, HtmlOptions and TiffOptions control resolution, compression and PDF/A compliance when the defaults are not enough. | https://docs.aspose.com/slides/cpp/convert-powerpoint-to-pdf/ |
| Slide thumbnails | Render every slide to a raster image at whatever size you ask for. | PPTX -> PNG per slide | GetImage takes a scale pair, an explicit Size, or rendering options that place speaker notes and comments inside the frame. | https://docs.aspose.com/slides/cpp/convert-slide/ |
| Charts from data | Build a native chart backed by a real, editable worksheet. | values -> ChartData -> PPTX | AddChart writes a genuine OOXML chart with its own cached workbook, so whoever opens the deck can click the chart and edit the numbers behind it. | https://docs.aspose.com/slides/cpp/create-chart/ |
| Protect | Encrypt a deck, mark it read-only, or both at once. | PPTX -> encrypted PPTX | Encrypt sets the password required to open the file. SetWriteProtection leaves it readable and only guards saving. RemoveEncryption and CheckWriteProtection undo and test the same state. | https://docs.aspose.com/slides/cpp/password-protected-presentation/ |
| Merge | Clone slides out of many decks into one, keeping their formatting. | PPTX + PPTX -> PPTX | AddClone copies a slide with its layout and master. Two further overloads take a destination master or layout instead, when everything should land in one house style. | https://docs.aspose.com/slides/cpp/merge-presentation/ |

```
#include <DOM/Presentation.h>
#include <Export/PdfOptions.h>
#include <Export/SaveFormat.h>
#include <system/smart_ptr.h>

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System;

int main()
{
    auto presentation = MakeObject<Presentation>(u"quarterly-review.pptx");

    // Straight to PDF on the defaults.
    presentation->Save(u"quarterly-review.pdf", SaveFormat::Pdf);

    // Or tune the render first.
    auto options = MakeObject<PdfOptions>();
    options->set_JpegQuality(90);
    options->set_SufficientResolution(300);
    presentation->Save(u"print-ready.pdf", SaveFormat::Pdf, options);

    // Same loaded object, other targets.
    presentation->Save(u"quarterly-review.html", SaveFormat::Html);
    presentation->Save(u"quarterly-review.tiff", SaveFormat::Tiff);

    presentation->Dispose();
    return 0;
}
```

```
#include <DOM/ISlide.h>
#include <DOM/ISlideCollection.h>
#include <DOM/Presentation.h>
#include <IImage.h>
#include <ImageFormat.h>
#include <system/smart_ptr.h>
#include <system/string.h>

using namespace Aspose::Slides;
using namespace System;

int main()
{
    auto presentation = MakeObject<Presentation>(u"quarterly-review.pptx");

    // Scale is relative to the slide's nominal size, so 2.0f doubles both axes.
    const float scale = 2.0f;

    for (int32_t i = 0; i < presentation->get_Slides()->get_Count(); i++)
    {
        auto image = presentation->get_Slide(i)->GetImage(scale, scale);
        image->Save(String::Format(u"slide_{0}.png", i + 1), ImageFormat::Png);
        image->Dispose();
    }

    presentation->Dispose();
    return 0;
}
```

```
#include <DOM/Chart/ChartType.h>
#include <DOM/Chart/IChartCategoryCollection.h>
#include <DOM/Chart/IChartData.h>
#include <DOM/Chart/IChartDataPointCollection.h>
#include <DOM/Chart/IChartDataWorkbook.h>
#include <DOM/Chart/IChartSeries.h>
#include <DOM/Chart/IChartSeriesCollection.h>
#include <DOM/IChart.h>
#include <DOM/IShapeCollection.h>
#include <DOM/ISlide.h>
#include <DOM/ISlideCollection.h>
#include <DOM/Presentation.h>
#include <Export/SaveFormat.h>
#include <system/object_ext.h>
#include <system/smart_ptr.h>
#include <system/string.h>
#include <vector>

using namespace Aspose::Slides;
using namespace Aspose::Slides::Charts;
using namespace Aspose::Slides::Export;
using namespace System;

int main()
{
    const std::vector<String> quarters = { u"Q1", u"Q2", u"Q3", u"Q4" };
    const std::vector<double> revenue  = { 12.4, 15.1, 13.8, 19.6 };

    auto presentation = MakeObject<Presentation>();
    auto slide = presentation->get_Slide(0);

    auto chart = slide->get_Shapes()->AddChart(
        ChartType::ClusteredColumn, 50.0f, 50.0f, 600.0f, 400.0f);

    auto data = chart->get_ChartData();
    auto book = data->get_ChartDataWorkbook();

    // Drop the placeholder data a new chart is seeded with.
    data->get_Series()->Clear();
    data->get_Categories()->Clear();

    const int32_t sheet = 0;

    for (int32_t row = 0; row < static_cast<int32_t>(quarters.size()); row++)
    {
        data->get_Categories()->Add(
            book->GetCell(sheet, row + 1, 0, ObjectExt::Box<String>(quarters[row])));
    }

    data->get_Series()->Add(
        book->GetCell(sheet, 0, 1, ObjectExt::Box<String>(u"Revenue")),
        chart->get_Type());

    auto series = data->get_Series()->idx_get(0);

    for (int32_t row = 0; row < static_cast<int32_t>(revenue.size()); row++)
    {
        series->get_DataPoints()->AddDataPointForBarSeries(
            book->GetCell(sheet, row + 1, 1, ObjectExt::Box<double>(revenue[row])));
    }

    presentation->Save(u"revenue.pptx", SaveFormat::Pptx);
    presentation->Dispose();
    return 0;
}
```

```
#include <DOM/IProtectionManager.h>
#include <DOM/Presentation.h>
#include <Export/SaveFormat.h>
#include <system/smart_ptr.h>

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System;

int main()
{
    auto presentation = MakeObject<Presentation>(u"quarterly-review.pptx");
    auto protection = presentation->get_ProtectionManager();

    // Opens for anyone, but PowerPoint asks for this before it will save edits.
    protection->SetWriteProtection(u"edit-password");

    // Encrypts the file itself. Without this one, nothing opens it at all.
    protection->Encrypt(u"open-password");

    presentation->Save(u"quarterly-review-locked.pptx", SaveFormat::Pptx);
    presentation->Dispose();
    return 0;
}
```

```
#include <DOM/ISlide.h>
#include <DOM/ISlideCollection.h>
#include <DOM/Presentation.h>
#include <Export/SaveFormat.h>
#include <system/smart_ptr.h>

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System;

int main()
{
    auto destination = MakeObject<Presentation>(u"deck-a.pptx");
    auto source = MakeObject<Presentation>(u"deck-b.pptx");

    // Each clone arrives with its own layout and master intact.
    for (const auto& slide : source->get_Slides())
    {
        destination->get_Slides()->AddClone(slide);
    }

    destination->Save(u"merged.pptx", SaveFormat::Pptx);

    source->Dispose();
    destination->Dispose();
    return 0;
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-solution-platforms
  id="operations"
  title="Browse by operation"
  lede="Each operation has its own page, listing the formats it covers with a code sample for each."
>}}

| Operation | Href | Note | Language | Icon |
|---|---|---|---|---|
| Conversion | /slides/cpp/conversion/ | Convert between presentation, document and image formats. | C++ | conversion |
| Merger | /slides/cpp/merger/ | Combine several presentations, documents or images into one file. | C++ | merger |
| Editor | /slides/cpp/editor/ | Open a file, change it and write it back, format by format. | C++ | editor |
| Viewer | /slides/cpp/viewer/ | Open a presentation and render it for viewing. | C++ | viewer |
| Parser | /slides/cpp/parser/ | Extract text, images, audio and video from a presentation. | C++ | parser |
| Metadata | /slides/cpp/metadata/ | Read and write presentation document properties. | C++ | metadata |
| Watermark | /slides/cpp/watermark/ | Add a text or image watermark. | C++ | watermark |
| Protect | /slides/cpp/protect/ | Password-protect a presentation. | C++ | protect |
| Unlock | /slides/cpp/unlock/ | Remove password protection. | C++ | unlock |
| Redaction | /slides/cpp/redaction/ | Find and replace sensitive text. | C++ | redaction |
| Search | /slides/cpp/search/ | Find text across the slides of a presentation. | C++ | search |
| Annotation | /slides/cpp/annotation/ | Remove comments and annotations. | C++ | annotation |
| Chart | /slides/cpp/chart/ | Create and edit charts on slides. | C++ | chart |

{{< /blocks/products/pf/slides-solution-platforms >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="The whole object model is exposed as C++ classes - slides, layouts and masters, shapes and groups, text down to the portion, tables, charts, SmartArt, animation timelines, comments and the renderer behind every export - with nothing held back on this runtime." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model ships for .NET, Java, Python, Node.js, PHP and Android. Class names, enumerations and save-format constants carry across unchanged, so a routine written against this page reads almost line for line on the next runtime."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| Aspose.Slides for .NET | One NuGet package for .NET Framework 4.x and .NET 6 or later, with no native prerequisite alongside it. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Java | A single JAR from Maven Central, published against a JDK classifier. Pure Java, nothing native to place. | JVM 8+ |
| Aspose.Slides for Python via .NET | A wheel that carries the engine with it, so pip install is the whole setup. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Node.js via Java | An npm package driving the Java build across a bridge. A JDK 8 or later must be installed and JAVA_HOME set. | NODE · JDK REQUIRED |
| Aspose.Slides for PHP via Java | PHP scripts calling the Java build through the same bridge, so a JDK is a hard prerequisite here too. | PHP · JDK REQUIRED |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/cpp/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR C++ · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/cpp/)
- [API reference](https://reference.aspose.com/slides/cpp/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/cpp/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
