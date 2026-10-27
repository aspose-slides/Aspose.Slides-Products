---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 160
title: เพิ่มแผนภูมิลงในงานนำเสนอ PPTX ด้วย Java
url: /th/java/chart/pptx/ 
description: เพิ่มแผนภูมิลงในงานนำเสนอ PPTX ใน Java ใช้ Aspose.Slides for Java เพื่อสร้างชุดข้อมูล หมวดหมู่ ป้ายชื่อข้อมูล และการจัดรูปแบบของแผนภูมิ
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="สร้างแผนภูมิ PPTX ใน Java" h2="ใช้ Aspose.Slides for Java เพื่อสร้างและจัดรูปแบบแผนภูมิในไฟล์งานนำเสนอโดยไม่ต้องใช้ Microsoft PowerPoint"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="สร้างแผนภูมิในไฟล์ PPTX ด้วย Java" %}}

ใช้ [Aspose.Slides for Java](/slides/th/java/) เพื่อสร้างและจัดรูปแบบแผนภูมิในงานนำเสนอ PPTX API มีออบเจ็กต์แผนภูมิ เช่น `IChart`, `IChartDataWorkbook`, `IChartSeries` และ `IDataLabel` คุณสามารถติดตั้งแพ็กเกจ `aspose-slides` ในโปรเจกต์ที่ใช้ Maven ได้โดยเพิ่มที่เก็บและการขึ้นต่อกันด้านล่าง

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ที่เก็บ" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="การขึ้นต่อกัน" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="สร้างแผนภูมิใน PPTX – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);

    chart.getChartTitle().addTextFrameForOverriding("Sales by quarter");
    chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
    chart.getChartTitle().setHeight(20);
    chart.setTitle(true);

    chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);

    int defaultWorksheetIndex = 0;
    IChartDataWorkbook chartDataWorkbook = chart.getChartData().getChartDataWorkbook();

    chart.getChartData().getSeries().clear();
    chart.getChartData().getCategories().clear();

    chart.getChartData().getSeries().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
    chart.getChartData().getSeries().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());

    chart.getChartData().getCategories().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 1, 0, "Category 1"));
    chart.getChartData().getCategories().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 2, 0, "Category 2"));
    chart.getChartData().getCategories().add(chartDataWorkbook.getCell(defaultWorksheetIndex, 3, 0, "Category 3"));

    IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
    firstSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 1, 1, 20));
    firstSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 2, 1, 50));
    firstSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 3, 1, 30));
    firstSeries.getFormat().getFill().setFillType(FillType.Solid);
    firstSeries.getFormat().getFill().getSolidFillColor().setColor(java.awt.Color.RED);

    IChartSeries secondSeries = chart.getChartData().getSeries().get_Item(1);
    secondSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 1, 2, 30));
    secondSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 2, 2, 10));
    secondSeries.getDataPoints().addDataPointForBarSeries(chartDataWorkbook.getCell(defaultWorksheetIndex, 3, 2, 60));
    secondSeries.getFormat().getFill().setFillType(FillType.Solid);
    secondSeries.getFormat().getFill().getSolidFillColor().setColor(java.awt.Color.GREEN);

    IDataLabel firstDataLabel = secondSeries.getDataPoints().get_Item(0).getLabel();
    firstDataLabel.getDataLabelFormat().setShowCategoryName(true);

    IDataLabel secondDataLabel = secondSeries.getDataPoints().get_Item(1).getLabel();
    secondDataLabel.getDataLabelFormat().setShowSeriesName(true);

    IDataLabel thirdDataLabel = secondSeries.getDataPoints().get_Item(2).getLabel();
    thirdDataLabel.getDataLabelFormat().setShowValue(true);
    thirdDataLabel.getDataLabelFormat().setShowSeriesName(true);
    thirdDataLabel.getDataLabelFormat().setSeparator("/");

    presentation.save("chart-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีสร้างแผนภูมิในไฟล์ PPTX ใน Java" intro="สร้างแผนภูมิในไฟล์ PPTX ด้วย Aspose.Slides for Java" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างออบเจ็กต์ `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}รับ `ISlide` แรกจากงานนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มออบเจ็กต์ `IChart` พร้อมข้อมูลเริ่มต้น{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ตั้งชื่อแผนภูมิและตัวเลือกป้ายชื่อข้อมูล{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}รับออบเจ็กต์ `IChartDataWorkbook` แล้วล้างชุดข้อมูลและหมวดหมู่เริ่มต้น{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มชุดข้อมูลและหมวดหมู่ใหม่ของแผนภูมิ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เติมข้อมูลของชุดข้อมูลและตั้งค่าสีเติมของชุดข้อมูล{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างป้ายชื่อข้อมูลแบบกำหนดเองสำหรับชุดข้อมูลของแผนภูมิ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอพร้อมแผนภูมิ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides for Java รองรับแพลตฟอร์มเดสก์ท็อปและเซิร์ฟเวอร์หลัก ตรวจสอบให้แน่ใจว่าโปรเจกต์ของคุณเป็นไปตามข้อกำหนดเบื้องต้นเหล่านี้" %}}

-  Microsoft Windows, Linux, macOS หรือระบบปฏิบัติการอื่นที่มี Java Runtime Environment ที่รองรับ
-  รับ Aspose.Slides for Java เวอร์ชันล่าสุดจาก [Maven](https://releases.aspose.com/java/repo/)

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="สร้างด้วย Aspose.Slides" title="สร้างแผนภูมิ PPTX ออนไลน์" description="แอป Aspose.Slides Chart ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Chart" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides สร้างแผนภูมิอย่างไรก่อนเขียนโค้ด
- สร้างแผนภูมิจากข้อมูล Excel หรือข้อมูลในตาราง
- ดาวน์โหลดเป็นไฟล์ PPTX หรือรูปภาพ
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

ไฟล์ PPTX คือไฟล์งานนำเสนอ Microsoft PowerPoint ในรูปแบบ Open XML ซึ่งจัดเก็บสไลด์ ข้อความ รูปภาพ แผนภูมิ การจัดรูปแบบ ภาพเคลื่อนไหว และเนื้อหางานนำเสนออื่นๆ ไว้ในแพ็กเกจที่บีบอัดซึ่งใช้ XML

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับแผนภูมิ" subTitle="ด้วย Java คุณยังสร้างแผนภูมิในรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/chart/ppt/" name="PPT" description="งานนำเสนอ PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
