---
lastmod: 2026-08-28
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Node.js via .NET PowerPoint API by Aspose.Slides"
weight: 5890
slidesIndexRebuild: true
url: /nodejs-net/
description: "Aspose.Slides for Node.js via .NET is a Node.js PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Node.js."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR NODE.JS VIA .NET · ON-PREMISES LIBRARY · NEEDS A .NET 6 RUNTIME"
  h1="PowerPoint files, from Node.js."
  sub="Aspose.Slides for Node.js via .NET creates, edits, converts and renders PowerPoint and OpenDocument presentations from JavaScript. It is not a native Node addon: the npm package wraps the Aspose.Slides .NET engine and calls into it over the edge-js bridge, so a .NET 6 or later runtime has to be present on the machine. Everything else is bundled, including edge-js and the native rendering libraries for Windows, Linux and macOS, and no Microsoft Office install or display server is involved."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/nodejs-net/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/nodejs-net/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Operations|#operations, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows, Linux and macOS, on Node.js with a .NET 6 or later runtime installed. The package carries its own native rendering libraries, x86 and x64 on Windows, x64 on Linux, and both Intel and Apple Silicon on macOS, and pulls in the edge-js bridge as an npm dependency. No Microsoft Office, no COM automation, no display server."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| npm | npm install aspose.slides.via.net |
| Check prerequisite | dotnet --list-runtimes |
| Require | const { Presentation } = require('aspose.slides.via.net'); |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 2 | Things to install: the npm package and a .NET 6 or later runtime. The edge-js bridge and the native rendering libraries ship inside the package. |
| 0 | Microsoft Office installs, COM automation and display servers needed. A headless container is enough once the .NET runtime is in it. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Node.js as shipped. Pick the job on the left."
  lang="JAVASCRIPT"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-Node.js-via-.NET"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Open a deck and write it out in another format. | PPTX -> PDF / HTML / TIFF | One save call per target. The SaveFormat constant chooses the writer, not the file extension. | https://reference.aspose.com/slides/net/aspose.slides/presentation/save/ |
| Slide thumbnails | Render every slide to a raster image at a fixed pixel size. | Slide -> PNG 960 x 540 | getImageWithImageSize takes a plain object with width and height. Dispose each image, it holds a handle on the .NET side. | https://reference.aspose.com/slides/net/aspose.slides/islide/getimage/ |
| Tables from data | Push a JavaScript array onto a slide as a native, editable table. | Array -> native table | Cell text is set through textFrame.text. This is the route from structured data to a slide in this binding, which does not surface the chart object model. | https://reference.aspose.com/slides/net/aspose.slides/ishapecollection/addtable/ |
| Protect | Encrypt a deck and mark it read-only before it leaves your process. | PPTX -> encrypted PPTX | encrypt sets the password needed to open the file, setWriteProtection the one needed to edit it. Both take effect on save. | https://reference.aspose.com/slides/net/aspose.slides/iprotectionmanager/encrypt/ |
| Merge | Append the slides of one deck to another and keep their layouts. | N decks -> 1 deck | addClone brings the slide across with its layout and master, so appended slides keep the look they had. | https://reference.aspose.com/slides/net/aspose.slides/islidecollection/addclone/ |

```
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;

const pres = new Presentation("quarterly-review.pptx");

pres.save("quarterly-review.pdf", SaveFormat.Pdf);
pres.save("quarterly-review.html", SaveFormat.Html);
pres.save("quarterly-review.tiff", SaveFormat.Tiff);

pres.dispose();
```

```
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, ImageFormat } = asposeSlides;
const fs = require('fs');

if (!fs.existsSync("thumbs")) fs.mkdirSync("thumbs");

const pres = new Presentation("quarterly-review.pptx");

for (let i = 0; i < pres.slides.count; i++) {
    const image = pres.slides.get(i).getImageWithImageSize({ width: 960, height: 540 });
    image.save("thumbs/slide-" + (i + 1) + ".png", ImageFormat.Png);
    image.dispose();
}

pres.dispose();
```

```
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;

const rows = [
    ["Region", "Q1", "Q2"],
    ["EMEA", "412", "455"],
    ["APAC", "388", "501"]
];

const pres = new Presentation();
const slide = pres.slides.get(0);
const table = slide.shapes.addTable(50, 50, [200, 120, 120], [40, 40, 40]);

for (let r = 0; r < rows.length; r++) {
    for (let c = 0; c < rows[r].length; c++) {
        table.getCell(c, r).textFrame.text = rows[r][c];
    }
}

pres.save("regional-summary.pptx", SaveFormat.Pptx);
pres.dispose();
```

```
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;

const pres = new Presentation("quarterly-review.pptx");

pres.protectionManager.encrypt("open-sesame");
pres.protectionManager.setWriteProtection("editors-only");

pres.save("quarterly-review-protected.pptx", SaveFormat.Pptx);
pres.dispose();
```

```
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;

const target = new Presentation("quarterly-review.pptx");
const source = new Presentation("appendix.pptx");

for (let i = 0; i < source.slides.count; i++) {
    target.slides.addClone(source.slides.get(i));
}

target.save("combined.pptx", SaveFormat.Pptx);

source.dispose();
target.dispose();
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-solution-platforms
  id="operations"
  title="Browse by operation"
  lede="Each operation has its own page, listing the formats it covers with a code sample for each."
>}}

| Operation | Href | Note | Language | Icon |
|---|---|---|---|---|
| Conversion | /slides/nodejs-net/conversion/ | Convert between presentation, document and image formats. | JavaScript | conversion |

{{< /blocks/products/pf/slides-solution-platforms >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="The Aspose.Slides object model is reachable from JavaScript, from slides, shapes, tables and text through to rendering and export, with charts the one area this binding does not surface." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model ships for .NET, Java, C++, Python and PHP, so a deck built here is built the same way on any of them."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| Aspose.Slides for .NET | The engine this package wraps, called directly from C#, VB.NET or F#. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Node.js via Java | Same language, a JVM instead of .NET. The alternative when a .NET runtime is not an option. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Java | Pure Java library. Needs a JVM and no .NET at all. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for Python via .NET | The same .NET engine behind a Python API. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for C++ | Native library with no managed runtime to install alongside it. | WINDOWS · LINUX · MACOS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/nodejs-net/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR NODE.JS VIA .NET · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/nodejs-net/)
- [API reference](https://docs.aspose.com/slides/nodejs-net/api-reference/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/nodejs-net/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
