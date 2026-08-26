---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "PowerPoint Conversion Solution for SharePoint"
weight: 910
slidesIndexRebuild: true
url: /sharepoint/
description: "SharePoint solution for converting PPT, PPTX, PPS, PPSX, POT, POTX, and macro-enabled presentations to PDF, TIFF, XPS, SVG, SWF, HTML, and other output formats."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR SHAREPOINT · FARM SOLUTION, NOT A LIBRARY · ONE SETUP.EXE PER SHAREPOINT GENERATION · NO MICROSOFT POWERPOINT"
  h1="Convert presentations inside SharePoint."
  sub="Aspose.Slides for SharePoint is a deployed solution, not a component you program against. You download one archive and run the Setup<version>.exe matching your farm — Setup2007, Setup2010, Setup2013, Setup2016 or Setup2019 — on the SharePoint server, and the solution adds a convert command to the Edit Control Block menu of items in document libraries, in every site collection where the feature has been activated; the 2007 package labels it Convert with Aspose.Slides, the 2019 package labels it Convert via Aspose.Slides... A person picks the output format, the destination file name and the destination folder, clicks Convert, and the converted file is written back into a SharePoint document library, with a results page that reports each file's status and offers Return to Source Library or Destination Library. Nothing is downloaded to a desktop first, no Microsoft PowerPoint is installed on the server, and nobody writes any code."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/sharepoint/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/sharepoint/"
  note="Free trial · evaluation watermark on each slide of every exported document until the licence package is deployed"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Windows Server, on-premises, inside your own SharePoint farm. The documented system requirements list Windows SharePoint Services 3.0, Microsoft Office SharePoint Server 2007, and SharePoint Server 2010, 2013, 2016 and 2019; Service Pack 2 or later is recommended for WSS 3.0 and MOSS 2007, while 2016 and 2019 are serviced by feature packs and public updates instead. The 26.7 archive ships a solution package and a matching installer for each of 2007, 2010, 2013, 2016 and 2019, and you run the one that matches your farm. That version-specific installer carries a minimum-version gate of its own: Setup2019.exe.config declares Require=“MOSS”, MinSharePointVersion 12.0.0.0 and no maximum. Aspose’s installation documentation adds three further conditions it says the installer checks — the SharePoint database online, the WSS Administration and Timer services running, and an account allowed to deploy SharePoint solutions. Deployment puts a version-specific Aspose.Slides.SharePoint assembly into the Global Assembly Cache and adds SafeControl entries to web.config; activation is scoped to a site collection, and in the 2007 package a feature receiver copies resource files into App_GlobalResources on the parent web application. The licence is a second solution package, Aspose.Slides.SharePoint.License.wsp, shipped in its own archive and deployed from the server console with stsadm.exe; until it is deployed, every exported document carries an evaluation watermark on each slide. No Microsoft PowerPoint and no Office automation on the server. Every supported host is an on-premises server product, so this is a farm solution rather than a SharePoint Online or Microsoft 365 add-in."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| Download | Aspose.Slides.SharePoint_26.7.zip |
| Deploy | Unpack, then run the Setup<version>.exe matching your farm (Setup2007/2010/2013/2016/2019) |
| License | Aspose.Slides.SharePoint.License.wsp via stsadm.exe -o deploysolution |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 5 .wsp | One solution package per SharePoint generation — Aspose.Slides.SharePoint2007.wsp, 2010.wsp, 2013.wsp, 2016.wsp and 2019.wsp — shipped in one archive alongside Setup2007.exe, Setup2010.exe, Setup2013.exe, Setup2016.exe and Setup2019.exe. You deploy the one that matches your farm. A licensed install deploys a second package, Aspose.Slides.SharePoint.License.wsp, over the top; without it the solution runs in evaluation mode. |
| 12 | Export targets named by the shipped 26.7 assembly, whose own feature description reads: "Converts documents with Aspose.Slides. Supports converting to pdf, tiff, xps, pps, ppsx, odp, pptm, ppsm, potx, potm, html and swf formats." Its resource table also carries notes-view targets for PDF, TIFF and SWF. The 2007 package's resource file is narrower: PDF, TIFF and XPS only. |
| WSS 3.0 to 2019 | Supported SharePoint hosts on the documented system requirements page, six of them, every one an on-premises server product. The current download page names four — WSS 3.0, MOSS 2007, SharePoint Server 2013 and SharePoint Server 2019 — while the 26.7 archive itself ships solution packages for 2007, 2010, 2013, 2016 and 2019. |
| 0 | Microsoft PowerPoint installations on the server. Conversion runs in managed code inside the SharePoint worker process, with no Office automation anywhere in the path. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything below happens in the SharePoint UI, done by a person browsing a document library. Activating the feature on a site collection is what makes the command appear there, and a site collection where it has not been activated is unchanged. Conversion runs in managed code inside the SharePoint worker process; the solution has no documented API surface of its own." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="This is a deployed solution, not a component you program. If you need to convert presentations from your own code, Aspose ships separate libraries for .NET, Java, C++, Python and Node.js."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| Windows SharePoint Services 3.0 | The oldest supported host, and one of the two the installation guide is written against. Service Pack 2 or later is recommended. Named on the current download page. | WSS 3.0 · ON-PREMISES |
| Microsoft Office SharePoint Server 2007 | Standard and Enterprise both, and the other host the installation guide is written against. Service Pack 2 or later is recommended. Named on the current download page. | MOSS 2007 · ON-PREMISES |
| SharePoint Server 2010 | Listed in the documented system requirements. Deployed exactly the same way: one solution package, activated per site collection. The 26.7 archive ships Aspose.Slides.SharePoint2010.wsp with Setup2010.exe. | SP2010 · FARM SOLUTION |
| SharePoint Server 2013 | Listed both in the documented system requirements and on the current download page as a supported server. | SP2013 · FARM SOLUTION |
| SharePoint Server 2016 | Listed in the documented system requirements; the 26.7 archive ships Aspose.Slides.SharePoint2016.wsp with Setup2016.exe. Serviced by feature packs and public updates rather than service packs, so no service pack level applies here. | SP2016 · FARM SOLUTION |
| SharePoint Server 2019 | The newest supported host, named on the current 26.7 download page alongside WSS 3.0, MOSS 2007 and SharePoint Server 2013. Serviced by public updates rather than service packs. | SP2019 · FARM SOLUTION |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/sharepoint/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR SHAREPOINT · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/sharepoint/)
- [API reference](https://reference.aspose.com/slides/sharepoint/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/sharepoint/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
