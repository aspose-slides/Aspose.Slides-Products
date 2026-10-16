---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir POTM en GIF via C#
weight: 5300
url: /fr/net/conversion/potm-to-gif/ 
description: Exemple de code pour la conversion POTM en GIF C#. Utilisez le code d'exemple d'API pour les fichiers POTM par lots en conversion GIF dans VB.NET, Asp.NET ou toute application basée sur .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir POTM en GIF via C#" h2="Exportez des fichiers PowerPoint® POTM au format GIF sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment convertir POTM en GIF avec C#" %}}

Afin de convertir POTM en GIF, nous utiliserons
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion POTM en GIF C#" >}}
```cs
using (var presentation = new Presentation("template.potm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour convertir POTM en GIF via C#" intro="Les développeurs .NET peuvent facilement charger et convertir des fichiers POTM en GIF en quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier POTM avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourir chaque diapositive de la présentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créer une image à grande échelle en tant que Bitmap à chaque itération{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode Bitmap.Save avec l'extension de fichier GIF et ImageFormat.Gif comme paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion .NET, assurez-vous que vous disposez des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Environnement de développement comme Microsoft Visual Studio.
- Aspose.Slides pour .NET DLL référencé dans votre projet.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Application gratuite pour convertir POTM en GIF"
  description="[Essayez notre application gratuite Video](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir POTM dans de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-bmp/" name="POTM TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-emf/" name="POTM TO EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-html/" name="POTM TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-odp/" name="POTM TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-otp/" name="POTM TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-pdf/" name="POTM TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-png/" name="POTM TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-pot/" name="POTM TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-potx/" name="POTM TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-pps/" name="POTM TO PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-svg/" name="POTM TO SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-swf/" name="POTM TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/conversion/potm-to-xps/" name="POTM TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
