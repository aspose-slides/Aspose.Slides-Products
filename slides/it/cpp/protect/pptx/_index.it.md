---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteggere presentazioni PPTX con C++
url: /it/cpp/protect/pptx/
description: Proteggi le presentazioni PPTX in C++. Usa Aspose.Slides for C++ per crittografare i file e impostare la protezione da scrittura.
keywords: Protezione da scrittura PPTX, crittografare PPTX, bloccare presentazione PPTX, proteggere PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloccare o proteggere con password un PPTX con C++" h2="Usa Aspose.Slides for C++ per crittografare le presentazioni e impostare la protezione da scrittura senza Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteggere una presentazione PPTX con C++" variant="code" %}}

Aspose.Slides for C++ ti permette di impedire l'apertura o la modifica delle presentazioni PPTX. Usa l'oggetto `ProtectionManager` della classe `Presentation` per crittografare un file con `Encrypt` o limitarne la modifica con `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Crittografare una presentazione PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Impostare la protezione da scrittura per una presentazione PPTX con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come proteggere con password un PPTX con C++" intro="Segui questi passaggi per proteggere una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTX con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Proteggi la presentazione con l'oggetto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa `Encrypt` per la protezione con password o `SetWriteProtection` per la protezione da scrittura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file protetto con `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Realizzato con Aspose.Slides" title="Proteggere con password file PPTX online" description="L'app gratuita Aspose.Slides Lock è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Lock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides protegge le presentazioni prima di scrivere codice.
- Imposta una password per aprire o modificare il tuo file PPTX.
- Scarica il file protetto.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la protezione" subTitle="Con C++, puoi proteggere anche i seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
