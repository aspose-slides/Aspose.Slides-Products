---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sbloccare presentazioni PPTX con Python
url: /it/python-net/unlock/pptx/
description: Rimuovi crittografia e protezione da scrittura dalle presentazioni PPTX con Python.
keywords: sbloccare PPTX, rimuovere password da PPTX, rimuovere crittografia PPTX, rimuovere protezione da scrittura da PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sbloccare presentazioni PPTX con Python" h2="Crea applicazioni Python che rimuovono le password di apertura e la protezione da scrittura dalle presentazioni PPTX con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere crittografia e protezione da scrittura da PPTX con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/it/python-net/), puoi rimuovere la crittografia che richiede una password per aprire una presentazione PPTX, oppure disattivarne la protezione da scrittura. Per aprire un file crittografato, fornisci la password attuale tramite `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la crittografia da una presentazione PPTX – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la protezione da scrittura da una presentazione PPTX – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere la protezione da PPTX con Python" intro="Segui questi passaggi per rimuovere la protezione da una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Per un file PPTX crittografato, imposta la password attuale in `LoadOptions`, quindi apri il file con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `ProtectionManager.remove_encryption` per rimuovere la password di apertura, oppure `ProtectionManager.remove_write_protection` per disattivare la protezione da scrittura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione risultante con `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Realizzato con Aspose.Slides" title="Sbloccare file PPTX online" description="L'app gratuita Aspose.Slides Unlock è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Unlock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove la protezione prima di scrivere codice.
- Rimuovi la password o la protezione da scrittura dal tuo file PPTX.
- Scarica il file sbloccato.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per lo sblocco" subTitle="Usa Python per rimuovere la protezione da altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
