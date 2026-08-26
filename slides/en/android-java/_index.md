---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Aspose.Slides for Android via Java: PowerPoint API for PPTX and PPT"
weight: 5960
slidesIndexRebuild: true
url: /android-java/
description: "Aspose.Slides for Android via Java is a PowerPoint API for creating, reading, editing, and converting PPT, POT, PPS, PPTX, POTX, and PPSX files in Android apps."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR ANDROID VIA JAVA · ITS OWN BUILD · NO SERVER, NO MICROSOFT OFFICE"
  h1="PowerPoint files, on the device."
  sub="Aspose.Slides for Android via Java opens, edits, converts and renders PowerPoint and OpenDocument presentations inside an Android app, with no server call and no Microsoft Office anywhere. It is its own build rather than the server JAR repackaged: the geometry types on its API surface are android.graphics PointF and RectF, sizes are com.aspose.slides.android.Size and IColorFormat.getColor() returns java.lang.Integer, rather than the java.awt ones, which is why this artifact runs on a device and the desktop one does not. You get it as a single JAR, aspose-slides-26.6-android.via.java.jar, 31 MB, whose POM declares no dependencies. It also declares 145,426 methods, so the first thing to plan for is not the download size but multidex."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/androidjava/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/java/aspose-slides-for-android-via-java/"
  note="Full API on trial · evaluation watermark on open and save · multidex required"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Android devices, and only Android devices. The geometry types on the API surface are android.graphics PointF and RectF, across 79 and 7 public members; sizes are com.aspose.slides.android.Size where the desktop JAR takes java.awt.Dimension, and IColorFormat.getColor() returns java.lang.Integer where the desktop JAR returns java.awt.Color. android.graphics Typeface and Paint appear only in the internal rendering backend, in 4 and 5 member signatures, and on no public member of any documented com.aspose.slides type. Across the JAR's 21,685 classes there is no reference to javax.imageio at all, and java.awt survives only as a residue in four internal classes, three of them naming java.awt.font.TextAttribute, which the Android SDK does provide, and one naming java.awt.Color, which it does not. That is why this is a separate download rather than the server JAR under another name: constructing a Presentation from this artifact on a desktop JVM fails at once with NoClassDefFoundError on android/graphics/PointF, and the desktop JAR has the mirror-image problem on a phone. Three things to plan for. The library declares 145,426 methods, well past the 65,536 references a single DEX file can hold, so multidex is mandatory, free from minSdk 21 and through the androidx.multidex library below it, and R8 shrinking belongs on every release build. Rendering and conversion are CPU-hungry and memory-hungry, so keep them off the main thread. And Android ships Roboto and the Noto families rather than the Microsoft core fonts, so bundle the fonts a deck actually uses in assets and register them through FontsLoader.loadExternalFont before you render, or accept substitution. The classes are Java 6 bytecode, so nothing about them needs desugaring, and the artifact resolves only from the Aspose repository at https://releases.aspose.com/java/repo/ with the android.via.java classifier. It is not published to Maven Central, so a bare com.aspose:aspose-slides coordinate will not find it. Everything runs on the device, so a deck opens and converts with the radio off. No minimum Android API level is stated by the product page, the install documentation or the JAR itself, so this page states none."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| Repository | maven { url 'https://releases.aspose.com/java/repo/' } |
| Dependency | implementation (group: 'com.aspose', name: 'aspose-slides', version: '26.6', classifier: 'android.via.java') |
| Multidex | android { defaultConfig { multiDexEnabled true } } |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 145,426 | Methods declared across the JAR's 21,685 classes. That is more than double the 65,536 method-reference ceiling of a single DEX file, so an app that links this library must enable multidex: free from minSdk 21, and through the androidx.multidex library below it. Keep R8 shrinking on for release builds. |
| 31 MB | The download. One JAR of 32,609,861 bytes whose POM declares no dependencies, so nothing is dragged in behind it and nothing native sits beside it. This is not the APK delta: that is a dexed and shrunk transform of 51 MiB of class data plus 18 MiB of packaged resources, and only your own release build can tell you what it costs. |
| 12 both ways | Presentation formats this build writes, counted in its own SaveFormat class, and the same 12 it reads, including the pre-2007 binary .ppt container and OpenDocument .odp. PowerPoint 95 is a detection value only: the JAR carries the string "Microsoft PowerPoint 95 presentation format is not supported." Nine further export targets sit beside them: PDF, XPS, TIFF, HTML, HTML5, SWF, GIF, MD and XML. |
| 26.6 | The current Android build. Across 2025 and 2026 the android.via.java classifier has appeared only on quarterly releases, 25.6, 25.9, 25.12, 26.3 and 26.6, so pin one of those rather than the newest Java version, which is 26.8 and ships no Android artifact at all. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Java as shipped. Pick the job on the left."
  lang="JAVA"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-Android-via-Java"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Open a deck bundled with the app and write a PDF into the app's own storage. | PPTX in assets -> PDF in getFilesDir() | The InputStream constructor is the one you want on Android, because an asset is not a file and has no path to pass. getFilesDir() keeps the result app-private and needs no storage permission, which also means nothing else on the device can open it: handing it to a viewer needs a FileProvider entry, a file_paths.xml, FileProvider.getUriForFile and ACTION_VIEW with FLAG_GRANT_READ_URI_PERMISSION. Unlicensed, an evaluation watermark is written at the top of the output. Call dispose() in a finally block, and run the whole method off the main thread. | https://docs.aspose.com/slides/androidjava/convert-presentation/ |
| Slide thumbnails | Render any slide to a PNG at a size you choose, with no PowerPoint and no screenshot. | ISlide -> IImage -> PNG in getCacheDir() | getImage() takes com.aspose.slides.android.Size in this build, where the server JAR takes java.awt.Dimension; the docs sample for this page still shows Dimension, which does not exist here. Dispose each IImage as you go so a long deck never holds every bitmap at once, and size the thumbnails to the view rather than the slide. Unlicensed, every rendered slide carries the evaluation watermark. | https://docs.aspose.com/slides/androidjava/convert-slide/ |
| Search a deck | Pull the text out of every slide so your app can search a file it has not opened. | PPTX -> IPresentationText -> slide numbers | Unarranged returns the text in storage order and is the right mode for an index; Arranged reorders it to match the reading order on the slide and is slower. Notes text comes back separately from body text. Unlicensed, every extracted string is replaced by an evaluation notice and only two slide entries come back however long the deck is, so a trial index finds nothing at all -- test this one under a temporary license. | https://docs.aspose.com/slides/androidjava/extract-text-from-presentation/ |
| Charts from data | Turn arrays your app already holds into a native PowerPoint chart that survives being emailed. | double[] -> IChart -> PPTX | The chart carries a real embedded workbook, so whoever opens the deck on a desktop can pull up the data sheet and change a number. Nothing here is rendered, so it costs far less than the two conversion tasks, though it still builds a presentation and writes that workbook. Unlicensed, the saved deck carries the evaluation watermark. | https://docs.aspose.com/slides/androidjava/create-chart/ |
| License and fonts | The two setup calls to make once, at startup, before any presentation is opened. | assets -> License and FontsLoader | setLicense() takes an InputStream, which is exactly what an Android asset gives you. Until it runs, the evaluation build watermarks documents on open and save and replaces extracted text with an evaluation notice. There is no folder inside an APK to point loadExternalFonts() at, so register bundled fonts as bytes with loadExternalFont() instead. Do both before the first render, not after. | https://docs.aspose.com/slides/androidjava/licensing/ |

```
import android.content.Context;

import com.aspose.slides.Presentation;
import com.aspose.slides.SaveFormat;

import java.io.File;
import java.io.IOException;
import java.io.InputStream;

public final class ConvertOnDevice {
    public static File toPdf(Context context, String assetName) throws IOException {
        File output = new File(context.getFilesDir(), "quarterly-review.pdf");

        InputStream input = context.getAssets().open(assetName);
        try {
            Presentation presentation = new Presentation(input);
            try {
                presentation.save(output.getAbsolutePath(), SaveFormat.Pdf);
            } finally {
                presentation.dispose();
            }
        } finally {
            input.close();
        }

        return output;
    }
}
```

```
import android.content.Context;

import com.aspose.slides.IImage;
import com.aspose.slides.ISlide;
import com.aspose.slides.ImageFormat;
import com.aspose.slides.Presentation;
import com.aspose.slides.android.Size;

import java.io.File;
import java.util.ArrayList;
import java.util.List;

public final class SlideThumbnails {
    public static List<File> render(Context context, String deckPath) {
        List<File> thumbnails = new ArrayList<File>();
        Size size = new Size(1024, 576);

        Presentation presentation = new Presentation(deckPath);
        try {
            for (int i = 0; i < presentation.getSlides().size(); i++) {
                ISlide slide = presentation.getSlides().get_Item(i);
                File file = new File(context.getCacheDir(), "slide-" + (i + 1) + ".png");

                IImage image = slide.getImage(size);
                try {
                    image.save(file.getAbsolutePath(), ImageFormat.Png);
                } finally {
                    image.dispose();
                }

                thumbnails.add(file);
            }
        } finally {
            presentation.dispose();
        }

        return thumbnails;
    }
}
```

```
import com.aspose.slides.IPresentationText;
import com.aspose.slides.ISlideText;
import com.aspose.slides.PresentationFactory;
import com.aspose.slides.TextExtractionArrangingMode;

import java.util.ArrayList;
import java.util.List;
import java.util.Locale;

public final class SearchDeck {
    public static List<Integer> slidesContaining(String deckPath, String needle) {
        List<Integer> hits = new ArrayList<Integer>();
        String query = needle.toLowerCase(Locale.ROOT);

        IPresentationText text = PresentationFactory.getInstance()
                .getPresentationText(deckPath, TextExtractionArrangingMode.Unarranged);

        ISlideText[] slides = text.getSlidesText();
        for (int i = 0; i < slides.length; i++) {
            String body = slides[i].getText() + " " + slides[i].getNotesText();
            if (body.toLowerCase(Locale.ROOT).contains(query)) {
                hits.add(i + 1);
            }
        }

        return hits;
    }
}
```

```
import android.content.Context;

import com.aspose.slides.ChartType;
import com.aspose.slides.IChart;
import com.aspose.slides.IChartDataWorkbook;
import com.aspose.slides.IChartSeries;
import com.aspose.slides.ISlide;
import com.aspose.slides.Presentation;
import com.aspose.slides.SaveFormat;

import java.io.File;

public final class ChartFromData {
    public static File build(Context context) {
        String[] quarters = { "Q1", "Q2", "Q3", "Q4" };
        double[] revenue = { 18.4, 21.9, 20.1, 26.7 };

        File output = new File(context.getFilesDir(), "revenue.pptx");

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

            presentation.save(output.getAbsolutePath(), SaveFormat.Pptx);
        } finally {
            presentation.dispose();
        }

        return output;
    }
}
```

```
import android.content.Context;

import com.aspose.slides.FontsLoader;
import com.aspose.slides.License;

import java.io.ByteArrayOutputStream;
import java.io.IOException;
import java.io.InputStream;

public final class AsposeSlidesSetup {
    public static boolean apply(Context context) throws IOException {
        License license = new License();

        InputStream input = context.getAssets().open("Aspose.Slides.Android.via.Java.lic");
        try {
            license.setLicense(input);
        } finally {
            input.close();
        }

        FontsLoader.loadExternalFont(asset(context, "fonts/Calibri.ttf"));
        FontsLoader.loadExternalFont(asset(context, "fonts/Calibri-Bold.ttf"));

        return license.isLicensed();
    }

    private static byte[] asset(Context context, String name) throws IOException {
        InputStream input = context.getAssets().open(name);
        try {
            ByteArrayOutputStream buffer = new ByteArrayOutputStream();
            byte[] chunk = new byte[8192];
            int count;
            while ((count = input.read(chunk)) != -1) {
                buffer.write(chunk, 0, count);
            }
            return buffer.toByteArray();
        } finally {
            input.close();
        }
    }
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything below is reached through plain Java objects and getters running inside your own app process, with no service call, no Office install, no PowerPoint and nothing that needs the device to be online. The object model is the full one: this build's own ShapeType class carries 187 preset shape types alongside the Custom and NotDefined sentinels, and its ChartType class carries 82 chart types." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model and the same class names ship for Java, .NET, C++, Python and Node.js. What changes in this build is the geometry types and where the code runs."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| Java | The server-side JAR this build is derived from. Same class names, java.awt geometry in place of the Android types. | WINDOWS · LINUX · MACOS |
| .NET | The C# and VB.NET build of the same object model, on .NET and .NET Framework. | WINDOWS · LINUX · MACOS |
| C++ | A native build for C++ projects, with no managed runtime sitting underneath it. | WINDOWS · LINUX · MACOS |
| Python via .NET | The Python package, with the .NET runtime it needs shipped inside the wheel. | WINDOWS · LINUX · MACOS |
| Node.js via Java | The Node.js package that drives the Java build through a bridge, for a backend doing the same work. | WINDOWS · LINUX · MACOS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/androidjava/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR ANDROID VIA JAVA · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/java/aspose-slides-for-android-via-java/)
- [API reference](https://reference.aspose.com/slides/android-java/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/android-java/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
