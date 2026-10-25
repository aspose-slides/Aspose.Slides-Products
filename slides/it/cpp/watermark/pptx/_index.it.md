---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Aggiungere una filigrana a presentazioni PPTX con C++
url: /it/cpp/watermark/pptx/
description: Aggiungi filigrane di testo o immagine a presentazioni PPTX in C++. Usa Aspose.Slides for C++ per inserire filigrane nelle diapositive.
keywords: aggiungere filigrana a PPTX, aggiungere filigrana di testo a PPTX, aggiungere filigrana immagine a PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Aggiungere una filigrana a una presentazione PPTX con C++" h2="Usa Aspose.Slides for C++ per aggiungere filigrane di testo o immagine ai file di presentazione senza Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aggiungere una filigrana a una presentazione PPTX tramite C++" variant="code" %}}

Aspose.Slides for C++ consente di aggiungere filigrane di testo o immagine alle presentazioni PPTX. Aggiungi una forma di filigrana alla diapositiva master con `AddAutoShape`, aggiungi testo con `AddTextFrame` oppure riempi la forma con un'immagine caricata tramite `File::ReadAllBytes` e `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere una filigrana di testo a PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Aggiungere una filigrana immagine a una presentazione PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come aggiungere una filigrana a PPTX con C++" intro="Segui questi passaggi per aggiungere una filigrana di testo o immagine ai file PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTX con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Seleziona la diapositiva master dalla raccolta `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi una forma di filigrana con il metodo `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi il testo della filigrana con il metodo `AddTextFrame` oppure imposta un riempimento immagine con `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file con filigrana con `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Realizzato con Aspose.Slides" title="Aggiungi filigrane a file PPTX online" description="L'app gratuita Aspose.Slides Watermark è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Watermark" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides aggiunge le filigrane prima di scrivere codice.
- Aggiungi una filigrana di testo o immagine al tuo file PPTX.
- Scarica il file con filigrana.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per le filigrane" subTitle="Con C++ puoi aggiungere filigrane anche ai seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
