---
title: Fusionner des fichiers PPS via C++
weight: 8570
url: /fr/cpp/merger/pps/ 
description: Exemple de code C++ pour combiner des documents PPS sur C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Fusionner des fichiers PPS en utilisant C++" h2="Fusion de documents PPS à l'aide d'API C++ côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment fusionner un fichier PPS avec C++" %}}

 Afin de fusionner le fichier PPS, nous utiliserons
 [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/)
 API qui est une API de fusion de documents riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme C++. Vous pouvez télécharger sa dernière version directement, il suffit d'ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestionnaire de paquets, recherchez
 **Aspose.Slides.Cpp**
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Étapes pour fusionner des fichiers PPS en C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Un document de base fusionnant et concaténant avec les API [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/) peut être réalisé avec seulement quelques lignes de code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez les deux fichiers PPS.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilisez la méthode get\_Slides() pour parcourir chaque diapositive.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilisez la fonction AddClone pour fusionner avec le fichier souhaité.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilisez la méthode Save () pour enregistrer dans le chemin spécifié
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides pour C++ prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
- Aspose.Slides pour la DLL C++ référencée dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Fusionner des fichiers PPS - C++" offSpacer="" %}}

```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.pps";
const String sourceFilePath2 = u"SourceFile3.pps";
const String outputFilePath = u"mergedOutput.pps";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pps);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Fusionner des fichiers PDF en ligne" sectionDescription="[Comment fusionner un PDF en Python](https://products.aspose.com/slides/fr/python-net/merge/pdf/)" >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de l'API Aspose.Slides pour C++" %}}

 L'API Aspose.Slides peut être utilisée pour lire, écrire, manipuler et convertir des documents Microsoft PowerPoint en PDF, XPS, HTML, TIFF, ODP et divers autres formats. On peut créer de nouveaux fichiers à partir de zéro et les enregistrer dans les formats pris en charge pertinents. Aspose.Slides est une API autonome pour créer, analyser ou manipuler des présentations, des diapositives et des éléments et ne dépend d'aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPS Merger Live Demos" sectionDescription="Merge PPS documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPS files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" >}}
PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de fusion pris en charge" subTitle="En utilisant C++, One peut également fusionner de nombreux autres formats de fichiers, y compris .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/odp/" name="ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/otp/" name="OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/pot/" name="POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/potm/" name="POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/potx/" name="POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/ppsm/" name="PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/ppsx/" name="PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/pptm/" name="PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/pptx/" name="PPTX" description="Format de présentation XML ouvert" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}