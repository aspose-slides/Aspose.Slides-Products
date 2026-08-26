---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "PowerPoint Rendering Extension for Reporting Services"
weight: 3020
slidesIndexRebuild: true
url: /reporting-services/
description: "PowerPoint rendering extension for SQL Server Reporting Services and Power BI Report Server to export RDL reports to PPT, PPTX, PPS, PPSX, and XPS."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR REPORTING SERVICES · SERVER RENDERING EXTENSIONS · NO MICROSOFT OFFICE REQUIRED"
  h1="PowerPoint, from the report server."
  sub="Aspose.Slides for Reporting Services is a set of rendering extensions you install into Microsoft SQL Server Reporting Services or Power BI Report Server. Once they are registered, PowerPoint output — PPT, PPS, PPTX and PPSX — appears in the Select Format list of every paginated RDL report on the server. Existing reports export unchanged, one managed assembly is deployed, and no Microsoft Office goes on the machine."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/reportingservices/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/reportingservices/"
  note="Evaluation has no time limit · watermarks on exported reports"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Microsoft SQL Server Reporting Services 2005, 2008, 2008 R2, 2012, 2014, 2016, 2017 and 2019, 32-bit and 64-bit, and Power BI Report Server for paginated RDL reports. Requires .NET Framework 3.5 on the host machine. The MSI installs and configures the default Reporting Services instance; a named instance, or more than one instance on the same machine, takes the manual route instead. No Microsoft Office, no PowerPoint automation."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| MSI (default instance) | Run the Aspose.Slides for Reporting Services 26.8 MSI installer; it configures the default Reporting Services instance |
| Manual | Copy Aspose.Slides.ReportingServices.dll from the Universal directory into the report server bin directory for SSRS 2008 and later and Power BI, or from the SSRS2005 directory for SQL Server 2005. The copy carries no explicit NTFS permissions with it |
| Register | Extension entries under Render in rsreportserver.config, plus a FullTrust CodeGroup in rssrvpolicy.config. The MSI registers six renderers — ASPPT, ASPPS, ASPPTX, ASPPSX, ASXPSS (XPS) and ASODP (ODP); the hand-editing procedures register the four PowerPoint ones |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 1 | Assembly to deploy, chosen from three per-host builds in the ZIP that share the name Aspose.Slides.ReportingServices.dll: SSRS2005 (24,607,736 B), Universal (24,675,832 B) and ReportViewer2010 (24,662,520 B). One of them is copied into the report server bin directory. |
| 8 | SQL Server Reporting Services releases named as supported: 2005, 2008, 2008 R2, 2012, 2014, 2016, 2017 and 2019, 32-bit and 64-bit. Power BI Report Server sits alongside them for paginated RDL. |
| 10 | RDL element groups the documented renderer covers: pages with headers and footers, text boxes, images, sub-reports, charts, lists, tables, matrices, styles and rectangles. That published list does not extend to gauges, maps, indicators, data bars or sparklines. |
| 0 | Microsoft PowerPoint installs needed on the report server. The product internally uses Aspose.Slides for .NET to produce the presentations, with no Office automation in the path. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything here is delivered by the installed rendering extensions and switched on in the report server's own configuration files, not by code you write. Where a note follows, the capability has a stated limit or applies to one output format only." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="Need the same output from your own code rather than from a report server? The same engine ships as a library for .NET, Java, C++, Python, Node.js and PHP."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| SQL Server Reporting Services | Registered as named rendering extensions under Render in rsreportserver.config, with a FullTrust CodeGroup in rssrvpolicy.config. Documented for 2005, 2008, 2008 R2, 2012, 2014, 2016, 2017 and 2019. | 32-BIT · 64-BIT |
| Power BI Report Server | Paginated RDL reports export through the same extensions. The installer detects the Power BI server on the machine, installs the product and then configures it. | WINDOWS |
| SharePoint integrated mode | A manual integration procedure is documented for SSRS 2012 in SharePoint integrated mode, as a fallback for when MSI installation fails. It is pinned to the SharePoint 2010 hive. | SSRS 2012 · MANUAL FALLBACK |
| Visual Studio Report Designer | Copy the assembly into Common7/IDE/PrivateAssemblies, add the Extension entries to RSReportDesigner.config and a FullTrust CodeGroup to RSPreviewPolicy.config, then restart Visual Studio. Both edits are required — the CodeGroup is what grants the assembly permission to execute. | VS 2005 · VS 2008 |
| .NET Framework | .NET Framework 3.5 must be present on the host. The shipped assemblies are themselves built against the .NET 2.0 runtime (CLR 2.0.50727), which is why 3.5 rather than 4.x is the requirement. | PREREQUISITE |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/reportingservices/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR REPORTING SERVICES · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/reportingservices/)
- [API reference](https://reference.aspose.com/slides/reporting-services/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/reporting-services/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
