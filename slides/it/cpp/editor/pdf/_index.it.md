---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Modifica PDF in C++
url: /it/cpp/editor/pdf/
keywords: Modifica PDF, PDF, API C++, libreria C++
description: Modifica PDF in C++. Usa l'API della libreria C++ per modificare il documento PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifica PDF in C++" h2="Libreria C++ ad alta velocità e multipiattaforma per la modifica di PDF utilizzando il codice C++" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifica PDF in C++" variant="code" %}}

Utilizzando [**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/), puoi aggiungere una nuova riga di testo a un documento PDF con poche righe di codice.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice C++ per la modifica di PDF" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifica PDF utilizzando Aspose.Slides" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) è una potente libreria C++ utilizzata per manipolare e modificare presentazioni, documenti PDF e altri file. Puoi modificare un documento PDF aggiungendovi una nuova riga di testo.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come modificare PDF in C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa **Aspose.Slides per C++**. Vedi [**Installazione**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi la libreria come riferimento nel tuo progetto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un'istanza della classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il documento PDF che desideri modificare.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi una nuova riga di testo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file PDF modificato.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Modifica altri file" subTitle="Puoi anche modificare i file in altri formati" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
