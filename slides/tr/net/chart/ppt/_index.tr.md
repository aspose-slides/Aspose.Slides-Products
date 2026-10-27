---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7050
title: .NET ile PPT grafikleri oluşturma
url: /tr/net/chart/ppt/ 
description: Aspose.Slides for .NET ile C# kullanarak PPT sunumlarında grafikler oluşturun.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile PPT grafikleri oluşturma" h2="Sunucu tarafı Aspose.Slides API'leriyle sunum dosyalarında grafik oluşturan .NET uygulamaları geliştirin."
  apiHomeLink="/slides/net/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/net/"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# kullanarak PPT grafikleri oluşturma" %}}

PPT sunumlarında grafik oluşturmak için [Aspose.Slides for .NET](/slides/tr/net/) kullanın. Paketi [NuGet](https://www.nuget.org/packages/Aspose.Slides.NET/) üzerinden yükleyin veya Paket Yöneticisi Konsolu'nda aşağıdaki komutu kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Komut" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT dosyasında grafik oluşturma – C#" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile PPT dosyalarında grafikler nasıl oluşturulur" intro="Aspose.Slides for .NET ile birkaç satır kodla bir PPT sunumunda grafik oluşturun." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Bir `Presentation` nesnesi oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hedef slaytı `presentation.Slides` içinden alın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Slayta grafik eklemek için `AddChart` yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`IChartDataWorkbook` ile grafik serileri ve veri noktaları ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunumu PPT dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Sistem gereksinimleri" intro="Aspose.Slides for .NET başlıca platformları ve işletim sistemlerini destekler. Ortamınızın aşağıdaki ön koşulları karşıladığından emin olun." %}}

- .NET veya Mono yüklü, desteklenen bir işletim sistemi.
- Microsoft Visual Studio gibi bir geliştirme ortamı.
- Projenizde başvurulan Aspose.Slides for .NET. NuGet üzerinden yükleyin veya yukarıdaki İndir düğmesiyle indirin.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Aspose.Slides ile geliştirildi" title="PPT grafiklerini çevrimiçi oluşturma" description="Ücretsiz Aspose.Slides Chart uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Chart uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın grafikleri nasıl oluşturduğunu görün.
- Excel veya tablo verilerinden grafik oluşturun.
- Sonucu PPT dosyası ya da resim olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Bir PPT dosyası, PowerPoint 97-2003 sunusunu ikili dosya biçiminde saklar. Metin, grafik, resim, multimedya ve katıştırılmış nesneler içeren slaytlar barındırabilir.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Grafikler için desteklenen diğer biçimler" subTitle="C# ile diğer biçimlerde de grafik oluşturabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/chart/pptx/" name="PPTX" description="Open XML sunu biçimi" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
