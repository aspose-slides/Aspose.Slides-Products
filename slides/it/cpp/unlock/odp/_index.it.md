---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sbloccare presentazioni ODP con C++
url: /it/cpp/unlock/odp/
description: Sblocca le presentazioni ODP in C++. Usa Aspose.Slides for C++ per rimuovere crittografia e protezione da scrittura dai file di presentazione.
keywords: Rimuovere protezione da scrittura ODP, decrittografare ODP, sbloccare presentazione ODP, rimuovere protezione ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sbloccare un ODP con C++" h2="Usa Aspose.Slides for C++ per rimuovere crittografia e protezione da scrittura dai file di presentazione senza Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere la protezione da una presentazione ODP con C++" variant="code" %}}

Aspose.Slides for C++ ti permette di rimuovere la crittografia o la protezione da scrittura dalle presentazioni ODP. Usa `LoadOptions` per aprire un file crittografato, quindi l'oggetto `ProtectionManager` della classe `Presentation` per chiamare `RemoveEncryption` o `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la protezione con password da un ODP con C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la protezione da scrittura da una presentazione ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere la password da un ODP con C++" intro="Segui questi passaggi per rimuovere la protezione da una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con la classe `Presentation` e, se è richiesta una password, con `LoadOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa l'oggetto `ProtectionManager` per rimuovere la protezione.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `RemoveEncryption` per i file crittografati o `RemoveWriteProtection` per i file protetti da scrittura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file sbloccato con `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Realizzato con Aspose.Slides" title="Sbloccare file ODP online" description="L'app gratuita Aspose.Slides Unlock è realizzata con [Aspose.Slides for C++](https://products.aspose.com/slides/it/cpp/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Unlock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove la protezione prima di scrivere codice.
- Rimuovi la password o la protezione da scrittura dal tuo file ODP.
- Scarica il file sbloccato.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per lo sblocco" subTitle="Con C++, puoi rimuovere la protezione anche dai seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
