---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sbloccare presentazioni ODP con Python
url: /it/python-net/unlock/odp/
description: Rimuovi crittografia e protezione da scrittura dalle presentazioni ODP con Python.
keywords: sbloccare ODP, rimuovere password da ODP, rimuovere crittografia ODP, rimuovere protezione da scrittura da ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sbloccare presentazioni ODP con Python" h2="Crea applicazioni Python che rimuovono le password di apertura e la protezione da scrittura dalle presentazioni ODP con Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere crittografia e protezione da scrittura da ODP con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/it/python-net/), puoi rimuovere la crittografia che richiede una password per aprire una presentazione ODP, oppure disattivarne la protezione da scrittura. Per aprire un file crittografato, fornisci la password attuale tramite `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la crittografia da una presentazione ODP – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la protezione da scrittura da una presentazione ODP – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere la protezione da ODP con Python" intro="Segui questi passaggi per rimuovere la protezione da una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Per un file ODP crittografato, imposta la password attuale in `LoadOptions`, quindi apri il file con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `ProtectionManager.remove_encryption` per rimuovere la password di apertura, oppure `ProtectionManager.remove_write_protection` per disattivare la protezione da scrittura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione risultante con `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Realizzato con Aspose.Slides" title="Sbloccare file ODP online" description="L'app gratuita Aspose.Slides Unlock è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Unlock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove la protezione prima di scrivere codice.
- Rimuovi la password o la protezione da scrittura dal tuo file ODP.
- Scarica il file sbloccato.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per lo sblocco" subTitle="Usa Python per rimuovere la protezione da altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
