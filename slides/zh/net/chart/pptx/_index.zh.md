---
title: 通过 .NET 的 PPTX 文档图表
weight: 7100
url: /zh/net/chart/pptx/ 
description: C# 源代码，用于在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上绘制和转换 PPTX 文件中的图表或图表。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPTX 在 C# 中格式化图表" h2="使用用于 .NET API 的服务器端 Aspose.Slides 的原生和高性能 PPTX 文档图表，无需使用 Microsoft 或 Adob​​e PDF 等任何软件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 创建 PPTX 图表" %}}

 为了创建 PPTX 图表，我们将使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net)
 API 是一个功能丰富、功能强大且易于使用的 C# 平台文档操作 API。打开
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 **Aspose.Slides**
 并安装。您还可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="在 C# 中创建 PPTX 文件图表的步骤" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="只需几行代码即可使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net) API 绘制基本文档图表。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建 Presentation 类对象。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
选择幻灯片。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将图表添加到幻灯片。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加带有数据的相关图表系列。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存 PPTX 文件
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要平台和操作系统都支持我们的 API。在执行以下代码之前，请确保您的系统具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或兼容 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台的操作系统
- Microsoft Visual Studio 等开发环境
- 项目中引用的 .NET DLL 的 Aspose.Slides - 使用上面的下载按钮从 NuGet 安装

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="创建 PPTX 文件图表 - C#" offSpacer="" %}}

```cs
//Creating Charts in a Presentation
    Presentation pres = new Presentation();
    
    ISlide slide = pres.Slides[0];
    
    //Creating the default chart
    IChart chart = slide.Shapes.AddChart(ChartType.ScatterWithSmoothLines, 0, 0, 400, 400);
    
    //Getting the default chart data worksheet index
    int defaultWorksheetIndex = 0;
    
    //Accessing the chart data worksheet
    IChartDataCellFactory fact = chart.ChartData.ChartDataCellFactory;
    
    //Delete demo series
    chart.ChartData.Series.Clear();
    
    //Add new series
    chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 1, 1, "Series 1"), chart.Type);
    chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 1, 3, "Series 2"), chart.Type);
    
    //Take first chart series
    IChartSeries series = chart.ChartData.Series[0];
    
    //Add new point (1:3) there.
    series.DataPoints.AddDataPointForScatterSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 1), fact.GetCell(defaultWorksheetIndex, 2, 2, 3));
    
    //Add new point (2:10)
    series.DataPoints.AddDataPointForScatterSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 2), fact.GetCell(defaultWorksheetIndex, 3, 2, 10));
    
    //Edit the type of series
    series.Type = ChartType.ScatterWithStraightLinesAndMarkers;
    
    //Changing the chart series marker
    series.Marker.Size = 10;
    series.Marker.Symbol = MarkerStyleType.Star;
    
    //Take second chart series
    series = chart.ChartData.Series[1];
    
    //Add new point (5:2) there.
    series.DataPoints.AddDataPointForScatterSeries(fact.GetCell(defaultWorksheetIndex, 2, 3, 5), fact.GetCell(defaultWorksheetIndex, 2, 4, 2));
    
    //Add new point (3:1)
    series.DataPoints.AddDataPointForScatterSeries(fact.GetCell(defaultWorksheetIndex, 3, 3, 3), fact.GetCell(defaultWorksheetIndex, 3, 4, 1));
    
    //Add new point (2:2)
    series.DataPoints.AddDataPointForScatterSeries(fact.GetCell(defaultWorksheetIndex, 4, 3, 2), fact.GetCell(defaultWorksheetIndex, 4, 4, 2));
    
    //Add new point (5:1)
    series.DataPoints.AddDataPointForScatterSeries(fact.GetCell(defaultWorksheetIndex, 5, 3, 5), fact.GetCell(defaultWorksheetIndex, 5, 4, 1));
    
    //Changing the chart series marker
    series.Marker.Size = 10;
    series.Marker.Symbol = MarkerStyleType.Circle;
    
    pres.Save("AsposeScatterChart.pptx", SaveFormat.Pptx);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于 Aspose.Slides for .NET API" %}}

 Aspose.Slides API 可用于读取、编写、操作 Microsoft PowerPoint 文档并将其转换为 PDF、XPS、HTML、TIFF、ODP 和各种其他格式。可以从头开始创建新文件并将其保存为相关支持的格式。 Aspose.Slides 是一个独立的 API，用于创建、解析或操作演示文稿、幻灯片和元素，它不依赖于 Microsoft 或 OpenOffice 等任何软件。基于图表模板，从excel数据生成PPT(X)图表、PPT(X)图。 
 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Chart Creation Live Demos" sectionDescription="Generate PPTX documents charts right now by visiting our [Live Demos website](https://products.aspose.app/slides/chart). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Chart will be created instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的图表格式" subTitle="使用 C#，可以轻松处理不同格式的图表，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/net/chart/ppt/" name="PPT" description="微软PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}