---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7050
title: ایجاد نمودارهای PPT با .NET
url: /fa/net/chart/ppt/ 
description: با Aspose.Slides for .NET در C# نمودارهایی در ارائه‌های PPT ایجاد کنید.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ایجاد نمودارهای PPT در C#" h2="برنامه‌های .NET بسازید که با APIهای سمت سرور Aspose.Slides در فایل‌های ارائه نمودار ایجاد می‌کنند."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ایجاد نمودارهای PPT با C#" %}}

از [Aspose.Slides for .NET](/slides/fa/net/) برای ایجاد نمودار در ارائه‌های PPT استفاده کنید. بسته را از [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) نصب کنید یا دستور زیر را در Package Manager Console اجرا کنید.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="دستور" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ایجاد نمودار در PPT – C#" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="چگونه با C# در فایل‌های PPT نمودار ایجاد کنیم" intro="با Aspose.Slides for .NET و تنها چند خط کد، در یک ارائه PPT نمودار ایجاد کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}یک شیء `Presentation` ایجاد کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}اسلاید هدف را از `presentation.Slides` بگیرید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}متد `AddChart` را فراخوانی کنید تا نموداری به اسلاید اضافه شود.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}سری‌ها و نقاط داده نمودار را با `IChartDataWorkbook` اضافه کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ارائه را به‌صورت فایل PPT ذخیره کنید.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="پیش‌نیازهای سیستم" intro="Aspose.Slides for .NET از پلتفرم‌ها و سیستم‌عامل‌های اصلی پشتیبانی می‌کند. مطمئن شوید محیط شما پیش‌نیازهای زیر را دارد." %}}

- یک سیستم‌عامل پشتیبانی‌شده با .NET یا Mono نصب‌شده.
- یک محیط توسعه مانند Microsoft Visual Studio.
- ارجاع به Aspose.Slides for .NET در پروژه شما. آن را از NuGet نصب کنید یا با دکمه دانلود در بالا دریافت کنید.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="ساخته شده با Aspose.Slides" title="ایجاد آنلاین نمودارهای PPT" description="برنامه رایگان Aspose.Slides Chart با [Aspose.Slides for .NET](https://products.aspose.com/slides/fa/net/) ساخته شده است، همان API که در کد بالا استفاده شده است. آن را باز کنید و ببینید API با فایل‌های PPT شما چه کارهایی می‌تواند انجام دهد." button="باز کردن Aspose.Slides Chart" note="[همه برنامه‌های رایگان](https://products.aspose.app/slides/family)" >}}
- در مرورگر شما اجرا می‌شود، بدون نیاز به نصب.
- پیش از نوشتن کد ببینید Aspose.Slides چگونه نمودار ایجاد می‌کند.
- از داده‌های Excel یا جدول نمودار بسازید.
- آن را به‌صورت فایل PPT یا تصویر دانلود کنید.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

یک فایل PPT ارائه PowerPoint 97-2003 را در قالب فایل دودویی ذخیره می‌کند. این فایل می‌تواند اسلایدهایی با متن، نمودار، تصویر، چندرسانه‌ای و اشیای جاسازی‌شده داشته باشد.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="سایر قالب‌های پشتیبانی‌شده برای نمودار" subTitle="با C# می‌توانید در قالب‌های دیگر نیز نمودار ایجاد کنید." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fa/net/chart/pptx/" name="PPTX" description="قالب ارائه Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
