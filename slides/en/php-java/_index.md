---
lastmod: 2026-08-28
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "PHP PowerPoint API for PPT, PPTX, and ODP Presentations"
weight: 5890
slidesIndexRebuild: true
url: /php-java/
description: "PHP library for creating, editing, converting, and processing presentations in formats such as PPT, PPTX, PPS, POT, PPSX, PPTM, PPSM, POTX, POTM, and ODP, with support for PDF output."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR PHP VIA JAVA · ON-PREMISES LIBRARY · JVM-BACKED · NO OFFICE REQUIRED"
  h1="PowerPoint files, from PHP."
  sub="Aspose.Slides for PHP via Java creates, edits, converts and renders PowerPoint and OpenDocument presentations from PHP. It is not a native extension: the Composer package aspose/slides is a thin PHP surface over the Java build, so the host needs a JRE and the PHP/Java Bridge running in a servlet container alongside PHP. What it does not need is a Microsoft Office install, COM automation or a display server."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/php-java/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/php-java/"
  note="Full API on trial · watermark on output"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Operations|#operations, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="Anywhere a Java runtime runs: Windows, Linux and macOS, 32-bit or 64-bit. You need PHP 7.0 or later with allow_url_include on, a JRE 8 or later with JAVA_HOME set, and the PHP/Java Bridge deployed as JavaBridge.war in a servlet container such as Tomcat, with the package's aspose-slides JAR copied into JavaBridge/WEB-INF/lib. PHP 8 hosts swap in the Java.inc from Java.inc.php8.zip that ships in the package. Note that files are opened and written by the JVM, not by PHP, so relative paths resolve against the servlet container's working directory - use absolute paths. Aspose's reference container is Ubuntu 20.04 with OpenJDK 8, Tomcat 9 and php-cli, and carries no Microsoft Office and no X display."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| Composer | composer require aspose/slides |
| Bridge JAR | cp vendor/aspose/slides/jar/aspose-slides-*-php.jar $CATALINA_HOME/webapps/JavaBridge/WEB-INF/lib/ |
| PHP wrapper | require_once("vendor/aspose/slides/lib/aspose.slides.php"); |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 189 / 82 | Shape types and chart types, each a real object that PowerPoint still recognises and lets a person edit. |
| 13 -> 12 | Presentation formats read and written, including the pre-2007 binary .ppt container and OpenDocument .odp, plus 9 further export targets. |
| 1 | Composer package, aspose/slides. It wraps the Java build rather than replacing it, so it is not the only thing you install. |
| JRE 8+ | Java runtime with JAVA_HOME set, plus the PHP/Java Bridge in a servlet container. Still zero Microsoft Office installs and zero X displays. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, PHP as shipped. Pick the job on the left."
  lang="PHP"
  allText="All examples on GitHub" allHref="https://github.com/aspose-slides/Aspose.Slides-for-PHP-via-Java"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Convert | Load a deck once and write it out in as many formats as you need. | PPTX -> PDF / HTML / TIFF | One save call per target, and no options object needed for sane defaults. SaveFormat also carries XPS, Markdown, GIF and the OpenDocument containers. | https://docs.aspose.com/slides/php-java/convert-powerpoint-to-pdf/ |
| Slide thumbnails | Render any slide to a raster image at an exact pixel size. | Slide -> PNG at 1200 x 800 | getImage returns an image object you dispose yourself. Pass a scale factor instead of a Dimension to render relative to the slide size. | https://docs.aspose.com/slides/php-java/presentation-viewer/ |
| Charts from data | Turn a PHP array into a native chart the recipient can still edit. | PHP array -> ClusteredColumn chart | Values land in the chart's embedded workbook, so PowerPoint opens a live data sheet rather than a flat picture. | https://docs.aspose.com/slides/php-java/create-chart/ |
| Protect | Encrypt a deck and lock editing before it leaves your server. | PPTX -> encrypted PPTX | encrypt sets the password needed to open the file. setWriteProtection sets a separate one needed to change it; the two are independent. | https://docs.aspose.com/slides/php-java/password-protected-presentation/ |
| Merge | Clone slides out of several decks into one and unify the design. | 3 x PPTX -> 1 PPTX | Pass the destination master to addClone and the result carries one master instead of three. Loop by index: slide collections are Java objects and do not support PHP foreach. | https://docs.aspose.com/slides/php-java/merge-presentation/ |

```
<?php
define("JAVA_HOSTS", "localhost:8080");
define("JAVA_SERVLET", "/JavaBridge/servlet.phpjavabridge");

require_once("Java.inc");
require_once("vendor/aspose/slides/lib/aspose.slides.php");

use aspose\slides\Presentation;
use aspose\slides\SaveFormat;

$presentation = new Presentation("/srv/decks/quarterly-review.pptx");
try {
    $presentation->save("/srv/decks/quarterly-review.pdf", SaveFormat::Pdf);
    $presentation->save("/srv/decks/quarterly-review.html", SaveFormat::Html);
    $presentation->save("/srv/decks/quarterly-review.tiff", SaveFormat::Tiff);
} finally {
    $presentation->dispose();
}
```

```
<?php
define("JAVA_HOSTS", "localhost:8080");
define("JAVA_SERVLET", "/JavaBridge/servlet.phpjavabridge");

require_once("Java.inc");
require_once("vendor/aspose/slides/lib/aspose.slides.php");

use aspose\slides\ImageFormat;
use aspose\slides\Presentation;

$size = new Java("java.awt.Dimension", 1200, 800);

$presentation = new Presentation("/srv/decks/quarterly-review.pptx");
try {
    $slides = $presentation->getSlides();

    for ($i = 0; $i < java_values($slides->size()); $i++) {
        $image = $slides->get_Item($i)->getImage($size);
        try {
            $image->save("/srv/decks/slide-" . ($i + 1) . ".png", ImageFormat::Png);
        } finally {
            $image->dispose();
        }
    }
} finally {
    $presentation->dispose();
}
```

```
<?php
define("JAVA_HOSTS", "localhost:8080");
define("JAVA_SERVLET", "/JavaBridge/servlet.phpjavabridge");

require_once("Java.inc");
require_once("vendor/aspose/slides/lib/aspose.slides.php");

use aspose\slides\ChartType;
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;

$data = ["Q1" => 120, "Q2" => 145, "Q3" => 132, "Q4" => 168];

$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);
    $chart = $slide->getShapes()->addChart(ChartType::ClusteredColumn, 50, 50, 600, 400);

    $chartData = $chart->getChartData();
    $workbook = $chartData->getChartDataWorkbook();
    $sheet = 0;

    $chartData->getSeries()->clear();
    $chartData->getCategories()->clear();
    $chartData->getSeries()->add($workbook->getCell($sheet, 0, 1, "Signups"), $chart->getType());

    $series = $chartData->getSeries()->get_Item(0);
    $row = 1;

    foreach ($data as $quarter => $value) {
        $chartData->getCategories()->add($workbook->getCell($sheet, $row, 0, $quarter));
        $series->getDataPoints()->addDataPointForBarSeries($workbook->getCell($sheet, $row, 1, $value));
        $row++;
    }

    $presentation->save("/srv/decks/signups-by-quarter.pptx", SaveFormat::Pptx);
} finally {
    $presentation->dispose();
}
```

```
<?php
define("JAVA_HOSTS", "localhost:8080");
define("JAVA_SERVLET", "/JavaBridge/servlet.phpjavabridge");

require_once("Java.inc");
require_once("vendor/aspose/slides/lib/aspose.slides.php");

use aspose\slides\Presentation;
use aspose\slides\SaveFormat;

$presentation = new Presentation("/srv/decks/quarterly-review.pptx");
try {
    $protection = $presentation->getProtectionManager();
    $protection->setWriteProtection("edit-password");
    $protection->encrypt("open-password");

    $presentation->save("/srv/decks/quarterly-review-protected.pptx", SaveFormat::Pptx);
} finally {
    $presentation->dispose();
}
```

```
<?php
define("JAVA_HOSTS", "localhost:8080");
define("JAVA_SERVLET", "/JavaBridge/servlet.phpjavabridge");

require_once("Java.inc");
require_once("vendor/aspose/slides/lib/aspose.slides.php");

use aspose\slides\Presentation;
use aspose\slides\SaveFormat;

$parts = ["/srv/decks/intro.pptx", "/srv/decks/results.pptx", "/srv/decks/roadmap.pptx"];

$merged = new Presentation($parts[0]);
try {
    $master = $merged->getMasters()->get_Item(0);

    for ($i = 1; $i < count($parts); $i++) {
        $source = new Presentation($parts[$i]);
        try {
            $slides = $source->getSlides();

            for ($j = 0; $j < java_values($slides->size()); $j++) {
                $merged->getSlides()->addClone($slides->get_Item($j), $master, true);
            }
        } finally {
            $source->dispose();
        }
    }

    $merged->save("/srv/decks/merged.pptx", SaveFormat::Pptx);
} finally {
    $merged->dispose();
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-solution-platforms
  id="operations"
  title="Browse by operation"
  lede="Each operation has its own page, listing the formats it covers with a code sample for each."
>}}

| Operation | Href | Note | Language | Icon |
|---|---|---|---|---|
| Conversion | /slides/php-java/conversion/ | Convert between presentation, document and image formats. | PHP | conversion |
| Merger | /slides/php-java/merger/ | Combine several presentations, documents or images into one file. | PHP | merger |
| Editor | /slides/php-java/editor/ | Open a file, change it and write it back, format by format. | PHP | editor |

{{< /blocks/products/pf/slides-solution-platforms >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything the Java engine does is reachable from PHP - shapes, tables, charts, SmartArt, animations, speaker notes, comments, sections and every export target in the JAR - so long as you remember that each value handed back is a Java object rather than a PHP one." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="The same object model ships for .NET, Java, C++, Python, Node.js and Android, so moving a deck pipeline between runtimes is renaming, not rewriting."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| .NET | Native managed library, one NuGet package, no JVM anywhere in the stack. | WINDOWS · LINUX · MACOS |
| Java | The engine this package wraps. Call it directly and the bridge disappears. | WINDOWS · LINUX · MACOS |
| Node.js via Java | The closest sibling to this build: same JAR, same object model, a JavaScript surface. | WINDOWS · LINUX · MACOS |
| Python via .NET | Same object model over the .NET build, so it asks for no Java runtime at all. | WINDOWS · LINUX · MACOS |
| C++ | Native code, no managed runtime and no JVM to provision or tune. | WINDOWS · LINUX · MACOS |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and replaces extracted text with an evaluation notice, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/php-java/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR PHP VIA JAVA · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/php-java/)
- [API reference](https://docs.aspose.com/slides/php-java/api-reference/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/php-java/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
