---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteggere file di presentazione PPTX con Python
url: /it/python-net/protect/pptx/
description: Crittografa le presentazioni PPTX o imposta la protezione da scrittura con Python.
keywords: protezione da scrittura PPTX, crittografare PPTX con Python, bloccare presentazione PPTX, proteggere PPTX con Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Proteggere presentazioni PPTX con Python" h2="Crea applicazioni Python che crittografano le presentazioni o impostano la protezione da scrittura con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteggere una presentazione PPTX con Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/it/python-net/) offre due meccanismi di protezione distinti. Chiama `ProtectionManager.encrypt` per crittografare una presentazione PPTX e richiedere una password per aprirla. In alternativa, chiama `ProtectionManager.set_write_protection` per scoraggiare le modifiche senza crittografare il file. Un utente può comunque aprire una presentazione protetta da scrittura e salvare le modifiche in un altro file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Crittografare una presentazione PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Impostare la protezione da scrittura per una presentazione PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come proteggere un PPTX con Python" intro="Segui questi passaggi per proteggere un file PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri il file PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Usa `ProtectionManager.encrypt` per richiedere una password all'apertura, oppure `ProtectionManager.set_write_protection` per scoraggiare le modifiche.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione protetta come PPTX con `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Realizzato con Aspose.Slides" title="Proteggere con password file PPTX online" description="L'app gratuita Aspose.Slides Lock è realizzata con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/it/python-net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Lock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides protegge le presentazioni prima di scrivere codice.
- Imposta una password per aprire o modificare il tuo file PPTX.
- Scarica il file protetto.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la protezione" subTitle="Usa Python per proteggere altri formati di presentazione supportati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
