---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bewerk HTML in C#
url: /nl/net/editor/html/
keywords: HTML, HTML, C# API, .NET-bibliotheek bewerken
description: Bewerk HTML in C#. Gebruik de .NET-bibliotheek-API om het HTML-bestand te bewerken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bewerk HTML in C#" h2="Krachtige platformonafhankelijke .NET API voor het bewerken van HTML met behulp van C#-code op NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bewerk HTML in C#" variant="code" %}}

Met [**Aspose.Slides for .NET**](https://products.aspose.com/slides/nl/net/) kunt u met slechts een paar regels code een nieuwe regel tekst toevoegen aan een HTML-document.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-code voor het bewerken van HTML" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML bewerken met Aspose.Slides" %}}

[**Aspose.Slides voor .NET**](https://products.aspose.com/slides/nl/net/) is een krachtige .NET-bibliotheek die wordt gebruikt om presentaties, HTML-documenten en andere bestanden te manipuleren en te bewerken. U kunt een HTML-document bewerken door er een nieuwe regel tekst aan toe te voegen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="HTML bewerken in C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides voor .NET**. Zie [**Installatie**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg de bibliotheek toe als referentie in uw project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een instantie van de klasse Presentatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad het HTML-document dat u wilt bewerken.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een nieuwe regel tekst toe.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het gewijzigde HTML-bestand op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
