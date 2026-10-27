---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir TIFF en XPS via l'application C++
weight: 1550
url: /fr/cpp/conversion/tiff-to-xps/ 
description: Exemple de code de conversion C++ pour un document TIFF au format XPS. Utilisez un exemple de code pour la conversion par lots de TIFF en XPS dans n'importe quelle application C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir TIFF en XPS via C++" h2="Conversion TIFF vers XPS haute performance à l'aide de la bibliothèque C++ sans avoir besoin de l'installation de Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment convertir TIFF en XPS en utilisant C++" %}}

Afin de convertir TIFF en XPS, nous utiliserons
 [Aspose.Slides pour C++](https://products.aspose.com/slides/fr/cpp/)
 API qui est une API de manipulation et de conversion de documents riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme C++. Vous pouvez télécharger sa dernière version directement, il suffit d'ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gestionnaire de paquets, recherchez
 Aspose.Slides.Cpp
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code source de conversion TIFF vers XPS C++" >}}
```cs
// Load the TIFF.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.tiff");
// Save in XPS format.
prs->Save(u"convertedFile.xps", Aspose::Slides::Export::SaveFormat::Xps);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour convertir TIFF en XPS via C++" intro="Les développeurs C++ peuvent facilement convertir un fichier TIFF en XPS en quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier TIFF avec Aspose.Slides pour l'objet de présentation C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode Save().{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Transmettez le chemin du fichier de sortie avec l'extension de fichier (XPS).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier XPS sera enregistré dans le chemin spécifié.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier XPS dans un programme compatible.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Avant d'exécuter l'exemple de code de conversion C++, assurez-vous que vous disposez des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
- Aspose.Slides pour la DLL C++ référencée dans votre projet.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Conçu avec Aspose.Slides" title="Convertir TIFF en XPS en ligne" description="L'application gratuite Aspose.Slides Conversion est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers TIFF." button="Ouvrir Aspose.Slides Conversion" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" upload="Déposez ou importez votre fichier" saveAs="Enregistrer sous" convert="Convertir" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Découvrez comment Aspose.Slides convertit les fichiers avant d'écrire du code.
- Téléchargez des fichiers TIFF et enregistrez-les au format XPS.
- Téléchargez le résultat ou convertissez d'autres fichiers.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir TIFF en de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="Langage de balisage extensible" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
