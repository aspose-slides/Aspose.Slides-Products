---
title: PPTX dokumentumdiagram .NET-en keresztül
weight: 7100
url: /hu/net/chart/pptx/ 
description: C#-forráskód diagramok vagy diagramok rajzolásához és konvertálásához PPTX-fájlba .NET-keretrendszer, .NET Core, Windows Azure, Mono vagy Xamarin platformokon.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPTX formátumú diagramok C#-ban" h2="Natív és nagy teljesítményű PPTX dokumentumdiagramok kiszolgálóoldali Aspose.Slides segítségével .NET API-khoz, olyan szoftverek használata nélkül, mint a Microsoft vagy az Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PPTX diagramok létrehozása C# használatával" %}}

 A PPTX diagramok létrehozásához használjuk
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési API C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 csomagkezelő, keressen
 **Aspose.Slides**
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="A PPTX fájldiagramok létrehozásának lépései C#-ban" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Az [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net) API-kkal az alapdokumentum-diagramok néhány sornyi kóddal elkészíthetők." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Prezentációs osztály objektum létrehozása.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Válassza a Dia lehetőséget.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Diagram hozzáadása a diához.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá releváns diagramsorozatokat adatokkal.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX fájl mentése
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 API-jaink az összes főbb platformon és operációs rendszeren támogatottak. Mielőtt végrehajtaná az alábbi kódot, győződjön meg arról, hogy a következő előfeltételek vannak a rendszeren.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal
- Fejlesztői környezet, mint a Microsoft Visual Studio
- Aspose.Slides for .NET DLL, amelyre a projektben hivatkozik - Telepítse a NuGetből a fenti Letöltés gomb segítségével

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPTX fájl diagram létrehozása - C#" offSpacer="" %}}

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

    {{% blocks/products/pf/agp/content h2="Az Aspose.Slides for .NET API-ról" %}}

 Az Aspose.Slides API használható Microsoft PowerPoint dokumentumok olvasására, írására, manipulálására és konvertálására PDF, XPS, HTML, TIFF, ODP és számos más formátumba. Új fájlokat lehet létrehozni a semmiből, és elmenteni azokat a megfelelő támogatott formátumokba. Az Aspose.Slides egy önálló API prezentációk, diák és elemek létrehozására, elemzésére vagy manipulálására, és nem függ semmilyen szoftvertől, például a Microsofttól vagy az OpenOffice-tól. PPT(X) diagram, PPT(X) diagram generálása Excel adatokból diagramsablon alapján. 
 



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

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott diagramformátumok" subTitle="A C# használatával könnyen kezelhető a különböző formátumok diagramjai, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/chart/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}