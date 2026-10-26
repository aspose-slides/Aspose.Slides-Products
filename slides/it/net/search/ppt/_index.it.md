---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cercare testo nei file di presentazione PPT con .NET
url: /it/net/search/ppt/
description: Codice sorgente C# per cercare testo nelle presentazioni PPT.
keywords: Cercare testo in PPT, trovare testo in PPT, cercare testo nella presentazione PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cercare testo nei file PPT con C#" h2="Crea app .NET che trovano testo nelle presentazioni con API lato server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cercare testo in una presentazione PPT con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/it/net/), puoi cercare testo in una presentazione PPT. Recupera le cornici di testo di una diapositiva con `SlideUtil.GetAllTextBoxes`, quindi controlla i loro valori `Text` per trovare la frase richiesta.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cercare testo in una presentazione PPT con C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come cercare testo in una presentazione PPT con C#" intro="Segui questi passaggi per cercare testo in una presentazione PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPT con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ottieni la diapositiva richiesta da `Presentation.Slides` e assegnala a una variabile.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recupera le sue cornici di testo con [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Controlla se il valore `Text` di ogni cornice contiene la frase richiesta.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Realizzato con Aspose.Slides" title="Cercare testo nei file PPT online" description="L'app gratuita Aspose.Slides Search è realizzata con [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPT." button="Apri Aspose.Slides Search" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides trova il testo prima di scrivere codice.
- Cerca testo semplice o espressioni regolari nel tuo file PPT.
- Scarica le corrispondenze come file di testo.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la ricerca" subTitle="Con C#, puoi cercare testo anche nei seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
