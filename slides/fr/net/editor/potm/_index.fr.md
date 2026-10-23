---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Modifier les fichiers POTM via .NET
url: /fr/net/editor/potm/ 
description: Code source C# pour modifier le document POTM sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifier les formats POTM en C#" h2="Édition de documents POTM native et hautes performances à l'aide d'Aspose.Slides côté serveur pour les API .NET, sans l'utilisation de logiciels tels que Microsoft ou Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment modifier un fichier POTM à l'aide de C#" %}}

Afin de modifier le fichier POTM, nous utiliserons l'API <a href="https://products.aspose.com/slides/fr/net">Aspose.Slides pour .NET</a> qui est une puissante et riche en fonctionnalités et API facile à utiliser pour la plate-forme C# pour n'importe quel éditeur. Ouvrez le gestionnaire de packages <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a>, recherchez <b>Aspose.Slides</b> et installez. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Commande" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Modifier les fichiers POTM - C#" >}}
```cs
using var presentation = new Presentation("document.potm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.potm", SaveFormat.Potm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour éditer les fichiers POTM en C#" intro="Une édition basique de documents avec [Aspose.Slides pour .NET](https://products.aspose.com/slides/fr/net) Les API peuvent être réalisées avec seulement quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier POTM avec un objet `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Accédez à la diapositive et à la forme cibles via des variables.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mettez à jour le texte via `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation modifiée avec `SaveFormat.Potm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Nos API sont prises en charge sur toutes les principales plates-formes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que vous disposez des prérequis suivants sur votre système." %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Environnement de développement comme Microsoft Visual Studio
- Aspose.Slides pour la DLL .NET référencée dans votre projet - Installez depuis NuGet à l'aide du bouton Télécharger ci-dessus

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Conçu avec Aspose.Slides" title="Modifiez des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Editor est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Editor" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides traite vos fichiers avant d'écrire du code.
- Chargez vos fichiers PPTX et modifiez-les instantanément.
- Enregistrez et téléchargez le fichier modifié.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. These settings can include styles, backgrounds, colour palette, fonts and defaults along with macros that consist of custom functions for doing particular task. They may also be opened by a previous version of PowerPoint with Open XML document support installed. POTM files can be opened in Microsoft PowerPoint for editing like any other PowerPoint file.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
