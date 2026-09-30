---
lastmod: 2026-09-30
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
  note="Full API on trial · watermark on output"
  moreText="C++, Android, PHP, SharePoint, JasperReports and more" moreUrl="#platforms"
  jump="Platforms|#platforms, What it does|#solutions, Example|#example, Formats|#formats, Conversions|#tasks, Capabilities|#capabilities, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows, Linux and macOS, on a host or in a container, wherever the .NET, Java or Python runtime the build targets is supported. No Microsoft Office installation on the machine that runs it."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Platform | Install |
|---|---|
| .NET | dotnet add package Aspose.Slides.NET |
| Python | pip install aspose-slides |
| Node.js | npm install aspose.slides.via.java |
| Java | mvn dependency:get -DremoteRepositories=https://releases.aspose.com/java/repo/ -Dartifact=com.aspose:aspose-slides:26.9:jar:jdk16 |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 187 / 80 | Shape types and chart types the API creates, each a real object that PowerPoint still recognises and lets a person edit after the file is written. |
| 12 → 12 | Presentation formats read and written, including the pre-2007 binary `.ppt` container and OpenDocument `.odp`, plus 9 further export targets. |
| Monthly | A new version of Aspose.Slides for .NET every month since December 2020. The [NuGet version list](https://www.nuget.org/packages/Aspose.Slides.NET#versions-body-tab) dates each one. |
| 0 | Microsoft Office installs, GDI dependencies and X displays needed. A small Linux container is enough. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-platform-table
  title="Pick your platform"
  lede="Same object model everywhere. The differences that matter are the runtime and what each build adds on top. The last five rows are not libraries you write code against — two are the .NET package under another name, three are integrations for an existing server product."
  allHref="/slides/family/" allText="All products, side by side"
>}}

{{< blocks/products/pf/slides-solution-platforms
  id="solutions"
  title="What people use it for"
  lede="Fifteen jobs, one page each. Twelve of them link to per-platform pages, each leading to code samples. Splitting, comparison and signatures offer a free online app instead."
>}}

| Platform | Href | Note | Language |
|---|---|---|---|
| Conversion | /slides/conversion/ | Convert between PPT, PPTX, PDF, HTML, POTX, POTM and ODP. |  |
| Merger | /slides/merger/ | Merge PowerPoint and OpenDocument presentations into one file. |  |
| Splitter | /slides/splitter/ | Split PPT, PPTX and ODP presentations into separate files. |  |
| Parser | /slides/parser/ | Extract text, images, audio and video from a presentation. |  |
| Viewer | /slides/viewer/ | Open presentations and export them for viewing. |  |
| Watermark | /slides/watermark/ | Add text and image watermarks to PPT, PPTX and ODP. |  |
| Protect | /slides/protect/ | Password-protect PPT, PPTX and ODP presentations. |  |
| Unlock | /slides/unlock/ | Remove password protection from PPT, PPTX and ODP. |  |
| Redaction | /slides/redaction/ | Find and redact text in PPT, PPTX and ODP presentations. |  |
| Comparison | /slides/comparison/ | Compare presentations in PPT, PPS, PPTX, POTX, PPSX, PPTM and ODP. |  |
| Chart | /slides/chart/ | Create and edit charts in PPT and PPTX presentations. |  |
| Metadata | /slides/metadata/ | View and edit presentation document properties. |  |
| Search | /slides/search/ | Find text in PPT, PPTX and ODP presentations. |  |
| Signature | /slides/signature/ | Add drawing, text or image signatures, and sign PPTX digitally. |  |
| Annotation | /slides/annotation/ | Remove comments and annotations from PowerPoint files. |  |

{{< /blocks/products/pf/slides-solution-platforms >}}

{{< blocks/products/pf/slides-fact-band
  id="example"
  title="Build a presentation from content you already have"
  lede="Most of the presentation work people automate runs *into* a deck rather than out of one: pulling HTML, images, PDF pages or database rows onto slides. Aspose.Slides reads HTML markup straight into a text frame, keeping the headings, bold runs and lists it finds."
  isGrey="true"
  split="true" codeLabelLeft="HTML → PPTX" codeLabelRight="PYTHON"
  image="sl/sl-example-slide-26-9-0.png" imageWidth="1120" imageHeight="840"
  imageAlt="Slide 1 of quarterly.pptx: a dark blue slide holding the heading Quarterly review and the line Revenue up 18 per cent on the quarter, with the figure in bold."
  imageCaption="The slide this program writes, rendered by Aspose.Slides for Python via .NET 26.9.0 under a licence. The free trial writes the same file with an evaluation watermark on every slide."
  docsText="Guide: import HTML text into paragraphs" docsUrl="https://docs.aspose.com/slides/python-net/manage-paragraph/#import-html-text-into-paragraphs"
  leafText="Convert HTML to PPTX in Python" leafUrl="/slides/python-net/conversion/html-to-pptx/"
>}}

```
import aspose.slides as slides

html = "<h1>Quarterly review</h1><p>Revenue up <b>18%</b> on the quarter.</p>"

with slides.Presentation() as presentation:
    shape = presentation.slides[0].shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 0, 0, 720, 540)
    shape.fill_format.fill_type = slides.FillType.SOLID
    shape.fill_format.solid_fill_color.scheme_color = slides.SchemeColor.TEXT2
    shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL
    frame = shape.text_frame
    frame.paragraphs.clear()
    frame.paragraphs.add_from_html(html)
    for paragraph in frame.paragraphs:
        paragraph.paragraph_format.alignment = slides.TextAlignment.CENTER
    presentation.save("quarterly.pptx", slides.export.SaveFormat.PPTX)
```

That is the whole program: no PowerPoint, no headless Office, no template file to keep in step. The same call takes markup a reporting job or a content system already produces, so an existing HTML report becomes a deck on a schedule instead of by hand.

{{< /blocks/products/pf/slides-fact-band >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-solution-platforms
  id="tasks"
  title="The conversions people come here for"
  lede="Every row below has its own page with a runnable sample: eleven conversions and one merge, the ones readers of this site open most, with a row per language where more than one is popular. Eight platforms list every conversion they support on their own conversion page."
  allHref="/slides/conversion/" allText="Every conversion, by platform"
>}}

| Conversion | Page | What it does | Language |
|---|---|---|---|
| HTML to PPTX | /slides/python-net/conversion/html-to-pptx/ | Turn an HTML report into an editable deck. | Python |
| HTML to PPTX | /slides/net/conversion/html-to-pptx/ | The same conversion from a .NET service. | C# |
| HTML to PPTX | /slides/java/conversion/html-to-pptx/ | The same conversion on the JVM. | Java |
| HTML to PPT | /slides/python-net/conversion/html-to-ppt/ | The same, written to the pre-2007 binary container. | Python |
| HTML to PPT | /slides/net/conversion/html-to-ppt/ | Markup in, binary PPT out, from C#. | C# |
| HTML to PPT | /slides/java/conversion/html-to-ppt/ | Markup in, binary PPT out, on the JVM. | Java |
| PNG to PPTX | /slides/net/conversion/png-to-pptx/ | Put one PNG image on a slide, stretched to fill it. | C# |
| Image to PPT | /slides/net/conversion/image-to-ppt/ | The same for one image, saved as binary PPT. | C# |
| PPTX to PPT | /slides/python-net/conversion/pptx-to-ppt/ | Down-convert for readers on older PowerPoint. | Python |
| PPTX to PPT | /slides/java/conversion/pptx-to-ppt/ | The same down-conversion on the JVM. | Java |
| PPTX to PPT | /slides/nodejs-java/conversion/pptx-to-ppt/ | The same down-conversion from Node.js. | JavaScript |
| PPT to PPTX | /slides/python-net/conversion/ppt-to-pptx/ | Bring a legacy deck onto the current format. | Python |
| PPT to PPTX | /slides/nodejs-java/conversion/ppt-to-pptx/ | Modernise a legacy deck from Node.js. | JavaScript |
| POT to PPT | /slides/nodejs-java/conversion/pot-to-ppt/ | Turn a PowerPoint template into a presentation. | JavaScript |
| PPTX to PDF | /slides/python-net/conversion/pptx-to-pdf/ | Render a deck to fixed-layout PDF. | Python |
| PPTX to HTML | /slides/python-net/conversion/pptx-to-html/ | Publish a deck as a web page. | Python |
| PPTX to HTML | /slides/nodejs-java/conversion/pptx-to-html/ | Publish a deck as a web page from Node.js. | JavaScript |
| Merge PPT | /slides/python-net/merge/ppt/ | Combine two PPT files into one. | Python |
| PDF to HTML | /slides/php-java/conversion/pdf-to-html/ | Publish a PDF as a web page. | PHP |
| Image to JPG | /slides/php-java/conversion/image-to-jpg/ | Convert an image to JPG at its original size. | PHP |

{{< /blocks/products/pf/slides-solution-platforms >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything here is supported. Where a grey note follows, the capability is delivered through a separate product or comes with a stated limit. Aspose.Slides also builds what a deck is made of, with a Python via .NET guide for each: [slide masters](https://docs.aspose.com/slides/python-net/slide-master/) and [layouts](https://docs.aspose.com/slides/python-net/slide-layout/) · [tables](https://docs.aspose.com/slides/python-net/manage-table/) · [speaker notes](https://docs.aspose.com/slides/python-net/presentation-notes/) · [SmartArt](https://docs.aspose.com/slides/python-net/manage-smartart/) · [animation.](https://docs.aspose.com/slides/python-net/powerpoint-animation/)" >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API, so you can test the formats you actually care about before you talk to anyone. In evaluation mode the library reads only the first five characters of any text, followed by a notice; its text extractor returns none of the presentation's text; and saving adds an evaluation watermark to every slide. A temporary licence lifts all three for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
  ctaTertiaryText="Pricing" ctaTertiaryUrl="https://purchase.aspose.com/pricing/slides/family/"
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
- [Why Aspose.Slides](/slides/benefits/)
- [Compared with python-pptx](/slides/python-net/python-pptx-comparison/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Case studies](https://about.aspose.com/customers/success-stories/)

## In use

> There would be no hesitation in recommending Aspose.Slides (or any of the other APIs) for both small and larger technical requirements. It will save you a world of time, money and energy over building it for yourself.

— Matt Rowbotham · Traxart · January 2020

[Traxart case study](https://library.conholdate.app/files/oLPS8MVj36/case-study-traxart.docx)

> It was worth the money with regards to purchase: it would have been nowhere near as fast without these products.

— Jens Gehrke, Principal Senior Consultant · Oracle Consultancy · 2011

[Oracle case study](https://library.conholdate.app/files/er7czWM37G/case-study-of-oracles-use-of-aspose-cells-and-aspose-slides-in-an-on-demand-reporting-system.pdf)

> The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— Bruce Brien, CEO · Stratascope Inc. · January 2011

[Stratascope case study](https://library.conholdate.app/files/mLRiZ6yXam/stratascope-uses-aspose-slides-for-net-to-output-custom-configured-account-plans-to-powerpoint.pdf)

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
