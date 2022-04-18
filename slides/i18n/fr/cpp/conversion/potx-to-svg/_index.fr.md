---
title: Convertir POTX en SVG via une application C++
weight: 4120
url: /fr/cpp/conversion/potx-to-svg/ 
description: Exemple de code de conversion C++ pour le document POTX au format SVG. Utilisez un exemple de code pour la conversion par lots de POTX en SVG dans n'importe quelle application C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir POTX en SVG via C++" h2="Conversion POTX vers SVG haute performance à l'aide de la bibliothèque C++ sans avoir besoin de l'installation de Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir POTX en SVG en utilisant C++" %}}

 Afin de convertir POTX en SVG, nous utiliserons
 [Aspose.Slides pour C++](https://products.aspose.com/slides/cpp)
 API qui est une API de manipulation et de conversion de documents riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme C++. Vous pouvez télécharger sa dernière version directement, il suffit d'ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestionnaire de paquets, recherchez
 Aspose.Slides.Cpp
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir POTX en SVG via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Les développeurs C++ peuvent facilement convertir un fichier POTX en SVG en quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Chargez le fichier POTX avec Aspose.Slides pour l'objet de présentation C++.
1. Appelez la méthode Save().
1. Transmettez le chemin du fichier de sortie avec l'extension de fichier (SVG).
1. Le fichier SVG sera enregistré dans le chemin spécifié.
1. Ouvrez le fichier SVG dans un programme compatible.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code de conversion C++, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
- Aspose.Slides pour la DLL C++ référencée dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code source de conversion POTX vers SVG C++" offSpacer="" %}}

```cs
// Load the POTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.potx");
// Save in SVG format.
prs->Save(u"convertedFile.svg", Aspose::Slides::Export::SaveFormat::Svg);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="POTX to SVG Conversion Live Demos" sectionDescription="[Convert POTX to SVG](https://products.aspose.app/slides/conversion/potx-to-svg) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POTX file, it will be converted instantly to SVG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Bibliothèque de manipulation de présentation C++" %}}

 Les diapositives et l'API de présentation peuvent être utilisées pour lire, écrire, manipuler et convertir des documents Microsoft PowerPoint en PDF, XPS, HTML, TIFF, ODP et divers autres formats. On peut créer de nouveaux fichiers à partir de zéro et les enregistrer dans les formats pris en charge pertinents. Aspose.Slides est une API autonome pour créer, analyser ou manipuler des présentations, des diapositives et des éléments et ne dépend d'aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" >}}

Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. This format was created to replace the POT file format that is based on the binary file format and is supported with PowerPoint 97-2003. The files generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

SVG files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of image. The word Scalable refers to the fact that the SVG can be scaled to different sizes without losing any quality. Text based description of such files make them independent of resolution. It is one of the mostly used format for building website and print graphics in order to achieve scalability. The format can only be used for two-dimensional graphics though. SVG files can be viewed/opened in almost all modern browsers including Chrome, Internet Explorer, Firefox, and Safari.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir POTX dans de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-bmp/" name="POTX TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-emf/" name="POTX TO EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-gif/" name="POTX TO GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-html/" name="POTX TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-odp/" name="POTX TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-otp/" name="POTX TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pdf/" name="POTX TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-png/" name="POTX TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pot/" name="POTX TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-potm/" name="POTX TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pps/" name="POTX TO PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-xml/" name="POTX TO XML" description="Langage de balisage extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-xps/" name="POTX TO XPS" description="Spécifications papier XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}