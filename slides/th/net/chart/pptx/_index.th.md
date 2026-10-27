---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7100
title: สร้างแผนภูมิ PPTX ด้วย .NET
url: /th/net/chart/pptx/ 
description: สร้างแผนภูมิในงานนำเสนอ PPTX ด้วย C# โดยใช้ Aspose.Slides for .NET
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="สร้างแผนภูมิ PPTX ใน C#" h2="สร้างแอปพลิเคชัน .NET ที่สร้างแผนภูมิในไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์ของ Aspose.Slides"
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="สร้างแผนภูมิ PPTX ด้วย C#" %}}

ใช้ [Aspose.Slides for .NET](/slides/th/net/) เพื่อสร้างแผนภูมิในงานนำเสนอ PPTX ติดตั้งแพ็กเกจจาก [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) หรือใช้คำสั่งต่อไปนี้ใน Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คำสั่ง" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="สร้างแผนภูมิใน PPTX – C#" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีสร้างแผนภูมิในไฟล์ PPTX ด้วย C#" intro="สร้างแผนภูมิในงานนำเสนอ PPTX ด้วย Aspose.Slides for .NET ด้วยโค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างออบเจ็กต์ `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}รับสไลด์เป้าหมายจาก `presentation.Slides`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `AddChart` เพื่อเพิ่มแผนภูมิลงในสไลด์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มชุดข้อมูลและจุดข้อมูลของแผนภูมิด้วย `IChartDataWorkbook`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอเป็นไฟล์ PPTX{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides for .NET รองรับแพลตฟอร์มและระบบปฏิบัติการหลัก ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของคุณเป็นไปตามข้อกำหนดเบื้องต้นต่อไปนี้" %}}

- ระบบปฏิบัติการที่รองรับซึ่งติดตั้ง .NET หรือ Mono
- สภาพแวดล้อมการพัฒนา เช่น Microsoft Visual Studio
- Aspose.Slides for .NET ที่อ้างอิงในโปรเจกต์ของคุณ ติดตั้งจาก NuGet หรือดาวน์โหลดด้วยปุ่มดาวน์โหลดด้านบน

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="สร้างด้วย Aspose.Slides" title="สร้างแผนภูมิ PPTX ออนไลน์" description="แอป Aspose.Slides Chart ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Chart" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides สร้างแผนภูมิอย่างไรก่อนเขียนโค้ด
- สร้างแผนภูมิจากข้อมูล Excel หรือข้อมูลในตาราง
- ดาวน์โหลดเป็นไฟล์ PPTX หรือรูปภาพ
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

ไฟล์ที่มีนามสกุล PPTX ใช้รูปแบบงานนำเสนอ Office Open XML ไฟล์ PPTX สามารถมีสไลด์ที่มีข้อความ แผนภูมิ รูปภาพ การจัดรูปแบบ ภาพเคลื่อนไหว และเนื้อหางานนำเสนออื่นๆ

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับแผนภูมิ" subTitle="ด้วย C# คุณยังสร้างแผนภูมิในรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/chart/ppt/" name="PPT" description="งานนำเสนอ PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
