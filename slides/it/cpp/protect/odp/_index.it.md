---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteggere presentazioni ODP con C++
url: /it/cpp/protect/odp/
description: Proteggi le presentazioni ODP in C++. Usa Aspose.Slides for C++ per crittografare i file e impostare la protezione da scrittura.
keywords: Protezione da scrittura ODP, crittografare ODP, bloccare presentazione ODP, proteggere ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloccare o proteggere con password un ODP con C++" h2="Usa Aspose.Slides for C++ per crittografare le presentazioni e impostare la protezione da scrittura senza Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteggere una presentazione ODP con C++" variant="code" %}}

Aspose.Slides for C++ ti permette di impedire l'apertura o la modifica delle presentazioni ODP. Usa l'oggetto `ProtectionManager` della classe `Presentation` per crittografare un file con `Encrypt` o limitarne la modifica con `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Crittografare una presentazione ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Impostare la protezione da scrittura per una presentazione ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come proteggere con password un ODP con C++" intro="Segui questi passaggi per proteggere una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Proteggi la presentazione con l'oggetto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa `Encrypt` per la protezione con password o `SetWriteProtection` per la protezione da scrittura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file protetto con `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Realizzato con Aspose.Slides" title="Proteggere con password file ODP online" description="L'app gratuita Aspose.Slides Lock è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Lock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides protegge le presentazioni prima di scrivere codice.
- Imposta una password per aprire o modificare il tuo file ODP.
- Scarica il file protetto.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la protezione" subTitle="Con C++, puoi proteggere anche i seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
