---
title: Gráfico de documentos PPTX a través de .NET
weight: 7100
url: /es/net/chart/pptx/ 
description: Código fuente C# para dibujar y convertir gráficos o diagramas en archivos PPTX en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Gráficos de formato PPTX en C#" h2="Gráficos de documentos PPTX nativos y de alto rendimiento que utilizan Aspose.Slides del lado del servidor para las API de .NET, sin el uso de ningún software como Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo crear gráficos PPTX usando C#" %}}

 Para crear gráficos PPTX, usaremos
 [Aspose.Slides para .NET](https://products.aspose.com/slides/es/net)
 API, que es una API de manipulación de documentos rica en funciones, potente y fácil de usar para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 administrador de paquetes, busque
 **Aspose.Diapositivas**
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Dominio" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Pasos para crear gráficos de archivos PPTX en C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Se puede hacer un gráfico básico de documentos con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net) API con solo unas pocas líneas de código." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crear objeto de clase de presentación.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Seleccione Diapositiva.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregar gráfico a la diapositiva.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue series de gráficos relevantes con datos.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar archivo PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nuestras API son compatibles con todas las principales plataformas y sistemas operativos. Antes de ejecutar el código a continuación, asegúrese de tener los siguientes requisitos previos en su sistema.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin
- Entorno de desarrollo como Microsoft Visual Studio
- Aspose.Slides para .NET DLL a la que se hace referencia en su proyecto - Instale desde NuGet usando el botón Descargar arriba

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Crear gráfico de archivos PPTX - C#" offSpacer="" %}}

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

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.Slides para la API de .NET" %}}

 Aspose.Slides API se puede utilizar para leer, escribir, manipular y convertir documentos de Microsoft PowerPoint a PDF, XPS, HTML, TIFF, ODP y varios otros formatos. Uno puede crear nuevos archivos desde cero y guardarlos en los formatos compatibles relevantes. Aspose.Slides es una API independiente para crear, analizar o manipular presentaciones, diapositivas y elementos y no depende de ningún software como Microsoft u OpenOffice. Genere un gráfico PPT (X), un diagrama PPT (X) a partir de datos de Excel, según la plantilla del gráfico. 
 



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

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de gráficos admitidos" subTitle="Usando C#, uno puede manejar fácilmente los gráficos con diferentes formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/chart/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}