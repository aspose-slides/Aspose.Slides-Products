---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: Extraire le texte de fichiers PPT avec .NET
url: /fr/net/parser/ppt/ 
description: Code source C# pour extraire le texte de fichiers PPT avec .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analyser des fichiers PPT en C#" h2="Extrayez le texte et inspectez la mise en forme du texte des fichiers PPT avec des API .NET côté serveur."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analyser un fichier PPT en C#" %}}

Utilisez [Aspose.Slides for .NET](/slides/fr/net/) pour extraire le texte de présentations PPT. Installez le package depuis [NuGet](https://www.nuget.org/packages/aspose.slides.net) ou exécutez la commande suivante dans la console du Gestionnaire de packages.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Commande" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analyser des fichiers PPT – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment analyser des fichiers PPT en C#" intro="L'analyse de base d'un document avec l'API [Aspose.Slides for .NET](/slides/fr/net/) ne demande que quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPT avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Récupérez les cadres de texte avec `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Parcourez les cadres de texte, les paragraphes et les portions.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lisez les propriétés `Text`, `FontHeight` et `LatinFont.FontName` selon vos besoins.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Un environnement d'exécution .NET pris en charge et une référence au package Aspose.Slides for .NET sont nécessaires. Vous pouvez utiliser Visual Studio ou un autre environnement de développement C# compatible." %}}

- Environnement compatible .NET Framework, .NET, Mono ou Xamarin
- Un environnement de développement C# tel que Visual Studio
- Aspose.Slides for .NET installé depuis NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Conçu avec Aspose.Slides" title="Extraire le texte et les images en ligne" description="L'application gratuite Aspose.Slides Parser est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Parser" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides lit vos fichiers avant d'écrire du code.
- Chargez un fichier PPT et récupérez son texte et ses images.
- Téléchargez le tout dans une seule archive ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A PPT file is a Microsoft PowerPoint 97-2003 presentation in the binary file format. It contains slides with text, bulleted lists, images, multimedia, and embedded OLE objects. Newer versions of PowerPoint use the Office Open XML-based PPTX format. Applications such as OpenOffice Impress and Apple Keynote can also create PPT files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats d'analyse pris en charge" subTitle="En C#, vous pouvez aussi analyser les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/parser/odp/" name="ODP" description="Présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/parser/pptx/" name="PPTX" description="Présentation PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
