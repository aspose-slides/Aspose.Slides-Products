---
title: Convertir PPSX en SVG via l'application C++
weight: 4660
url: /fr/cpp/conversion/ppsx-to-svg/ 
description: Exemple de code de conversion C++ pour le document PPSX au format SVG. Utilisez un exemple de code pour la conversion par lots de PPSX en SVG dans n'importe quelle application C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PPSX en SVG via C++" h2="Conversion PPSX vers SVG haute performance à l'aide de la bibliothèque C++ sans avoir besoin de l'installation de Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir PPSX en SVG en utilisant C++" %}}

 Afin de convertir PPSX en SVG, nous utiliserons
 [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/)
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir PPSX en SVG via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Les développeurs C++ peuvent facilement convertir un fichier PPSX en SVG en quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Chargez le fichier PPSX avec Aspose.Slides pour l'objet de présentation C++.
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

{{% blocks/products/pf/agp/code-block title="Code source de conversion PPSX vers SVG C++" offSpacer="" %}}

```cs
// Load the PPSX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsx");
// Save in SVG format.
for (int32_t index = 0; index < prs->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = prs->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Application gratuite pour convertir PPSX en SVG" 
        sectionDescription="[Essayez notre application gratuite Collage](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPSX dans de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Langage de balisage extensible" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Spécifications papier XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}