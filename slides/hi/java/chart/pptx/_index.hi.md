---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 160
title: Java का उपयोग करके PPTX प्रेज़ेंटेशन में चार्ट जोड़ें
url: /hi/java/chart/pptx/ 
description: Java में PPTX प्रेज़ेंटेशन में चार्ट जोड़ें। चार्ट सीरीज़, श्रेणियाँ, डेटा लेबल और फ़ॉर्मेटिंग बनाने के लिए Aspose.Slides for Java का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java में PPTX चार्ट बनाएँ" h2="Microsoft PowerPoint के बिना प्रेज़ेंटेशन फ़ाइलों में चार्ट बनाने और फ़ॉर्मेट करने के लिए Aspose.Slides for Java का उपयोग करें।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java का उपयोग करके PPTX फ़ाइलों में चार्ट बनाएँ" %}}

PPTX प्रेज़ेंटेशन में चार्ट बनाने और फ़ॉर्मेट करने के लिए [Aspose.Slides for Java](/slides/hi/java/) का उपयोग करें। API `IChart`, `IChartDataWorkbook`, `IChartSeries` और `IDataLabel` जैसे चार्ट ऑब्जेक्ट देता है। नीचे दी गई रिपॉज़िटरी और डिपेंडेंसी जोड़कर आप Maven-आधारित प्रोजेक्ट में `aspose-slides` पैकेज इंस्टॉल कर सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="रिपॉज़िटरी" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="डिपेंडेंसी" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX में चार्ट बनाएँ – Java" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java में PPTX फ़ाइलों में चार्ट कैसे बनाएँ" intro="Aspose.Slides for Java के साथ PPTX फ़ाइलों में चार्ट बनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एक `Presentation` ऑब्जेक्ट बनाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेज़ेंटेशन से पहली `ISlide` प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}डिफ़ॉल्ट डेटा के साथ एक `IChart` ऑब्जेक्ट जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}चार्ट का शीर्षक और डेटा लेबल विकल्प सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`IChartDataWorkbook` ऑब्जेक्ट प्राप्त करें और डिफ़ॉल्ट सीरीज़ और श्रेणियाँ साफ़ करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}नई चार्ट सीरीज़ और श्रेणियाँ जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सीरीज़ का डेटा भरें और सीरीज़ के फ़िल रंग सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}चार्ट सीरीज़ के लिए कस्टम डेटा लेबल बनाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}चार्ट के साथ प्रेज़ेंटेशन सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएँ" intro="Aspose.Slides for Java प्रमुख डेस्कटॉप और सर्वर प्लेटफ़ॉर्म का समर्थन करता है। सुनिश्चित करें कि आपका प्रोजेक्ट ये पूर्वापेक्षाएँ पूरी करता है।" %}}

-  समर्थित Java Runtime Environment वाला Microsoft Windows, Linux, macOS या कोई अन्य OS।
-  Aspose.Slides for Java का नवीनतम संस्करण [Maven](https://releases.aspose.com/java/repo/) से प्राप्त करें।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides से निर्मित" title="PPTX चार्ट ऑनलाइन बनाएँ" description="मुफ़्त Aspose.Slides Chart ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Chart खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides चार्ट कैसे बनाता है।
- Excel या टेबल डेटा से चार्ट बनाएँ।
- इसे PPTX फ़ाइल या इमेज के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

PPTX फ़ाइल Open XML फ़ॉर्मेट वाली Microsoft PowerPoint प्रेज़ेंटेशन फ़ाइल है। यह स्लाइड, टेक्स्ट, इमेज, चार्ट, फ़ॉर्मेटिंग, एनिमेशन और अन्य प्रेज़ेंटेशन सामग्री को XML-आधारित ज़िप पैकेज में संग्रहीत करती है।

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="चार्ट के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="Java के साथ, आप अन्य फ़ॉर्मेट में भी चार्ट बना सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/chart/ppt/" name="PPT" description="PowerPoint 97-2003 प्रेज़ेंटेशन" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
