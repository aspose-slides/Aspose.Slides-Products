---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Fusionner des fichiers OTP via C++
weight: 4580
url: /fr/cpp/merger/otp/ 
description: Exemple de code C++ pour combiner des documents OTP sur l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Fusionner des fichiers OTP à l'aide de C++" h2="Fusion de documents OTP à l'aide d'API C++ côté serveur."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment fusionner un fichier OTP avec C++" %}}

Afin de fusionner le fichier OTP, nous utiliserons
 [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/)
 API qui est une API de fusion de documents riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme C++. Vous pouvez télécharger sa dernière version directement, il suffit d'ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestionnaire de paquets, recherchez
 **Aspose.Slides.Cpp**
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Commande" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Fusionner des fichiers OTP - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.otp";
const String sourceFilePath2 = u"SourceFile3.otp";
const String outputFilePath = u"mergedOutput.otp";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Otp);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour fusionner des fichiers OTP en C++" intro="Un document de base fusionnant et concaténant avec les API [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/) peut être réalisé avec seulement quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez les deux fichiers OTP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez la méthode get\_Slides() pour parcourir chaque diapositive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez la fonction AddClone pour fusionner avec le fichier souhaité.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez la méthode Save () pour enregistrer dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Aspose.Slides pour C++ prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
- Aspose.Slides pour la DLL C++ référencée dans votre projet.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Fusionner des fichiers PDF en ligne"
  description="[Comment fusionner un PDF en Python](https://products.aspose.com/slides/fr/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Les fichiers portant l’extension `.OTP` sont des modèles de présentation OpenDocument. Ils stockent des mises en page, des styles, une mise en forme, des arrière-plans et d’autres contenus réutilisables pour créer de nouvelles présentations au design cohérent. Les fichiers OTP peuvent être créés et ouverts par les applications compatibles avec l’OpenDocument Format (ODF). Ce format est comparable aux formats de modèle Microsoft PowerPoint POT et POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats de fusion pris en charge" subTitle="En utilisant C++, One peut également fusionner de nombreux autres formats de fichiers, y compris .." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/odp/" name="ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/pot/" name="POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/potm/" name="POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/potx/" name="POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/pps/" name="PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/ppsm/" name="PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/ppsx/" name="PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/pptm/" name="PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/merger/pptx/" name="PPTX" description="Format de présentation XML ouvert" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
