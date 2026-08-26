---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Java PowerPoint API | Aspose.Slides for Java"
weight: 6330
slidesIndexRebuild: true
url: /java/
description: "Aspose.Slides for Java is a PowerPoint API for creating, editing, converting, and processing PPT, PPTX, and other presentation formats in Java."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR JAVA · ON-PREMISES JAR · NO MICROSOFT OFFICE REQUIRED"
  h1="PowerPoint files, from Java."
  sub="Aspose.Slides for Java creates, edits, converts and renders PowerPoint and OpenDocument presentations from ordinary Java code. It is a pure-Java JAR whose POM declares no dependencies and which carries no native library, no COM automation and no .NET runtime underneath it. What it does need is a JVM: Java 6 or later on Windows, Linux, Unix, macOS or a container, plus fontconfig and installed fonts anywhere you render to PDF or images."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/java/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/java/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Java 6 and later, on Windows, Linux, Unix, macOS and containers. Aspose.Slides for Java is a pure-Java JAR with no declared dependencies and no native library, so a JVM is very nearly the whole prerequisite list; the exception is rendering, where a bare Linux image also needs fontconfig and installed fonts before PDF or image output looks right. The artifact resolves only from the Aspose repository at https://releases.aspose.com/java/repo/ and is not published to Maven Central, so a bare com.aspose:aspose-slides coordinate will fail until you add that repository. No Office install, no COM automation, no X display."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| CLI | mvn dependency:get -DremoteRepositories=https://releases.aspose.com/java/repo/ -Dartifact=com.aspose:aspose-slides:26.8:jar:jdk16 |
| Repository | https://releases.aspose.com/java/repo/ |
| Coordinate | com.aspose:aspose-slides:26.8:jdk16 |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 1 | JAR, resolved from the Aspose repository rather than Maven Central. Its POM declares no dependencies, so nothing is dragged in behind it and nothing native sits beside it. |
| Java 6+ | The one real prerequisite. This is pure Java, so no Office install, no COM automation and no X display enter the picture, but it runs inside a JVM and it wants fontconfig and installed fonts wherever it renders. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Java as shipped. Pick the job on the left."
  lang="JAVA"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-Java"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Read a deck once and write it back out in whichever formats your readers actually open. | PPTX -> PDF / HTML / TIFF | One Presentation instance, saved three times. Call dispose() in a finally block to release the file handles and the render cache. | https://docs.aspose.com/slides/java/convert-powerpoint-to-pdf/ |
| Slide thumbnails | Render any slide to a bitmap at a size you pick, with no PowerPoint and no screenshot. | ISlide -> IImage -> PNG | getImage() also accepts a scale pair or a RenderingOptions for notes and comments. Dispose each IImage as you go so a long deck never holds every bitmap at once. | https://docs.aspose.com/slides/java/convert-slide/ |
| Charts from data | Turn your own arrays into a native PowerPoint chart that stays editable after you hand it over. | double[] -> IChart -> PPTX | The chart carries a real embedded workbook, so whoever opens the deck can pull up the data sheet and change a number. | https://docs.aspose.com/slides/java/create-chart/ |
| Protect | Encrypt a deck so it cannot be opened, and mark it so it cannot be saved over. | PPTX -> encrypted PPTX | encrypt() sets the open password and genuinely encrypts the file. setWriteProtection() only sets the modify password, and does not. | https://docs.aspose.com/slides/java/password-protected-presentation/ |
| Merge | Fold several decks into one, carrying each slide's layout and master across with it. | 3 x PPTX -> 1 PPTX | addClone() brings the source layout and master along when the destination has no match. Overloads let you force a destination layout or master instead. | https://docs.aspose.com/slides/java/merge-presentation/ |

```
import com.aspose.slides.Presentation;
import com.aspose.slides.SaveFormat;

public class ConvertPresentation {
    public static void main(String[] args) {
        Presentation presentation = new Presentation("quarterly-review.pptx");
        try {
            presentation.save("quarterly-review.pdf", SaveFormat.Pdf);
            presentation.save("quarterly-review.html", SaveFormat.Html);
            presentation.save("quarterly-review.tiff", SaveFormat.Tiff);
        } finally {
            presentation.dispose();
        }
    }
}
```

```
import com.aspose.slides.IImage;
import com.aspose.slides.ISlide;
import com.aspose.slides.ImageFormat;
import com.aspose.slides.Presentation;

import java.awt.Dimension;

public class SlideThumbnails {
    public static void main(String[] args) {
        Presentation presentation = new Presentation("quarterly-review.pptx");
        try {
            Dimension size = new Dimension(1280, 720);
            for (int i = 0; i < presentation.getSlides().size(); i++) {
                ISlide slide = presentation.getSlides().get_Item(i);
                IImage image = slide.getImage(size);
                try {
                    image.save("slide-" + (i + 1) + ".png", ImageFormat.Png);
                } finally {
                    image.dispose();
                }
            }
        } finally {
            presentation.dispose();
        }
    }
}
```

```
import com.aspose.slides.ChartType;
import com.aspose.slides.IChart;
import com.aspose.slides.IChartDataWorkbook;
import com.aspose.slides.IChartSeries;
import com.aspose.slides.ISlide;
import com.aspose.slides.Presentation;
import com.aspose.slides.SaveFormat;

public class ChartFromData {
    public static void main(String[] args) {
        String[] quarters = { "Q1", "Q2", "Q3", "Q4" };
        double[] revenue = { 18.4, 21.9, 20.1, 26.7 };

        Presentation presentation = new Presentation();
        try {
            ISlide slide = presentation.getSlides().get_Item(0);
            IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 40, 40, 620, 400);

            IChartDataWorkbook book = chart.getChartData().getChartDataWorkbook();
            chart.getChartData().getSeries().clear();
            chart.getChartData().getCategories().clear();

            chart.getChartData().getSeries().add(book.getCell(0, 0, 1, "Revenue"), chart.getType());
            IChartSeries series = chart.getChartData().getSeries().get_Item(0);

            for (int i = 0; i < quarters.length; i++) {
                chart.getChartData().getCategories().add(book.getCell(0, i + 1, 0, quarters[i]));
                series.getDataPoints().addDataPointForBarSeries(book.getCell(0, i + 1, 1, revenue[i]));
            }

            series.getLabels().getDefaultDataLabelFormat().setShowValue(true);

            presentation.save("revenue.pptx", SaveFormat.Pptx);
        } finally {
            presentation.dispose();
        }
    }
}
```

```
import com.aspose.slides.LoadOptions;
import com.aspose.slides.Presentation;
import com.aspose.slides.SaveFormat;

public class ProtectPresentation {
    public static void main(String[] args) {
        Presentation presentation = new Presentation("quarterly-review.pptx");
        try {
            presentation.getProtectionManager().setWriteProtection("do-not-edit");
            presentation.getProtectionManager().encrypt("open-sesame");
            presentation.save("quarterly-review-protected.pptx", SaveFormat.Pptx);
        } finally {
            presentation.dispose();
        }

        LoadOptions options = new LoadOptions();
        options.setPassword("open-sesame");

        Presentation reopened = new Presentation("quarterly-review-protected.pptx", options);
        try {
            System.out.println("Encrypted: " + reopened.getProtectionManager().isEncrypted());
            System.out.println("Write protected: " + reopened.getProtectionManager().isWriteProtected());
        } finally {
            reopened.dispose();
        }
    }
}
```

```
import com.aspose.slides.ISlide;
import com.aspose.slides.Presentation;
import com.aspose.slides.SaveFormat;

public class MergePresentations {
    public static void main(String[] args) {
        String[] sources = { "results.pptx", "appendix.pptx" };

        Presentation merged = new Presentation("intro.pptx");
        try {
            for (String path : sources) {
                Presentation source = new Presentation(path);
                try {
                    for (ISlide slide : source.getSlides()) {
                        merged.getSlides().addClone(slide);
                    }
                } finally {
                    source.dispose();
                }
            }

            merged.save("deck.pptx", SaveFormat.Pptx);
        } finally {
            merged.dispose();
        }
    }
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything below is reached through plain Java objects and getters rather than a bridge or a generated wrapper, and none of it asks for PowerPoint to be installed." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model, the same class names and the same format support are available for .NET, C++, Python, PHP and Android."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| .NET | The C# and VB.NET build of the same object model, on .NET and .NET Framework. | WINDOWS · LINUX · MACOS |
| C++ | A native build for C++ projects, with no managed runtime sitting underneath it. | WINDOWS · LINUX · MACOS |
| Python via .NET | The Python package, with the .NET runtime it needs shipped inside the wheel. | WINDOWS · LINUX · MACOS |
| PHP via Java | This same JAR, driven from PHP over a Java bridge. A JVM is required there too. | WINDOWS · LINUX · MACOS |
| Android via Java | The same object model built against the Android runtime, for on-device work. | ANDROID |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/java/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR JAVA · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/java/)
- [API reference](https://reference.aspose.com/slides/java/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/java/installation)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
