---
title: Tableau de documents PPTX via .NET
weight: 7100
url: /fr/net/chart/pptx/ 
description: Code source C# pour dessiner et convertir un graphique ou un diagramme dans un fichier PPTX sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Tableaux des formats PPTX en C#" h2="Graphiques de documents PPTX natifs et hautes performances utilisant Aspose.Slides côté serveur pour les API .NET, sans l'utilisation de logiciels tels que Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment créer des graphiques PPTX à l'aide de C#" %}}

 Afin de créer des graphiques PPTX, nous utiliserons
 [Aspose.Slides pour .NET](https://products.aspose.com/slides/fr/net)
 API qui est une API de manipulation de documents riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme C#. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gestionnaire de paquets, recherchez
 **Aspose.Slides**
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Étapes pour créer des graphiques de fichiers PPTX en C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Une représentation graphique de document de base avec les API [Aspose.Slides pour .NET](https://products.aspose.com/slides/fr/net) peut être réalisée avec seulement quelques lignes de code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Créer un objet de classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sélectionnez Diapositive.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajouter un graphique à la diapositive.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez des séries de graphiques pertinentes avec des données.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le fichier PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Nos API sont prises en charge sur toutes les principales plates-formes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que vous disposez des prérequis suivants sur votre système.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Environnement de développement comme Microsoft Visual Studio
- Aspose.Slides pour la DLL .NET référencée dans votre projet - Installez depuis NuGet à l'aide du bouton Télécharger ci-dessus

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Créer un graphique de fichiers PPTX - C#" offSpacer="" %}}

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

    {{% blocks/products/pf/agp/content h2="À propos de l'API Aspose.Slides pour .NET" %}}

 L'API Aspose.Slides peut être utilisée pour lire, écrire, manipuler et convertir des documents Microsoft PowerPoint en PDF, XPS, HTML, TIFF, ODP et divers autres formats. On peut créer de nouveaux fichiers à partir de zéro et les enregistrer dans les formats pris en charge pertinents. Aspose.Slides est une API autonome pour créer, analyser ou manipuler des présentations, des diapositives et des éléments et ne dépend d'aucun logiciel comme Microsoft ou OpenOffice. Générer un graphique PPT(X), un diagramme PPT(X) à partir de données Excel, basé sur un modèle de graphique. 
 



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

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de graphique pris en charge" subTitle="En utilisant C#, on peut facilement gérer les graphiques avec différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/chart/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}