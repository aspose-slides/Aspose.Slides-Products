---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2780
title: Estrarre testo da presentazioni PPT con C++
url: /it/cpp/parser/ppt/ 
description: Estrai testo da presentazioni PPT in C++. Usa Aspose.Slides for C++ per analizzare diapositive, cornici di testo, paragrafi e porzioni.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analizzare presentazioni PPT in C++" h2="Usa Aspose.Slides for C++ per estrarre testo dalle diapositive senza Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analizzare un file PPT con C++" %}}

Usa Aspose.Slides for C++ per analizzare file di presentazione PPT ed estrarre il testo dalle diapositive. L'API espone il testo delle diapositive tramite `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` e `IPortion`, così puoi leggere il contenuto testuale senza automatizzare Microsoft PowerPoint. Installa il pacchetto [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) da NuGet oppure usa il comando seguente nella Console di Gestione pacchetti.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analizzare file PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come analizzare file PPT in C++" intro="Estrai testo da file PPT con Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPT con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ottieni gli oggetti `ITextFrame` dalla prima diapositiva con `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri gli oggetti `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri gli oggetti `IParagraph` di ogni `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Scorri gli oggetti `IPortion` di ogni `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leggi il testo con `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisiti di sistema" intro="Aspose.Slides for C++ supporta le principali piattaforme desktop e server. Assicurati che il tuo progetto soddisfi i seguenti prerequisiti." %}}

-  Microsoft Windows, Linux, macOS o un altro sistema operativo compatibile con il runtime C++ supportato.
-  La libreria Aspose.Slides for C++ referenziata nel progetto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Realizzato con Aspose.Slides" title="Estrarre testo e immagini online" description="L'app gratuita Aspose.Slides Parser è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPT." button="Apri Aspose.Slides Parser" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides legge i tuoi file prima di scrivere codice.
- Carica un file PPT e ottieni il suo testo e le sue immagini.
- Scarica tutto in un unico archivio ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A PPT file is a Microsoft PowerPoint 97-2003 presentation file. It stores slides, text, images, multimedia, and embedded objects in the binary PowerPoint file format used before the Open XML PPTX format.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati di analisi supportati" subTitle="Con C++ puoi analizzare anche altri formati di presentazione." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/parser/odp/" name="ODP" description="Presentazione OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/parser/pptx/" name="PPTX" description="Presentazione PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
