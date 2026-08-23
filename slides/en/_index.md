---
lastmod: 2026-08-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Create, Edit, and Convert PowerPoint Presentations with Aspose.Slides"
weight: 7160
slidesIndexRebuild: true
url: /
keywords:
- PowerPoint
- presentation
- slide
- create a presentation
- edit a presentation
- convert a presentation
- create a slide
- edit a slide
- convert a slide
- presentation format
- C#
- Java
- C++
- Python
description: "Aspose.Slides APIs create, edit, render, and convert PowerPoint and OpenDocument presentations in .NET, Java, C++, Python, and other environments."
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ON-PREMISES LIBRARY · NO MICROSOFT OFFICE REQUIRED"
  h1="Read, write and render PowerPoint files from your own code."
  sub="Aspose.Slides creates, edits, converts and renders PowerPoint and OpenDocument presentations in .NET, Java, Python, C++, Node.js, Android and more. It runs in your process, on Windows, Linux or macOS, in a container or on a host, with no Office install."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/"
  note="Full API on trial · watermark on open and save"
  moreText="C++, Android, PHP, SharePoint, JasperReports and more" moreUrl="#platforms"
  runsOnTitle="RUNS ON"
  runsOn="Windows, Linux and macOS, on a host or in a container, wherever the .NET, Java or Python runtime the build targets is supported. No Microsoft Office installation on the machine that runs it."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Platform | Install |
|---|---|
| .NET | dotnet add package Aspose.Slides.NET |
| Python | pip install aspose-slides |
| Node.js | npm install aspose.slides.via.java |
| Java | com.aspose:aspose-slides |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit after the file is written. |
| 13 → 12 | Presentation formats read and written, including the pre-2007 binary `.ppt` container and OpenDocument `.odp`, plus 9 further export targets. |
| 128 | Consecutive months with a release, on a published version stream. |
| 0 | Microsoft Office installs, GDI dependencies and X displays needed. A small Linux container is enough. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-platform-table
  title="Pick your platform"
  lede="Same object model everywhere. The differences that matter are the runtime and what each build adds on top."
  allHref="/slides/family/" allText="All high-code APIs"
>}}

{{< blocks/products/pf/slides-fact-band
  id="example"
  title="Build a presentation from content you already have"
  lede="Most of the presentation work people automate runs *into* a deck rather than out of one: pulling HTML, images, PDF pages or database rows onto slides. Aspose.Slides reads HTML markup straight into a text frame, keeping the headings, bold runs and lists it finds."
  isGrey="true"
  split="true" codeLabelLeft="HTML → PPTX" codeLabelRight="PYTHON"
>}}

```
import aspose.slides as slides

html = "<h1>Quarterly review</h1><p>Revenue up <b>18%</b> on the quarter.</p>"

with slides.Presentation() as presentation:
    frame = presentation.slides[0].shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 40, 40, 640, 300).text_frame
    frame.paragraphs.clear()
    frame.paragraphs.add_from_html(html)
    presentation.save("quarterly.pptx", slides.export.SaveFormat.PPTX)
```

That is the whole program: no PowerPoint, no headless Office, no template file to keep in step. The same call takes markup a reporting job or a content system already produces, so an existing HTML report becomes a deck on a schedule instead of by hand.

{{< /blocks/products/pf/slides-fact-band >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything here is supported. Where a grey note follows, the capability is delivered through a separate product or comes with a stated limit." >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES · PRODUCTS.ASPOSE.COM"
  barRight="PRESENTATION AUTOMATION WITHOUT MICROSOFT OFFICE"
>}}

## If you don't want a library

Aspose.Slides Cloud is a hosted REST API for loading, creating, editing and converting presentations.

- [![](https://www.aspose.cloud/templates/asposecloud/App_Themes/V3/images/sdk/272x272/aspose_slides-for-curl.png)cURL](https://products.aspose.cloud/slides/curl/)
- [![](https://www.aspose.cloud/templates/asposecloud/App_Themes/V3/images/sdk/272x272/aspose_slides-for-net.png).NET SDK](https://products.aspose.cloud/slides/net/)
- [![](https://www.aspose.cloud/templates/asposecloud/App_Themes/V3/images/sdk/272x272/aspose_slides-for-java.png)Java SDK](https://products.aspose.cloud/slides/java/)
- [All low-code APIs →](https://products.aspose.cloud/slides/family/)

## No-code apps

- [![](https://www.aspose.cloud/templates/asposeapp/images/products/logo/aspose_viewer-app.png)Viewer](https://products.aspose.app/slides/viewer)
- [![](https://www.aspose.cloud/templates/asposeapp/images/products/logo/aspose_conversion-app.png)Conversion](https://products.aspose.app/slides/conversion)
- [![](https://www.aspose.cloud/templates/asposeapp/images/products/logo/aspose_annotation-app.png)Annotation](https://products.aspose.app/slides/annotation)
- [All apps →](https://products.aspose.app/slides/family)

## Resources

- [Documentation](https://docs.aspose.com/slides/)
- [API reference](https://reference.aspose.com/slides/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Case studies](https://about.aspose.com/customers/success-stories/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
