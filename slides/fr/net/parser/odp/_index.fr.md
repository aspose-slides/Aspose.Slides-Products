---
title: Extraire du texte et des images d'un document ODP via .NET
weight: 3070
url: /fr/net/parser/odp/ 
description: Code source C# pour extraire du texte et des images d'un fichier ODP sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Analyser les formats ODP en C#" h2="Analyse de documents ODP native et hautes performances à l'aide d'Aspose.Slides côté serveur pour les API .NET, sans l'utilisation de logiciels tels que Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment analyser un fichier ODP à l'aide de C#" %}}

 Afin d'analyser le fichier ODP, nous utiliserons
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


{{< blocks/products/pf/agp/feature-section-col title="Étapes pour analyser les fichiers ODP en C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Une analyse de document de base avec les API [Aspose.Slides pour .NET](https://products.aspose.com/slides/fr/net) peut être effectuée avec seulement quelques lignes de code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger le fichier ODP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenez tous les blocs de texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Parcourez chaque portion de paragraphe.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenez la sortie requise comme le texte, la police, etc.
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

{{% blocks/products/pf/agp/code-block title="Analyser les fichiers ODP - C#" offSpacer="" %}}

```cs
//Extract Text from the Whole odp Presentation 
    Presentation odpPresentation = new Presentation(dataDir + "demo.odp");
    
    //Get an Array of ITextFrame objects from all slides in the PPTX
    ITextFrame[] textFramesPPTX = Aspose.Slides.Util.SlideUtil.GetAllTextFrames(odpPresentation, true);
    
    //Loop through the Array of TextFrames
     for (int i = 0; i < textFramesPPTX.Length; i++)
    
        //Loop through paragraphs in current ITextFrame
        foreach (IParagraph para in textFramesPPTX[i].Paragraphs)
    
             //Loop through portions in the current IParagraph
             foreach (IPortion port in para.Portions)
             {
                //Display text in the current portion
                Console.WriteLine(port.Text);
    
                //Display font height of the text
                Console.WriteLine(port.PortionFormat.FontHeight);
    
                //Display font name of the text
                if (port.PortionFormat.LatinFont != null)
                   Console.WriteLine(port.PortionFormat.LatinFont.FontName);
            }  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de l'API Aspose.Slides pour .NET" %}}

 L'API Aspose.Slides peut être utilisée pour lire, écrire, manipuler et convertir des documents Microsoft PowerPoint en PDF, XPS, HTML, TIFF, ODP et divers autres formats. On peut créer de nouveaux fichiers à partir de zéro et les enregistrer dans les formats pris en charge pertinents. Aspose.Slides est une API autonome pour créer, analyser ou manipuler des présentations, des diapositives et des éléments et ne dépend d'aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Parser Live Demos" sectionDescription="Extract text and images from ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats d'analyse pris en charge" subTitle="En utilisant C#, on peut facilement analyser d'autres formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/parser/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/parser/pptx/" name="PPTX" description="Format de présentation XML ouvert" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}