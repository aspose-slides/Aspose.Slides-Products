---
lastmod: 2026-08-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: "Export JasperReports to PowerPoint | Aspose.Slides"
weight: 8320
slidesIndexRebuild: true
url: /jasperreports/
description: "Aspose.Slides for JasperReports exports JasperReports and JasperServer reports to PowerPoint formats such as PPT, PPTX, PPS, and PPSX."
outputs: ["HTML", "MDTWIN", "LLMS"]
---

{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/slides-hero
  eyebrow="ASPOSE.SLIDES FOR JASPERREPORTS · EXPORTER JAR · NO MICROSOFT POWERPOINT REQUIRED"
  h1="PowerPoint output for JasperReports."
  sub="Aspose.Slides for JasperReports is an exporter, not a presentation API. One library JAR goes onto the JasperReports classpath and adds four exporter classes - ASPptExporter, ASPptxExporter, ASPdfExporter and ASHtmlExporter - each taking the same filled JasperPrint your PDF and HTML exporters already take. JasperServer needs that same library JAR plus a small server JAR beside it, both in jasperserver/WEB-INF/lib. Your report designs are not touched: the exporter walks the printed elements and writes real slides and shapes, so what comes out is an editable deck rather than a picture of the report. The presentation engine is compiled into the library JAR, so there is no second dependency and Microsoft PowerPoint is never installed or automated. This is a separate product with its own download and its own licence, distributed as a ZIP rather than through Maven."
  ctaPrimaryText="Download free trial" ctaPrimaryUrl="https://releases.aspose.com/slides/jasperreport/"
  ctaSecondaryText="Documentation" ctaSecondaryUrl="https://docs.aspose.com/slides/jasperreports/"
  note="Evaluation has no time limit · watermark at the centre of every slide"
  moreText="Other platforms, same object model" moreUrl="/slides/family/"
  jump="Code|#tasks, Formats|#formats, Capabilities|#capabilities, Runtimes|#runtimes, Licensing|#pricing"
  runsOnTitle="RUNS ON"
  runsOn="JasperReports Library 3.7.2 through 6.16.0 and JasperReports Server, on any JVM from Java 6 upward. The ZIP carries three builds of the library JAR - for JasperReports 3.7.2 to 5.5.1, 5.5.2 to 6.4.0, and 6.5.0 to 6.16.0 - and you copy the one whose folder name covers your JasperReports into its lib directory. JasperServer needs that library JAR and aspose.slides.jasperreports.server-26.6.jar together in jasperserver/WEB-INF/lib, because the server JAR holds only the adapter classes and none of the engine - six of them in the 6.5.0 to 6.16.0 build, eleven in the two builds below 6.5.0, whose five extra classes are ASAbstractWSExporter, ASPptWSExporter, ASPptxWSExporter, ASPdfWSExporter and ASHtmlWSExporter, implementing com.jaspersoft.jasperserver.ws.axis2.WSExporter; it also needs a bean registration in viewReportBeans.xml and takes its settings from an ASExportParametersBean in applicationContext.xml. Support for JDK 1.4 and JasperReports 2.0.3 to 3.7.1 was discontinued at version 17.6.0. There is no Maven coordinate and no package-manager route of any kind: this product is distributed only as a ZIP from releases.aspose.com. The library has no native components, but it does reach AWT for text measurement, so run it headless with java.awt.headless=true and install the fonts your reports call for. No Office install and no PowerPoint automation."
  cloudNote="Prefer not to host it yourself? The same work is available as a hosted REST API through [Aspose.Slides Cloud](https://products.aspose.cloud/slides/family/)."
>}}

| Label | Install |
|---|---|
| Download | aspose-slides-26.6-jasperreports.zip from releases.aspose.com, there is no Maven coordinate |
| JasperReports | copy aspose.slides.jasperreports.library-26.6.jar, from the lib folder whose name covers your JasperReports version, into JasperReports/lib |
| JasperServer | copy the library AND server 26.6 JARs into jasperserver/WEB-INF/lib, then register the exporter bean in viewReportBeans.xml |

{{< /blocks/products/pf/slides-hero >}}

{{< blocks/products/pf/slides-stat-row >}}

| Figure | Caption |
|---|---|
| 4 | Exporter classes in the library JAR: ASPptExporter, ASPptxExporter, ASPdfExporter and ASHtmlExporter. Each is an ordinary JRExporter, so it accepts the JasperPrint your existing export step already produces. |
| 1 JAR | One self-contained library JAR of 27.7 MB holding 20,382 classes - 20,383 in the 5.5.2 to 6.4.0 build - with the presentation engine compiled in and not a single native .dll, .so or .dylib. JasperServer adds a 14-19 KB server JAR beside it. |
| 3.7.2 to 6.16.0 | JasperReports Library versions covered, shipped as three separate builds inside the same ZIP. Copy the one whose folder name covers your JasperReports. Support for JDK 1.4 and JasperReports 2.0.3 to 3.7.1 ended at version 17.6.0. |
| 6 | Export parameters this JAR adds beside the standard JasperReports ones: a licence path, a font substitution map, a font embedding mode, an alt-text flag, a default template deck and a per-report template map. The full reference ships as a javadoc JAR in the ZIP's doc folder rather than on the web. |

{{< /blocks/products/pf/slides-stat-row >}}

{{< blocks/products/pf/slides-task-tabs
  id="tasks"
  title="Five things people actually write"
  lede="Each sample is the whole program, Java as shipped. Pick the job on the left."
  lang="JAVA"
>}}

| Task | Hint | Flow | Note | Docs |
|---|---|---|---|---|
| Export a filled report | Take a report you have already filled and write it out as a PowerPoint deck instead of a PDF. | JasperPrint -> PPTX | ASPptxExporter is an ordinary JRExporter, so it reads JASPER_PRINT and OUTPUT_FILE_NAME like every exporter you already use. ASPptExporter writes the binary 97-2003 format, and ASPdfExporter and ASHtmlExporter take the same JasperPrint. | https://docs.aspose.com/slides/jasperreports/ppt-pptx-pdf-and-html-export/ |
| Fill and export in one pass | Compile the design, fill it, and hand the result straight to the exporter. | JRXML -> JasperPrint -> PPT | JasperFillManager produces exactly the JasperPrint the exporters consume, so the PowerPoint step drops in beside your existing PDF step without changing anything upstream of it. Take the data source or the JDBC connection from your container rather than hard-coding credentials in a scheduled job. | https://docs.aspose.com/slides/jasperreports/product-overview/ |
| Export onto your own deck | Land the report on a branded template instead of a blank presentation. | PPTX template + JasperPrint -> branded PPTX | PPT_TEMPLATE_PRESENTATION sets the template used for everything. PPT_TEMPLATE_MAP_PRESENTATION overrides it per report, keyed by the JasperPrint name, and reports absent from the map fall back to the default. Neither constant appears on any web page; the reference for both is the javadoc JAR in the ZIP's doc folder. |  |
| Embed the fonts | Map the report's logical fonts onto real faces, then embed only what the deck uses. | font map -> PPTX with fonts embedded | PPT_EMBED_FONTS takes OnlyUsed to embed only the characters the deck uses, or All to embed whole faces; omit the parameter and 26.6 embeds nothing. Set PPT_FONT_MAP alongside it: with embedding switched on and a logical font such as SansSerif left unmapped, the export stops with Font not found. | https://docs.aspose.com/slides/jasperreports/integration-with-jasperserver/ |
| Apply the licence | Lift the evaluation watermark, either once for the JVM or per export. | lic file -> licensed exporter | License.setLicense() licenses the component for the process and isLicensed() tells you whether it took. PPT_LICENSE does the same job for a single export from a file path, which is the form JasperServer uses through the licenseFile property on its ASExportParametersBean. | https://docs.aspose.com/slides/jasperreports/licensing/ |

```
import com.aspose.slides.jasperreports.ASPptxExporter;

import net.sf.jasperreports.engine.JRExporterParameter;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.util.JRLoader;

public class ExportReportToPptx {
    public static void main(String[] args) throws Exception {
        JasperPrint jasperPrint =
                (JasperPrint) JRLoader.loadObjectFromFile("QuarterlySales.jrprint");

        ASPptxExporter exporter = new ASPptxExporter();
        exporter.setParameter(JRExporterParameter.JASPER_PRINT, jasperPrint);
        exporter.setParameter(JRExporterParameter.OUTPUT_FILE_NAME, "QuarterlySales.pptx");
        exporter.exportReport();
    }
}
```

```
import com.aspose.slides.jasperreports.ASPptExporter;

import net.sf.jasperreports.engine.JREmptyDataSource;
import net.sf.jasperreports.engine.JRExporterParameter;
import net.sf.jasperreports.engine.JasperCompileManager;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.JasperReport;

import java.util.HashMap;
import java.util.Map;

public class FillAndExport {
    public static void main(String[] args) throws Exception {
        JasperReport report = JasperCompileManager.compileReport("QuarterlySales.jrxml");

        Map<String, Object> parameters = new HashMap<String, Object>();
        parameters.put("Quarter", "Q3");

        // Swap JREmptyDataSource for your own JRDataSource, or for a Connection taken
        // from the container's DataSource, rather than hard-coding credentials here.
        JasperPrint jasperPrint =
                JasperFillManager.fillReport(report, parameters, new JREmptyDataSource());

        ASPptExporter exporter = new ASPptExporter();
        exporter.setParameter(JRExporterParameter.JASPER_PRINT, jasperPrint);
        exporter.setParameter(JRExporterParameter.OUTPUT_FILE_NAME, "QuarterlySales.ppt");
        exporter.exportReport();
    }
}
```

```
import com.aspose.slides.jasperreports.ASExporterParameters;
import com.aspose.slides.jasperreports.ASPptxExporter;

import net.sf.jasperreports.engine.JRExporterParameter;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.util.JRLoader;

import java.util.HashMap;
import java.util.Map;

public class ExportOntoTemplate {
    public static void main(String[] args) throws Exception {
        JasperPrint jasperPrint =
                (JasperPrint) JRLoader.loadObjectFromFile("QuarterlySales.jrprint");

        // Keyed by report name, so QuarterlySales lands on finance.pptx and
        // every other report falls back to corporate.pptx.
        Map<String, String> perReport = new HashMap<String, String>();
        perReport.put("QuarterlySales", "finance.pptx");

        ASPptxExporter exporter = new ASPptxExporter();
        exporter.setParameter(JRExporterParameter.JASPER_PRINT, jasperPrint);
        exporter.setParameter(JRExporterParameter.OUTPUT_FILE_NAME, "QuarterlySales.pptx");
        exporter.setParameter(
                ASExporterParameters.PPT_TEMPLATE_PRESENTATION, "corporate.pptx");
        exporter.setParameter(
                ASExporterParameters.PPT_TEMPLATE_MAP_PRESENTATION, perReport);
        exporter.exportReport();
    }
}
```

```
import com.aspose.slides.jasperreports.ASExporterParameters;
import com.aspose.slides.jasperreports.ASPptxExporter;

import net.sf.jasperreports.engine.JRExporterParameter;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.util.JRLoader;

import java.util.HashMap;
import java.util.Map;

public class ExportWithFonts {
    public static void main(String[] args) throws Exception {
        JasperPrint jasperPrint =
                (JasperPrint) JRLoader.loadObjectFromFile("QuarterlySales.jrprint");

        // Map every logical font the report uses onto a real installed face.
        Map<String, String> fontMap = new HashMap<String, String>();
        fontMap.put("SansSerif", "Arial");
        fontMap.put("Serif", "Times New Roman");
        fontMap.put("Monospaced", "Courier New");

        ASPptxExporter exporter = new ASPptxExporter();
        exporter.setParameter(JRExporterParameter.JASPER_PRINT, jasperPrint);
        exporter.setParameter(JRExporterParameter.OUTPUT_FILE_NAME, "QuarterlySales.pptx");
        exporter.setParameter(ASExporterParameters.PPT_FONT_MAP, fontMap);
        exporter.setParameter(ASExporterParameters.PPT_EMBED_FONTS, "OnlyUsed");
        exporter.exportReport();
    }
}
```

```
import com.aspose.slides.jasperreports.ASExporterParameters;
import com.aspose.slides.jasperreports.ASPptxExporter;
import com.aspose.slides.jasperreports.License;

import net.sf.jasperreports.engine.JRExporterParameter;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.util.JRLoader;

import java.io.FileInputStream;
import java.io.InputStream;

public class ApplyLicense {
    public static void main(String[] args) throws Exception {
        License license = new License();
        InputStream stream =
                new FileInputStream("Aspose.Slides.JasperReports.Developer.lic");
        try {
            license.setLicense(stream);
        } finally {
            stream.close();
        }
        System.out.println("Licensed: " + license.isLicensed());

        JasperPrint jasperPrint =
                (JasperPrint) JRLoader.loadObjectFromFile("QuarterlySales.jrprint");

        ASPptxExporter exporter = new ASPptxExporter();
        exporter.setParameter(JRExporterParameter.JASPER_PRINT, jasperPrint);
        exporter.setParameter(JRExporterParameter.OUTPUT_FILE_NAME, "QuarterlySales.pptx");

        // Equivalent to the License call above, scoped to this one export.
        exporter.setParameter(
                ASExporterParameters.PPT_LICENSE,
                "Aspose.Slides.JasperReports.Developer.lic");
        exporter.exportReport();
    }
}
```

{{< /blocks/products/pf/slides-task-tabs >}}

{{< blocks/products/pf/slides-formats title="What goes in, what comes out" >}}

{{< blocks/products/pf/slides-capability-table title="Capabilities, one line each" lede="Everything below is what this JAR adds to JasperReports. It runs against the filled report rather than the design, so the report you already have is exported unchanged, and none of it asks for Microsoft PowerPoint to be installed." >}}

{{< blocks/products/pf/slides-runtime-cards
  id="runtimes"
  title="Runs where your code already runs"
  lede="Where a build of this library is supported, and what each target is for."
  footText="This exporter has no presentation API of its own beyond the four exporter classes and their six parameters. If you need one, Aspose.Slides ships as a standalone library for Java, .NET, C++, Python, PHP, Node.js and Android."
  allText="All high-code APIs" allHref="/slides/family/"
  isGrey="true"
>}}

| Runtime | Note | Platforms |
|---|---|---|
| JasperReports Library | The embedded case. Your Java code fills or loads a report, hands the JasperPrint to ASPptxExporter and calls exportReport(). Only the library JAR is needed on the classpath. | LIBRARY JAR · JAVA |
| JasperReports Server | The deployed case. Both JARs go in jasperserver/WEB-INF/lib, ASPptReportExporter is registered in viewReportBeans.xml, and PowerPoint appears in the export menu beside PDF and Excel. No report is edited and no application code is written. | SERVER JAR · SPRING XML |
| Java SE | Anywhere a JVM already runs a report: a batch fill, a scheduled job, a servlet container. Pure Java from JDK 1.6 upward with no native components. Run it headless, with java.awt.headless=true and the fonts your reports call for installed. | JDK 1.6 AND LATER |
| Aspose.Total for JasperReports | The same exporter licensed alongside the Words, Cells, PDF, Imaging, BarCode and CAD exporters, so one report design can reach Office, PDF, image and CAD targets under one agreement. | SUITE |

{{< /blocks/products/pf/slides-runtime-cards >}}

{{< blocks/products/pf/slides-licensing-band
  title="Start with the trial, license when you ship"
  body="The trial is the full API. It applies an evaluation watermark when a presentation is opened or saved and caps text extraction at one slide, so you can test the formats you actually care about before you talk to anyone. A temporary licence lifts both for 30 days."
  ctaPrimaryText="Download" ctaPrimaryUrl="https://releases.aspose.com/slides/jasperreport/"
  ctaSecondaryText="Temporary license" ctaSecondaryUrl="https://purchase.aspose.com/temporary-license/"
>}}

{{< blocks/products/pf/slides-resource-columns
  barLeft="ASPOSE.SLIDES FOR JASPERREPORTS · PRODUCTS.ASPOSE.COM"
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

- [Documentation](https://docs.aspose.com/slides/jasperreports/)
- [API reference](https://reference.aspose.com/slides/jasperreports/)
- [Support forum](https://forum.aspose.com/c/slides/)
- [Installation](https://docs.aspose.com/slides/jasperreports/installation/)

## In use

The product worked as advertised, the documentation was easy to follow, and the support forums were all the help we needed. The final solution that we deployed has exceeded our initial expectations by a great deal.

— BRUCE BRIEN · STRATASCOPE INC, USA

{{< /blocks/products/pf/slides-resource-columns >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}
