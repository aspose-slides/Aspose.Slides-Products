---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Aspose.Slides for .NET Core | .NET Core PowerPoint API"
weight: 5190
slidesIndexRebuild: true
url: /net-core/
description: "Aspose.Slides for .NET Core is a PowerPoint API for building .NET Core presentation-processing solutions."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR .NET · THE SAME PACKAGE, ON .NET CORE · NO MICROSOFT OFFICE REQUIRED"
  h1="PowerPoint files, on .NET Core."
  sub="There is no separate .NET Core product, package or download. Aspose.Slides for .NET Core is Aspose.Slides for .NET — the same Aspose.Slides.NET NuGet package, the same download, the same API — resolved against a .NET Core or .NET 6 and later target framework. The same C# creates, edits, converts and renders PowerPoint and OpenDocument presentations on Windows, Linux and macOS, inside your own process, with no Office install and no COM automation."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/net/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/display/slidesnet/Home"
  note="Same package as the .NET build · full API on trial · evaluation watermark on open and save"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn=".NET Core, .NET 5, 6, 7, 8 and 9 — the versions Aspose's system requirements name; .NET 10 is not among them. Windows, Linux, macOS and containers. On non-Windows the standard build needs libgdiplus and the fonts your decks use, whichever asset you bind; the net6.0 asset additionally needs one AppContext switch at startup, System.Drawing.EnableUnixSupport. The Aspose.Slides.NET6.CrossPlatform package removes libgdiplus and the switch on glibc hosts, though every build still needs the fonts. No Office, no COM automation, no display server."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| CLI | dotnet add package Aspose.Slides.NET |
| Console | Install-Package Aspose.Slides.NET |
| Linux and macOS | libgdiplus and fonts on the image; on .NET 6 or later also the System.Drawing.EnableUnixSupport AppContext switch at startup |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 1 | NuGet package, Aspose.Slides.NET, shared with the .NET build. There is no .NET Core package to look for and no separate .NET Core download. |
| 3 | Target frameworks inside that one package in 26.8.0 — net462, netstandard2.0 and net6.0. A .NET Core project binds to one of the last two on its own. |
| 26.8.0 | Current version on NuGet, published 2026-08-03, and the same version a .NET Framework project resolves. No .NET Core version line runs beside it. |
| 0 | Microsoft PowerPoint installs and Office automation calls in the deployment. Rendering happens inside your own process, with no display server. |

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
| Convert | One load, several output formats | PPTX → PDF / HTML / TIFF | The same call on Windows, Linux and macOS. The rendering engine ships in the package. | https://docs.aspose.com/slides/net/convert-presentation/ |
| Start on Linux | The startup lines, plus libgdiplus on the image | STARTUP → RENDERING | libgdiplus is needed on the image whichever asset you bind. The switch is required on non-Windows for the net6.0 asset, which uses System.Drawing.Common 6.0.0. It is not needed on .NET Core or .NET 5, where it does not exist. Fonts are needed by every build. | https://docs.aspose.com/slides/net/system-requirements/ |
| Slide images | A PNG per slide, no display server | PPTX → PNG | GetImage(2f, 2f) renders at twice slide size. The parameterless overload returns a small preview instead. | https://docs.aspose.com/slides/net/convert-powerpoint-to-png/ |
| Streams | No temp files in a web request | UPLOAD → PDF RESPONSE | Minimal API on .NET 8, where an IFormFile endpoint is antiforgery-validated unless you opt out. DisableAntiforgery is safe on an unauthenticated or bearer-token endpoint, not on a cookie-authenticated one. One Presentation instance per request, never shared across threads. | https://docs.aspose.com/slides/net/open-presentation/ |
| License | Applied once per process | EMBEDDED LIC → FULL API | Without it an evaluation watermark is inserted on open and on save, and text extraction returns one slide only. | https://docs.aspose.com/slides/net/licensing/ |

```
using Aspose.Slides;
using Aspose.Slides.Export;

using var presentation = new Presentation("quarterly-review.pptx");

presentation.Save("review.pdf", SaveFormat.Pdf);
presentation.Save("review.html", SaveFormat.Html);
presentation.Save("review.tiff", SaveFormat.Tiff);
```

```
using System;
using Aspose.Slides;
using Aspose.Slides.Export;

// Once at startup on Linux or macOS, for the net6.0 asset.
AppContext.SetSwitch("System.Drawing.EnableUnixSupport", true);

// A slim image ships almost no fonts, so point the renderer at the ones you deploy.
FontsLoader.LoadExternalFonts(new[] { "/app/fonts" });

using (var presentation = new Presentation("/data/deck.pptx"))
{
    presentation.Save("/data/deck.pdf", SaveFormat.Pdf);
}

FontsLoader.ClearCache();
```

```
using Aspose.Slides;

using var presentation = new Presentation("deck.pptx");

for (int index = 0; index < presentation.Slides.Count; index++)
{
    ISlide slide = presentation.Slides[index];

    using IImage image = slide.GetImage(2f, 2f);
    image.Save($"slide-{index + 1}.png", ImageFormat.Png);
}
```

```
using Aspose.Slides;
using Aspose.Slides.Export;

var builder = WebApplication.CreateBuilder(args);
var app = builder.Build();

app.MapPost("/convert", async (IFormFile file) =>
{
    await using var upload = file.OpenReadStream();
    using var presentation = new Presentation(upload);

    var pdf = new MemoryStream();
    presentation.Save(pdf, SaveFormat.Pdf);
    pdf.Position = 0;

    return Results.File(pdf, "application/pdf", "converted.pdf");
}).DisableAntiforgery();

app.Run();
```

```
using System.IO;
using System.Reflection;
using Aspose.Slides;

// Once per process, before the first Presentation is constructed.
using Stream licenseStream = Assembly
    .GetExecutingAssembly()
    .GetManifestResourceStream("MyApp.Aspose.Slides.NET.lic");

var license = new License();
license.SetLicense(licenseStream);
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="This is the .NET build's capability list, unchanged, because .NET Core loads the same assembly. Two lines need a runtime qualifier rather than a product one: printing goes through System.Drawing printer settings and is Windows-only under .NET Core, and rendering fidelity depends on the fonts present in the image. Where a grey note follows, the capability is delivered through a separate product or comes with a stated limit." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same package also targets .NET Framework 4.6.2 for Windows-only work. Same object model on other platforms: Java, Python, C++, Node.js, Android, PHP, SharePoint and JasperReports."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| .NET Core and .NET 5 | Both resolve the netstandard2.0 asset — the net6.0 asset needs .NET 6 or later. That asset declares System.Drawing.Common 5.0.3, so on non-Windows it needs libgdiplus like the net6.0 asset does. Aspose names .NET Core with no minimum version, so there is no vendor-stated floor to quote. The System.Drawing.EnableUnixSupport switch arrived with System.Drawing.Common 6.0 and is neither present nor needed here. | WINDOWS · LINUX · MACOS |
| .NET 6, 7, 8 and 9 | Binds to the net6.0 asset, which brings System.Drawing.Common 6.0.0 with it. Where new work should start. Aspose's supported-versions list ends at .NET 9 and does not name .NET 10, so confirm with Aspose before targeting it. | WINDOWS · LINUX · MACOS |
| Linux containers | The standard build wants libgdiplus. Alpine images also need a font package such as ttf-dejavu, or rendering fails on a missing font. | DOCKER · KUBERNETES |
| ASP.NET Core | Read the request stream, write the response stream, no temp files. One Presentation instance per request and never shared between threads. | KESTREL · IIS · AZURE |
| Aspose.Slides.NET6.CrossPlatform | Optional sibling package, net6.0 and later, with Aspose's own graphics engine and no System.Drawing.Common dependency. It needs glibc — 2.23 or later on x64, 2.39 or later on ARM64 — so musl images such as Alpine, and CentOS 7, stay on the standard build. | LINUX · MACOS · WINDOWS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/net/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR .NET CORE · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/display/slidesnet/Home)
- [API reference](https://reference.aspose.com/slides/net-core/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/net-core/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
