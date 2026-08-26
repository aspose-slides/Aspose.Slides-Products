---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Node.js via Java PowerPoint API by Aspose.Slides"
weight: 5890
slidesIndexRebuild: true
url: /nodejs-java/
description: "Aspose.Slides for Node.js via Java is a Node.js PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Node.js."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR NODE.JS VIA JAVA · ON-PREMISES LIBRARY · JDK 8 REQUIRED · NO MICROSOFT OFFICE"
  h1="PowerPoint files, from Node.js."
  sub="Aspose.Slides for Node.js via Java creates, edits, converts and renders PowerPoint and OpenDocument presentations from server-side JavaScript. It is not a native port: one npm package wraps the Java engine and drives it through the node-java bridge, so a JVM is loaded into your Node process and a JDK 8 or later has to be installed with JAVA_HOME set. Past that it runs in your own process on Windows, Linux or macOS - no Office install, no COM automation, no display server."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/nodejs-java/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/nodejs-java/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows, Linux and macOS, wherever Node.js and a JDK both run. The package is the Java engine driven through the node-java bridge, so a JDK 8 or later must be installed and JAVA_HOME set; a JVM is loaded into your Node process rather than a native library. Installing the bridge compiles a native addon, which needs node-gyp and a C++ toolchain: Build Tools on Windows, build-essential and Python on Linux, Xcode Command Line Tools on macOS. Linux containers should also carry a font package, so text is not silently substituted. No Microsoft Office installation on the machine that runs it."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| NPM | npm install aspose.slides.via.java |
| Require | const aspose = require("aspose.slides.via.java"); |
| Prerequisite | JAVA_HOME set to a JDK 8 or later |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 1 | npm package. It pulls the node-java bridge in with it, and that bridge compiles a native addon at install time, so a node-gyp toolchain has to be present. |
| JDK 8 | or later, with JAVA_HOME set. This build runs the Java engine in a JVM inside your Node process, so a JDK is a genuine prerequisite. Microsoft Office still is not. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Node.js as shipped. Pick the job on the left."
  lang="JAVASCRIPT"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-Node.js-via-Java"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Load a presentation and write it out in another format. | PPTX -> PDF / HTML / TIFF | One save call per target. PdfOptions, HtmlOptions and TiffOptions set resolution, compression and compliance when the defaults are not what you want. | https://docs.aspose.com/slides/nodejs-java/convert-powerpoint-to-pdf/ |
| Slide thumbnails | Render any slide to a raster image at the size you ask for. | Slide -> PNG | getImage renders at slide size; pass scale factors or a java.awt.Dimension for exact pixels. Dispose every image, since each one holds a Java object. | https://docs.aspose.com/slides/nodejs-java/presentation-viewer/ |
| Charts from data | Add a real chart object backed by its own worksheet, not a picture of one. | Rows -> ClusteredColumn chart | The chart keeps an embedded workbook, so the numbers stay editable in PowerPoint after the file is written. | https://docs.aspose.com/slides/nodejs-java/create-chart/ |
| Protect | Encrypt a deck with an open password, or lock it against edits. | PPTX -> encrypted PPTX | encrypt sets the password needed to open the file; setWriteProtection leaves it readable but asks for a password before changes are saved. Reopen with LoadOptions. | https://docs.aspose.com/slides/nodejs-java/password-protected-presentation/ |
| Merge | Clone slides from one deck into another, keeping their design. | PPTX + PPTX -> PPTX | addClone copies a slide with its layout and master. Other overloads re-map it onto the destination master instead. | https://docs.aspose.com/slides/nodejs-java/merge-presentation/ |

```
const aspose = { slides: require("aspose.slides.via.java") };

const presentation = new aspose.slides.Presentation("quarterly.pptx");
try {
    const pdfOptions = new aspose.slides.PdfOptions();
    pdfOptions.setSufficientResolution(300);
    pdfOptions.setTextCompression(aspose.slides.PdfTextCompression.Flate);
    pdfOptions.setCompliance(aspose.slides.PdfCompliance.Pdf15);

    presentation.save("quarterly.pdf", aspose.slides.SaveFormat.Pdf, pdfOptions);
    presentation.save("quarterly.html", aspose.slides.SaveFormat.Html);
} finally {
    presentation.dispose();
}
```

```
const aspose = { slides: require("aspose.slides.via.java") };
const java = require("java");

const presentation = new aspose.slides.Presentation("quarterly.pptx");
try {
    const size = java.newInstanceSync("java.awt.Dimension", 960, 540);

    for (let index = 0; index < presentation.getSlides().size(); index++) {
        const slide = presentation.getSlides().get_Item(index);
        const image = slide.getImage(size);
        try {
            image.save("slide-" + (index + 1) + ".png", aspose.slides.ImageFormat.Png);
        } finally {
            image.dispose();
        }
    }
} finally {
    presentation.dispose();
}
```

```
const aspose = { slides: require("aspose.slides.via.java") };

const quarters = ["Q1", "Q2", "Q3", "Q4"];
const revenue = [412, 468, 501, 587];

const presentation = new aspose.slides.Presentation();
try {
    const slide = presentation.getSlides().get_Item(0);
    const chart = slide.getShapes().addChart(
        aspose.slides.ChartType.ClusteredColumn, 40, 40, 640, 400);

    chart.setTitle(true);
    chart.getChartTitle().addTextFrameForOverriding("Revenue by quarter");

    const chartData = chart.getChartData();
    const workbook = chartData.getChartDataWorkbook();
    const sheet = 0;

    chartData.getSeries().clear();
    chartData.getCategories().clear();
    chartData.getSeries().add(workbook.getCell(sheet, 0, 1, "Revenue"), chart.getType());

    const series = chartData.getSeries().get_Item(0);
    for (let row = 0; row < quarters.length; row++) {
        chartData.getCategories().add(workbook.getCell(sheet, row + 1, 0, quarters[row]));
        series.getDataPoints().addDataPointForBarSeries(
            workbook.getCell(sheet, row + 1, 1, revenue[row]));
    }

    presentation.save("revenue.pptx", aspose.slides.SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```

```
const aspose = { slides: require("aspose.slides.via.java") };

const presentation = new aspose.slides.Presentation("quarterly.pptx");
try {
    presentation.getProtectionManager().encrypt("open-password");
    presentation.save("quarterly-encrypted.pptx", aspose.slides.SaveFormat.Pptx);
} finally {
    presentation.dispose();
}

const loadOptions = new aspose.slides.LoadOptions();
loadOptions.setPassword("open-password");

const reopened = new aspose.slides.Presentation("quarterly-encrypted.pptx", loadOptions);
try {
    reopened.getProtectionManager().setWriteProtection("edit-password");
    reopened.save("quarterly-locked.pptx", aspose.slides.SaveFormat.Pptx);
} finally {
    reopened.dispose();
}
```

```
const aspose = { slides: require("aspose.slides.via.java") };

const destination = new aspose.slides.Presentation("intro.pptx");
const source = new aspose.slides.Presentation("appendix.pptx");
try {
    for (let index = 0; index < source.getSlides().size(); index++) {
        destination.getSlides().addClone(source.getSlides().get_Item(index));
    }
    destination.save("merged.pptx", aspose.slides.SaveFormat.Pptx);
} finally {
    source.dispose();
    destination.dispose();
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Every capability below is reachable from Node.js, because the package exposes the Java API through the node-java bridge under Java naming - getSlides, get_Item, dispose - rather than a separate JavaScript surface of its own." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model ships for .NET, Java, Python, C++ and Node.js via .NET. Class and member names carry across; what changes is the runtime you install and the naming idiom it uses."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| .NET | The managed build. One NuGet package and nothing to install beside it, so no JVM and no node-gyp step. | WINDOWS · LINUX · MACOS |
| Java | The same engine this package wraps, called straight from JVM code instead of across a bridge. | WINDOWS · LINUX · MACOS |
| Node.js via .NET | The sibling npm build, aspose.slides.via.net. Same jobs over the .NET engine, wanting a .NET 6 runtime rather than a JDK. | WINDOWS · LINUX · MACOS |
| Python via .NET | pip install aspose-slides. The .NET runtime ships inside the wheel, so nothing else is installed. | WINDOWS · LINUX · MACOS |
| C++ | A native build with no managed runtime at all, for processes that cannot host one. | WINDOWS · LINUX · MACOS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/nodejs-java/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR NODE.JS VIA JAVA · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/nodejs-java/)
- [API reference](https://docs.aspose.com/slides/nodejs-java/api-reference/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/nodejs-java/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
