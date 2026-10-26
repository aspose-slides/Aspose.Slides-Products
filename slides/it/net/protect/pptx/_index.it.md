---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteggere file di presentazione PPTX con .NET
url: /it/net/protect/pptx/
description: Codice sorgente C# per proteggere con password le presentazioni PPTX.
keywords: Protezione da scrittura PPTX, crittografare PPTX, bloccare presentazione PPTX, proteggere PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloccare o proteggere con password file PPTX con C#" h2="Crea app .NET che crittografano le presentazioni e limitano le modifiche con API lato server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteggere una presentazione PPTX con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/it/net/), puoi crittografare una presentazione PPTX o limitarne la modifica con una password. Per aprire una presentazione crittografata con `ProtectionManager.Encrypt` serve la password. Usa `ProtectionManager.SetWriteProtection` per consentire l'apertura della presentazione limitando però le modifiche.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Crittografare una presentazione PPTX con C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Impostare la protezione da scrittura per una presentazione PPTX con C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come proteggere con password una presentazione PPTX con C#" intro="Segui questi passaggi per proteggere con password una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crittografa la presentazione con `ProtectionManager.Encrypt` o limita le modifiche con `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file protetto con `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Realizzato con Aspose.Slides" title="Proteggere con password file PPTX online" description="L'app gratuita Aspose.Slides Lock è realizzata con [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Lock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides protegge le presentazioni prima di scrivere codice.
- Imposta una password per aprire o modificare il tuo file PPTX.
- Scarica il file protetto.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la protezione" subTitle="Con C#, puoi proteggere anche i seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
