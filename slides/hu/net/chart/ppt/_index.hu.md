---
title: PPT dokumentumdiagram .NET-en keresztül
weight: 7050
url: /hu/net/chart/ppt/ 
description: C#-forráskód diagramok vagy diagramok PPT-fájlba való rajzolásához és konvertálásához .NET-keretrendszeren, .NET Core-on, Windows Azure-on, Mono- vagy Xamarin-platformokon.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPT formátumú diagramok C# nyelven" h2="Natív és nagy teljesítményű PPT-dokumentumdiagramok szerveroldali Aspose.Slides használatával .NET API-khoz, olyan szoftverek használata nélkül, mint a Microsoft vagy az Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PPT diagramok létrehozása C# használatával" %}}

 A PPT diagramok létrehozásához használjuk
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


{{< blocks/products/pf/agp/feature-section-col title="Lépések a PPT-fájl diagramok létrehozásához C#-ban" >}}

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
PPT fájl mentése
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

{{% blocks/products/pf/agp/code-block title="PPT fájl diagram létrehozása - C#" offSpacer="" %}}

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
    
    pres.Save("AsposeScatterChart.ppt", SaveFormat.Ppt);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Az Aspose.Slides for .NET API-ról" %}}

 Az Aspose.Slides API használható Microsoft PowerPoint dokumentumok olvasására, írására, manipulálására és konvertálására PDF, XPS, HTML, TIFF, ODP és számos más formátumba. Új fájlokat lehet létrehozni a semmiből, és elmenteni azokat a megfelelő támogatott formátumokba. Az Aspose.Slides egy önálló API prezentációk, diák és elemek létrehozására, elemzésére vagy manipulálására, és nem függ semmilyen szoftvertől, például a Microsofttól vagy az OpenOffice-tól. PPT(X) diagram, PPT(X) diagram generálása Excel adatokból diagramsablon alapján. 
 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Chart Creation Live Demos" sectionDescription="Generate PPT documents charts right now by visiting our [Live Demos website](https://products.aspose.app/slides/chart). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Chart will be created instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott diagramformátumok" subTitle="A C# használatával könnyen kezelhető a különböző formátumok diagramjai, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/chart/pptx/" name="PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}