---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir POT en JPEG via C#
weight: 6650
url: /fr/net/conversion/pot-to-jpeg/ 
description: Exemple de code pour la conversion POT en JPEG C#. Utilisez le code d'exemple d'API pour la conversion de fichiers POT par lots en JPEG dans VB.NET, Asp.NET ou toute autre application basée sur .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir POT en JPEG via C#" h2="Exportez des fichiers PowerPoint® POT au format JPEG sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment convertir POT en JPEG à l'aide de C#" %}}

Afin de convertir POT en JPEG, nous utiliserons
 [Aspose.Slides pour .NET](https://products.aspose.com/slides/fr/net)
 API qui est une API de manipulation et de conversion de documents riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme C#. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gestionnaire de paquets, recherchez
 Aspose.Slides
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Commande de la console du gestionnaire de packages" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion POT en JPEG C#" >}}
```cs
using (var presentation = new Presentation("template.pot"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour convertir POT en JPEG via C#" intro="Les développeurs .NET peuvent facilement charger et convertir des fichiers POT en JPEG en quelques lignes de code seulement." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier POT avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourir chaque diapositive de la présentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créer une image à grande échelle en tant que Bitmap à chaque itération{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode Bitmap.Save avec l'extension de fichier JPEG et ImageFormat.Jpeg comme paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion .NET, assurez-vous que vous disposez des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Environnement de développement comme Microsoft Visual Studio.
- Aspose.Slides pour .NET DLL référencé dans votre projet.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Application gratuite pour convertir POT en JPEG"
  description="[Essayez notre application gratuite pour convertir PPT en JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir POT dans de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-bmp/" name="POT TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-emf/" name="POT TO EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-gif/" name="POT TO GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-html/" name="POT TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-odp/" name="POT TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-otp/" name="POT TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-pdf/" name="POT TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-png/" name="POT TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-potm/" name="POT TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-potx/" name="POT TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-pps/" name="POT TO PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-svg/" name="POT TO SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-swf/" name="POT TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/pot-to-xps/" name="POT TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
