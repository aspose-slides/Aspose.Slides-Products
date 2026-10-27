---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7050
title: .NET का उपयोग करके PPT चार्ट बनाएँ
url: /hi/net/chart/ppt/ 
description: Aspose.Slides for .NET के साथ C# में PPT प्रेज़ेंटेशन में चार्ट बनाएँ।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# में PPT चार्ट बनाएँ" h2="ऐसे .NET एप्लिकेशन बनाएँ जो सर्वर-साइड Aspose.Slides API के ज़रिए प्रेज़ेंटेशन फ़ाइलों में चार्ट बनाएँ।"
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके PPT चार्ट बनाएँ" %}}

PPT प्रेज़ेंटेशन में चार्ट बनाने के लिए [Aspose.Slides for .NET](/slides/hi/net/) का उपयोग करें। [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) से पैकेज इंस्टॉल करें या Package Manager Console में निम्न कमांड चलाएँ।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कमांड" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT में चार्ट बनाएँ – C#" >}}
```cs
using var presentation = new Presentation();

var slide = presentation.Slides[0];
var chart = slide.Shapes.AddChart(ChartType.ScatterWithSmoothLines, 0, 0, 400, 400);
var defaultWorksheetIndex = 0;
var chartDataWorkbook = chart.ChartData.ChartDataWorkbook;

chart.ChartData.Series.Clear();
chart.ChartData.Series.Add(chartDataWorkbook.GetCell(defaultWorksheetIndex, 1, 1, "Series 1"), chart.Type);
chart.ChartData.Series.Add(chartDataWorkbook.GetCell(defaultWorksheetIndex, 1, 3, "Series 2"), chart.Type);

var firstSeries = chart.ChartData.Series[0];
firstSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 1, 1),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 2, 3));
firstSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 1, 2),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 2, 10));
firstSeries.Type = ChartType.ScatterWithStraightLinesAndMarkers;
firstSeries.Marker.Size = 10;
firstSeries.Marker.Symbol = MarkerStyleType.Star;

var secondSeries = chart.ChartData.Series[1];
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 3, 5),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 2, 4, 2));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 3, 3),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 3, 4, 1));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 4, 3, 2),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 4, 4, 2));
secondSeries.DataPoints.AddDataPointForScatterSeries(
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 5, 3, 5),
    chartDataWorkbook.GetCell(defaultWorksheetIndex, 5, 4, 1));
secondSeries.Marker.Size = 10;
secondSeries.Marker.Symbol = MarkerStyleType.Circle;

presentation.Save("AsposeScatterChart.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# का उपयोग करके PPT फ़ाइलों में चार्ट कैसे बनाएँ" intro="Aspose.Slides for .NET के साथ कुछ ही पंक्तियों के कोड में PPT प्रेज़ेंटेशन में चार्ट बनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एक `Presentation` ऑब्जेक्ट बनाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`presentation.Slides` से लक्ष्य स्लाइड प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}स्लाइड में चार्ट जोड़ने के लिए `AddChart` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`IChartDataWorkbook` के साथ चार्ट सीरीज़ और डेटा पॉइंट जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेज़ेंटेशन को PPT फ़ाइल के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएँ" intro="Aspose.Slides for .NET प्रमुख प्लेटफ़ॉर्म और ऑपरेटिंग सिस्टम का समर्थन करता है। सुनिश्चित करें कि आपका परिवेश निम्नलिखित पूर्वापेक्षाएँ पूरी करता है।" %}}

- .NET या Mono इंस्टॉल वाला कोई समर्थित ऑपरेटिंग सिस्टम।
- Microsoft Visual Studio जैसा कोई डेवलपमेंट परिवेश।
- आपके प्रोजेक्ट में संदर्भित Aspose.Slides for .NET। इसे NuGet से इंस्टॉल करें या ऊपर दिए गए डाउनलोड बटन से डाउनलोड करें।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides से निर्मित" title="PPT चार्ट ऑनलाइन बनाएँ" description="मुफ़्त Aspose.Slides Chart ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Chart खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides चार्ट कैसे बनाता है।
- Excel या टेबल डेटा से चार्ट बनाएँ।
- इसे PPT फ़ाइल या इमेज के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

PPT फ़ाइल PowerPoint 97-2003 प्रेज़ेंटेशन को बाइनरी फ़ाइल फ़ॉर्मेट में संग्रहीत करती है। इसमें टेक्स्ट, चार्ट, इमेज, मल्टीमीडिया और एम्बेड किए गए ऑब्जेक्ट वाली स्लाइड हो सकती हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="चार्ट के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="C# के साथ, आप अन्य फ़ॉर्मेट में भी चार्ट बना सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/chart/pptx/" name="PPTX" description="Open XML प्रेज़ेंटेशन फ़ॉर्मेट" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
