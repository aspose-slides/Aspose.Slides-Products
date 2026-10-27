---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7490
title: C++ का उपयोग करके PPT चार्ट बनाएँ
url: /hi/cpp/chart/ppt/ 
description: Windows और Linux पर PPT प्रेज़ेंटेशन में चार्ट बनाने के लिए C++ उदाहरण कोड।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ का उपयोग करके PPT प्रेज़ेंटेशन में चार्ट बनाएँ" h2="Microsoft PowerPoint के बिना सर्वर-साइड Aspose.Slides for C++ API के ज़रिए PPT प्रेज़ेंटेशन चार्ट बनाएँ।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ का उपयोग करके PPT चार्ट बनाएँ" %}}

PPT प्रेज़ेंटेशन में चार्ट बनाने के लिए [Aspose.Slides for C++](/slides/hi/cpp/) का उपयोग करें। [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) से पैकेज इंस्टॉल करें या Package Manager Console में निम्न कमांड चलाएँ।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कमांड" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT में चार्ट बनाएँ – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

// Add a chart with default data.
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0, 0, 500, 500);

// Set the index of the chart data sheet.
int defaultWorksheetIndex = 0;

// Get the chart data workbook.
auto chartDataWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();

// Set the chart title.
chart->get_ChartTitle()->AddTextFrameForOverriding(u"Sample Title");
chart->get_ChartTitle()->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chart->get_ChartTitle()->set_Height(20);
chart->set_HasTitle(true);

// Delete the default generated series and categories.
chart->get_ChartData()->get_Series()->Clear();
chart->get_ChartData()->get_Categories()->Clear();

// Add series.
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 1, ObjectExt::Box(String(u"Series 1"))), chart->get_Type());
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 2, ObjectExt::Box(String(u"Series 2"))), chart->get_Type());

// Add categories.
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 0, ObjectExt::Box(String(u"Category 1"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 0, ObjectExt::Box(String(u"Category 2"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 0, ObjectExt::Box(String(u"Category 3"))));

// Take the first chart series.
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 1, ObjectExt::Box(20)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 1, ObjectExt::Box(50)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 1, ObjectExt::Box(30)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Blue());

// Take the second chart series.
series = chart->get_ChartData()->get_Series()->idx_get(1);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 2, ObjectExt::Box(30)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 2, ObjectExt::Box(10)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 2, ObjectExt::Box(60)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Orange());

// Show the category name for the first label.
auto dataLabel = series->get_DataPoints()->idx_get(0)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowCategoryName(true);

dataLabel = series->get_DataPoints()->idx_get(1)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);

// Show the value for the third label.
dataLabel = series->get_DataPoints()->idx_get(2)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowValue(true);
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);
dataLabel->get_DataLabelFormat()->set_Separator(u"/");

// Save the PPT file.
presentation->Save(u"column_chart.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ का उपयोग करके PPT फ़ाइलों में चार्ट कैसे बनाएँ" intro="Aspose.Slides for C++ के साथ कुछ ही पंक्तियों के कोड में PPT प्रेज़ेंटेशन में चार्ट बनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एक `Presentation` ऑब्जेक्ट बनाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पहली स्लाइड तक पहुँचें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}डिफ़ॉल्ट डेटा के साथ एक चार्ट जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}चार्ट डेटा शीट का इंडेक्स सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}चार्ट डेटा वर्कबुक प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}चार्ट का शीर्षक सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}डिफ़ॉल्ट रूप से बनी सीरीज़ और श्रेणियाँ हटाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सीरीज़ और श्रेणियाँ जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पहली चार्ट सीरीज़ लें और उसका डेटा भरें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सीरीज़ का फ़िल रंग सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}दूसरी सीरीज़ के डेटा लेबल में श्रेणी का नाम, सीरीज़ का नाम और मान दिखाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएँ" intro="Aspose.Slides for C++ प्रमुख प्लेटफ़ॉर्म और ऑपरेटिंग सिस्टम का समर्थन करता है। सुनिश्चित करें कि आपका परिवेश निम्नलिखित पूर्वापेक्षाएँ पूरी करता है।" %}}

-  समर्थित C++ रनटाइम वाला Microsoft Windows, Linux, macOS या कोई अन्य संगत OS।
-  आपके प्रोजेक्ट में संदर्भित Aspose.Slides for C++ लाइब्रेरी।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides से निर्मित" title="PPT चार्ट ऑनलाइन बनाएँ" description="मुफ़्त Aspose.Slides Chart ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Chart खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides चार्ट कैसे बनाता है।
- Excel या टेबल डेटा से चार्ट बनाएँ।
- इसे PPT फ़ाइल या इमेज के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

PPT फ़ाइल में स्लाइड शो के लिए स्लाइड का संग्रह होता है। यह Microsoft PowerPoint 97-2003 के बाइनरी फ़ाइल फ़ॉर्मेट का उपयोग करती है। PPT फ़ाइल में टेक्स्ट, बुलेट पॉइंट, इमेज, मल्टीमीडिया और अन्य एम्बेड किए गए OLE ऑब्जेक्ट हो सकते हैं। Microsoft ने PowerPoint 2007 में नया PPTX फ़ॉर्मेट पेश किया। PPTX, Office Open XML पर आधारित है और पुराने बाइनरी फ़ॉर्मेट से अलग है। OpenOffice Impress और Apple Keynote जैसे अन्य ऐप भी PPT फ़ाइलें बना सकते हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="चार्ट के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="C++ के साथ, आप अन्य फ़ॉर्मेट में भी चार्ट बना सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/chart/pptx/" name="PPTX" description="Open XML प्रेज़ेंटेशन फ़ॉर्मेट" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
