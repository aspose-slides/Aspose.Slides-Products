---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Afficher OTP en C#
keywords: Afficher OTP, Ouvrir OTP, Visionneuse OTP, OTP, API C#, Bibliothèque .NET
weight: 6830
url: /fr/net/viewer/otp/ 
description: Affichez des fichiers OTP en C#. Utilisez Aspose.Slides for .NET pour ouvrir des fichiers de présentation et les enregistrer en HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Afficher OTP en C#" h2="API C# pour ouvrir des fichiers OTP et les enregistrer en HTML responsive."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Afficher OTP avec Aspose.Slides" %}}

Pour afficher des fichiers OTP, utilisez l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), une API C# puissante, complète et facile à utiliser. Ouvrez le gestionnaire de packages [NuGet](https://www.nuget.org/packages/aspose.slides.net), recherchez **Aspose.Slides** et installez-le. Vous pouvez aussi exécuter la commande suivante dans la console du Gestionnaire de packages.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Commande de la console du Gestionnaire de packages" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Avec [**Aspose.Slides for .NET**](/slides/fr/net/), vous pouvez charger un fichier OTP et l'enregistrer en HTML responsive en quelques lignes de code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code C# pour afficher OTP" >}}
```cs
using var presentation = new Presentation("presentation.otp");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment afficher OTP en C#" intro="Aspose.Slides permet aux développeurs d'afficher des fichiers OTP en quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides for .NET**. Voir [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier `OTP` avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez un objet `ResponsiveHtmlController` pour une sortie HTML responsive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez un objet `HtmlOptions` et définissez la propriété `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier OTP au format HTML avec `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Aspose.Slides for .NET prend en charge tous les principaux systèmes d'exploitation. Assurez-vous de disposer des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Un environnement de développement tel que Microsoft Visual Studio
- Une référence à Aspose.Slides for .NET dans votre projet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Conçu avec Aspose.Slides" title="Affichez des fichiers OTP en ligne" description="L'application gratuite Aspose.Slides Viewer est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers OTP." button="Ouvrir Aspose.Slides Viewer" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides affiche vos fichiers avant d'écrire du code.
- Chargez votre fichier OTP et affichez ses diapositives instantanément.
- Fonctionne sur ordinateur et mobile, sans PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Les fichiers portant l’extension `.OTP` sont des modèles de présentation OpenDocument. Ils stockent des mises en page, des styles, une mise en forme, des arrière-plans et d’autres contenus réutilisables pour créer de nouvelles présentations au design cohérent. Les fichiers OTP peuvent être créés et ouverts par les applications compatibles avec l’OpenDocument Format (ODF). Ce format est comparable aux formats de modèle Microsoft PowerPoint POT et POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Afficher d'autres fichiers" subTitle="Vous pouvez aussi ouvrir et afficher des présentations dans d'autres formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/odp/" name="ODP" description="Présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pot/" name="POT" description="Modèle PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/potm/" name="POTM" description="Modèle PowerPoint prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/potx/" name="POTX" description="Modèle PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pps/" name="PPS" description="Diaporama PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/ppsm/" name="PPSM" description="Diaporama PowerPoint prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/ppsx/" name="PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/ppt/" name="PPT" description="Présentation PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pptm/" name="PPTM" description="Présentation PowerPoint prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/net/viewer/pptx/" name="PPTX" description="Présentation PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
