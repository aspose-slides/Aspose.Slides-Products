---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Afficher PPT en C#
keywords: Afficher PPT, Ouvrir PPT, Visionneuse PPT, PPT, PowerPoint, API C#, Bibliothèque .NET
weight: 6310
url: /fr/net/viewer/ppt/ 
description: Affichez des fichiers PPT en C#. Utilisez Aspose.Slides for .NET pour ouvrir des fichiers de présentation et les enregistrer en HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Afficher PPT en C#" h2="API C# pour ouvrir des fichiers PPT et les enregistrer en HTML responsive."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Afficher PPT avec Aspose.Slides" %}}

Pour afficher des fichiers PPT, utilisez l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), une API C# puissante, complète et facile à utiliser. Ouvrez le gestionnaire de packages [NuGet](https://www.nuget.org/packages/aspose.slides.net), recherchez **Aspose.Slides** et installez-le. Vous pouvez aussi exécuter la commande suivante dans la console du Gestionnaire de packages.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Commande de la console du Gestionnaire de packages" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Avec [**Aspose.Slides for .NET**](/slides/fr/net/), vous pouvez charger un fichier PPT et l'enregistrer en HTML responsive en quelques lignes de code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code C# pour afficher PPT" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment afficher PPT en C#" intro="Aspose.Slides permet aux développeurs d'afficher des fichiers PPT en quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides for .NET**. Voir [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier `PPT` avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez un objet `ResponsiveHtmlController` pour une sortie HTML responsive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez un objet `HtmlOptions` et définissez la propriété `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier PPT au format HTML avec `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Aspose.Slides for .NET prend en charge tous les principaux systèmes d'exploitation. Assurez-vous de disposer des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Un environnement de développement tel que Microsoft Visual Studio
- Une référence à Aspose.Slides for .NET dans votre projet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Conçu avec Aspose.Slides" title="Affichez des fichiers PPT en ligne" description="L'application gratuite Aspose.Slides Viewer est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Viewer" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides affiche vos fichiers avant d'écrire du code.
- Chargez votre fichier PPT et affichez ses diapositives instantanément.
- Fonctionne sur ordinateur et mobile, sans PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Afficher d'autres fichiers" subTitle="Vous pouvez aussi ouvrir et afficher des présentations dans d'autres formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/odp/" name="ODP" description="Présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/otp/" name="OTP" description="Modèle de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pot/" name="POT" description="Modèle PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/potm/" name="POTM" description="Modèle PowerPoint prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/potx/" name="POTX" description="Modèle PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pps/" name="PPS" description="Diaporama PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/ppsm/" name="PPSM" description="Diaporama PowerPoint prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/ppsx/" name="PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pptm/" name="PPTM" description="Présentation PowerPoint prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pptx/" name="PPTX" description="Présentation PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
