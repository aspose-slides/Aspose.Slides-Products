---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7100
title: إنشاء مخططات PPTX باستخدام .NET
url: /ar/net/chart/pptx/ 
description: أنشئ مخططات في عروض PPTX التقديمية بلغة C# باستخدام Aspose.Slides for .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="إنشاء مخططات PPTX بلغة C#" h2="أنشئ تطبيقات .NET تضيف مخططات إلى ملفات العروض التقديمية باستخدام واجهات Aspose.Slides API من جانب الخادم."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="إنشاء مخططات PPTX باستخدام C#" %}}

استخدم [Aspose.Slides for .NET](/slides/ar/net/) لإنشاء مخططات في عروض PPTX التقديمية. ثبّت الحزمة من [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) أو استخدم الأمر التالي في وحدة تحكم مدير الحزم.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="الأمر" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="إنشاء مخطط في PPTX – C#" >}}
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

presentation.Save("AsposeScatterChart.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية إنشاء مخططات في ملفات PPTX باستخدام C#" intro="أنشئ مخططًا في عرض تقديمي بتنسيق PPTX باستخدام Aspose.Slides for .NET ببضعة أسطر من التعليمات البرمجية." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أنشئ كائن `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احصل على الشريحة المطلوبة من `presentation.Slides`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}استدعِ الأسلوب `AddChart` لإضافة مخطط إلى الشريحة.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف سلاسل المخطط ونقاط البيانات باستخدام `IChartDataWorkbook`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}احفظ العرض التقديمي كملف PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="متطلبات النظام" intro="يدعم Aspose.Slides for .NET المنصات وأنظمة التشغيل الرئيسية. تأكد من أن بيئتك تستوفي المتطلبات الأساسية التالية." %}}

- نظام تشغيل مدعوم مثبت عليه .NET أو Mono.
- بيئة تطوير مثل Microsoft Visual Studio.
- مرجع إلى Aspose.Slides for .NET في مشروعك. ثبّته من NuGet أو نزّله باستخدام زر التنزيل أعلاه.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="مبني باستخدام Aspose.Slides" title="إنشاء مخططات PPTX عبر الإنترنت" description="تطبيق Aspose.Slides Chart المجاني مبني باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/ar/net/)، وهي نفس واجهة برمجة التطبيقات المستخدمة في الكود أعلاه. افتحه واكتشف ما يمكن لواجهة برمجة التطبيقات فعله بملفات PPTX الخاصة بك." button="افتح Aspose.Slides Chart" note="[جميع التطبيقات المجانية](https://products.aspose.app/slides/family)" >}}
- يعمل في متصفحك، دون الحاجة إلى تثبيت أي شيء.
- شاهد كيف ينشئ Aspose.Slides المخططات قبل أن تكتب الشيفرة.
- أنشئ مخططًا من بيانات Excel أو من جدول.
- نزّله كملف PPTX أو كصورة.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

تستخدم الملفات ذات الامتداد PPTX تنسيق العروض التقديمية Office Open XML. يمكن أن يحتوي ملف PPTX على شرائح تتضمن نصوصًا ومخططات وصورًا وتنسيقًا ورسومًا متحركة ومحتوى عروض تقديمية آخر.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="تنسيقات أخرى مدعومة للمخططات" subTitle="باستخدام C#، يمكنك أيضًا إنشاء مخططات بتنسيقات أخرى." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ar/net/chart/ppt/" name="PPT" description="عرض تقديمي PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
