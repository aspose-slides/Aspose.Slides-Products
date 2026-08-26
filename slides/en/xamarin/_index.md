---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Aspose.Slides for Xamarin | Xamarin PowerPoint API"
weight: 800
slidesIndexRebuild: true
url: /xamarin/
description: "Aspose.Slides for Xamarin enables C# applications to create, edit, render, and convert PowerPoint and OpenDocument presentations."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR XAMARIN · NOT A SEPARATE PRODUCT · THE .NET PACKAGE, REFERENCED FROM A XAMARIN PROJECT"
  h1="The .NET library, from a Xamarin project."
  sub="Aspose.Slides for Xamarin is not a separate product. It is Aspose.Slides for .NET referenced from a Xamarin project: the same NuGet package, Aspose.Slides.NET, the same download page, the same licence file. A Xamarin target restores and compiles against the package's netstandard2.0 asset, so the classes you call are the .NET classes. No Xamarin-specific assembly ships in the package any more — Aspose.Slides.Droid.dll last shipped in 22.10 and was gone from 22.11 — although the assembly still embeds Xamarin.Forms project templates among its XAML-export resources. What nobody has established since is how much of the library runs on an Android device: that asset depends on System.Drawing.Common, and Android has no GDI+ behind it."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/net/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/net/aspose-slides-for-xamarin/"
  note="Full API on trial · evaluation watermark on open and save · text extraction returns only an evaluation notice"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Aspose.Slides.NET restores and compiles against a Xamarin.Android target through its netstandard2.0 asset, byte for byte the one a .NET Standard 2.0 class library gets. That is where the checkable part stops. Aspose removed its last Xamarin-specific assembly in 22.11 (2022-11-23). Its Xamarin documentation page is still live and still tells you to reference Aspose.Slides.Droid.dll — that assembly is not in any release from 22.11 onward; ignore it. The netstandard2.0 asset depends on System.Drawing.Common 5.0.3, which has no working GDI+ backend on Android, and that dependency is loaded by the Presentation constructor itself, not only at render time. Compiling is not running, and nothing on this page has been run on a Xamarin.Android device, so prove any of it on real hardware before you ship it, or do that work server-side and return the file. NuGet also lists Xamarin.iOS, Xamarin.Mac, tvOS and watchOS as compatible frameworks, but that is NuGet's netstandard2.0 compatibility table rather than a support statement, and Android is the only Xamarin target Aspose ever documented. Microsoft ended support for every Xamarin SDK on 2024-05-01. No Microsoft Office, no COM automation and no network call: the work happens in your own process."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| NuGet CLI | dotnet add package Aspose.Slides.NET |
| Package Manager | Install-Package Aspose.Slides.NET |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 1 | NuGet package to install, Aspose.Slides.NET, and one download page. There is no Xamarin-specific package and no Xamarin download: releases.aspose.com/slides/xamarin/ returns 404. |
| netstandard2.0 | The asset a Xamarin target resolves out of that package. The 26.8 package ships netstandard2.0, net6.0 and net462 and nothing else, and the netstandard2.0 group pulls System.Drawing.Common 5.0.3 with it. |
| 0 | Xamarin-specific assemblies in the release you install. Aspose.Slides.Droid.dll last shipped in 22.10 and was gone from 22.11, released 2022-11-23; the Aspose.Slides.Drawing.Xamarin types went with it. |
| 2024-05-01 | The day Microsoft ended support for every Xamarin SDK, Xamarin.Forms included. New mobile work belongs on .NET for Android or .NET MAUI, which reference this same package. |

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
| Open | Load a deck from a stream, in-process and offline. | STREAM -> PRESENTATION | The constructor does not dispose the stream — that is yours to close. By default (PresentationLockingBehavior.LoadAndRelease) it reads the source during construction and releases it, so the Presentation keeps working after you close the stream. Dispose the Presentation when you are done; until you do, the whole in-memory document stays alive. | https://reference.aspose.com/slides/net/aspose.slides/presentation/ |
| Read text | Pull every word out of a deck without laying a slide out. | PPTX -> STRING | Unarranged is the faster of the two modes and is what the docs point at when speed matters; Arranged returns the text in on-slide order and is slower. Unlicensed, extraction returns no usable text: every slide's text comes back replaced by an evaluation notice, and the array is capped at two entries whatever the deck's length. | https://reference.aspose.com/slides/net/aspose.slides/presentationfactory/getpresentationtext/ |
| Edit | Rewrite text in place and write the deck back out as PPTX. | PPTX -> PPTX | Setting portion.Text keeps that run's own font, size and colour. Setting textFrame.Text instead replaces every run in the frame and flattens it to the first run's look. | https://reference.aspose.com/slides/net/aspose.slides/iportion/text/ |
| License | Apply the licence file once, at start-up. | STREAM -> LICENSE | Call it once before the first Presentation is constructed, from Application.OnCreate rather than from an activity. Unlicensed, an evaluation watermark is inserted on open and on save, and text extraction returns no usable text — every slide's text comes back replaced by an evaluation notice. It is the same .lic file the .NET build uses. | https://reference.aspose.com/slides/net/aspose.slides/license/setlicense/ |

```
using System.IO;
using Aspose.Slides;

public static int CountSlides(Stream source)
{
    using (MemoryStream buffer = new MemoryStream())
    {
        source.CopyTo(buffer);
        buffer.Position = 0;

        using (Presentation presentation = new Presentation(buffer))
        {
            return presentation.Slides.Count;
        }
    }
}
```

```
using System.IO;
using System.Text;
using Aspose.Slides;

public static string ReadDeckText(Stream source)
{
    using (MemoryStream buffer = new MemoryStream())
    {
        source.CopyTo(buffer);
        buffer.Position = 0;

        IPresentationText text = PresentationFactory.Instance.GetPresentationText(
            buffer, TextExtractionArrangingMode.Unarranged);

        StringBuilder builder = new StringBuilder();
        foreach (ISlideText slide in text.SlidesText)
        {
            builder.AppendLine(slide.Text);
            builder.AppendLine(slide.NotesText);
        }

        return builder.ToString();
    }
}
```

```
using System.IO;
using Aspose.Slides;
using Aspose.Slides.Export;

public static void ReplaceText(Stream source, Stream output, string find, string replacement)
{
    using (Presentation presentation = new Presentation(source))
    {
        foreach (ISlide slide in presentation.Slides)
        {
            foreach (IShape shape in slide.Shapes)
            {
                IAutoShape autoShape = shape as IAutoShape;
                if (autoShape != null && autoShape.TextFrame != null)
                {
                    foreach (IParagraph paragraph in autoShape.TextFrame.Paragraphs)
                    {
                        foreach (IPortion portion in paragraph.Portions)
                        {
                            portion.Text = portion.Text.Replace(find, replacement);
                        }
                    }
                }
            }
        }

        presentation.Save(output, SaveFormat.Pptx);
    }
}
```

```
using System.IO;
using Aspose.Slides;

public static void ApplyLicense(Stream licenseStream)
{
    // Once per process, before the first Presentation is constructed.
    License license = new License();
    license.SetLicense(licenseStream);
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="The object model here is the .NET object model — one assembly, the same class and method names — so a call written in a Xamarin project is the call you would write in a console app. Every strip below is plain stream-in, stream-out C#, kept to the C# 7.3 that a classic Xamarin.Android project compiles by default, and none of it rasterises a slide. System.Drawing.Common is loaded by the Presentation constructor itself, not only by rendering and export, and nothing here has been run on a Xamarin.Android device, so prove any of it on real hardware before you depend on it or move the work server-side. Do not lean on the device's fonts either: bundle the faces your decks need and register them with FontsLoader.LoadExternalFonts. And ignore Aspose's own Xamarin documentation page — it still tells you to look for a separate Aspose.Slides.Droid.dll, four years after that assembly stopped shipping." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="Building for Android today? Aspose.Slides for Android via Java is the build Aspose actually ships for the platform. The same object model also ships for .NET, Java, C++, Python, PHP and Node.js."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| Aspose.Slides for .NET | The library this page is about, called directly. One package carries the net6.0, net462 and netstandard2.0 assets, and a Xamarin project picks the last of the three. | WINDOWS · LINUX · MACOS |
| .NET for Android and .NET MAUI | Microsoft's supported successors to Xamarin.Android and Xamarin.Forms. The same package is the one you would reference, and Aspose publishes no supported-platform statement for either, so prove anything that renders on a device before you commit a mobile target. | ANDROID · IOS |
| Aspose.Slides for Android via Java | The build Aspose actually ships for Android, on the Java engine rather than reached through Mono. The route when the app is Kotlin or Java instead of C#. | ANDROID |
| Aspose.Slides for Java | Pure Java library and the engine behind the Android build. Needs a JVM and no .NET at all. | WINDOWS · LINUX · MACOS |
| Aspose.Slides for C++ | Native library for C++ codebases, with no managed runtime to install alongside it. | WINDOWS · LINUX · MACOS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/net/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR XAMARIN · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/net/aspose-slides-for-xamarin/)
- [API reference](https://reference.aspose.com/slides/xamarin/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/xamarin/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
