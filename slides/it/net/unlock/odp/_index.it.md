---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sbloccare file di presentazione ODP con .NET
url: /it/net/unlock/odp/
description: Codice sorgente C# per rimuovere la protezione con password dalle presentazioni ODP.
keywords: Rimuovere protezione da scrittura ODP, decrittografare ODP, sbloccare presentazione ODP, rimuovere protezione ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sbloccare file ODP con C#" h2="Crea app .NET che rimuovono crittografia e protezione da scrittura dalle presentazioni con API lato server." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Rimuovere la protezione da una presentazione ODP con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/it/net/), puoi rimuovere la crittografia o la protezione da scrittura da una presentazione ODP. Per rimuovere la crittografia, carica la presentazione con la password corretta e chiama `ProtectionManager.RemoveEncryption`. Per rimuovere la protezione da scrittura, chiama `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la crittografia da una presentazione ODP con C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Rimuovere la protezione da scrittura da una presentazione ODP con C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come rimuovere la protezione da una presentazione ODP con C#" intro="Segui questi passaggi per rimuovere la protezione da una presentazione ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file ODP con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Per un file crittografato, fornisci la password tramite `LoadOptions.Password` prima di caricarlo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama `ProtectionManager.RemoveEncryption` o `ProtectionManager.RemoveWriteProtection`, a seconda della protezione applicata.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva la presentazione sbloccata con `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Realizzato con Aspose.Slides" title="Sbloccare file ODP online" description="L'app gratuita Aspose.Slides Unlock è realizzata con [Aspose.Slides for .NET](https://products.aspose.com/slides/it/net/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file ODP." button="Apri Aspose.Slides Unlock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides rimuove la protezione prima di scrivere codice.
- Rimuovi la password o la protezione da scrittura dal tuo file ODP.
- Scarica il file sbloccato.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per lo sblocco" subTitle="Con C#, puoi rimuovere la protezione anche dai seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
