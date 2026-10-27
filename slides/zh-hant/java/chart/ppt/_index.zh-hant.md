---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 5050
title: 使用 Java 將圖表新增至 PPT 簡報
url: /zh-hant/java/chart/ppt/ 
description: 在 Java 中將圖表新增至 PPT 簡報。使用 Aspose.Slides for Java 建立圖表數列、類別、資料標籤與格式設定。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 建立 PPT 圖表" h2="使用 Aspose.Slides for Java，無需 Microsoft PowerPoint 即可在簡報檔案中建立圖表並設定格式。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Java 在 PPT 檔案中建立圖表" %}}

使用 [Aspose.Slides for Java](/slides/zh-hant/java/) 在 PPT 簡報中建立圖表並設定格式。此 API 提供 `IChart`、`IChartDataWorkbook`、`IChartSeries` 與 `IDataLabel` 等圖表物件。新增下列存放庫與相依性，即可在以 Maven 為基礎的專案中安裝 `aspose-slides` 套件。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="存放庫" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="相依性" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="在 PPT 中建立圖表 – Java" >}}
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

    presentation.save("chart-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Java 在 PPT 檔案中建立圖表" intro="使用 Aspose.Slides for Java 在 PPT 檔案中建立圖表。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}建立 `Presentation` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}取得簡報中的第一個 `ISlide`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}新增含有預設資料的 `IChart` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}設定圖表標題與資料標籤選項。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}取得 `IChartDataWorkbook` 物件，並清除預設數列與類別。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}新增圖表數列與類別。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}填入數列資料並設定數列的填滿色彩。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}為圖表數列建立自訂資料標籤。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}儲存含有圖表的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統需求" intro="Aspose.Slides for Java 支援主要的桌面與伺服器平台。請確認您的專案符合這些先決條件。" %}}

-  具有受支援 Java 執行階段環境的 Microsoft Windows、Linux、macOS 或其他作業系統。
-  從 [Maven](https://releases.aspose.com/java/repo/) 取得最新版本的 Aspose.Slides for Java。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="以 Aspose.Slides 建置" title="線上建立 PPT 圖表" description="免費的 Aspose.Slides Chart 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Chart" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何建立圖表。
- 根據 Excel 或表格資料建立圖表。
- 將其下載為 PPT 檔案或影像。
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

PPT 檔案是 Microsoft PowerPoint 97-2003 簡報檔案。它以 Open XML PPTX 格式之前使用的二進位 PowerPoint 檔案格式儲存投影片、文字、影像、多媒體、圖表與內嵌物件。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="圖表支援的其他格式" subTitle="使用 Java，您也可以在其他格式中建立圖表。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/chart/pptx/" name="PPTX" description="Open XML 簡報格式" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
