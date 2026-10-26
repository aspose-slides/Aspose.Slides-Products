---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteggere file di presentazione PPTX con Java
url: /it/java/protect/pptx/
description: Proteggi le presentazioni PPTX in Java. Usa Aspose.Slides for Java per crittografare i file di presentazione e impostare la protezione da scrittura.
keywords: Protezione da scrittura PPTX, crittografare un PPTX, bloccare presentazione PPTX, proteggere PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloccare o proteggere con password un PPTX con Java" h2="Crea applicazioni Java che proteggono i file di presentazione con API lato server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteggere una presentazione PPTX con Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/it/java/), puoi impedire l'apertura o la modifica di una presentazione PPTX impostando una password. Usa l'oggetto `ProtectionManager` della classe `Presentation` per chiamare metodi come `encrypt` e `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Crittografare una presentazione PPTX con Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Impostare la protezione da scrittura per una presentazione PPTX con Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come proteggere con password un PPTX con Java" intro="Segui questi passaggi per proteggere una presentazione PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica il file PPTX con la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiama il metodo `encrypt` o il metodo `setWriteProtection` dell'oggetto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il file protetto con `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Realizzato con Aspose.Slides" title="Proteggere con password file PPTX online" description="L'app gratuita Aspose.Slides Lock è realizzata con [Aspose.Slides for Java](https://products.aspose.com/slides/it/java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file PPTX." button="Apri Aspose.Slides Lock" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides protegge le presentazioni prima di scrivere codice.
- Imposta una password per aprire o modificare il tuo file PPTX.
- Scarica il file protetto.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altri formati supportati per la protezione" subTitle="Con Java, puoi proteggere anche i seguenti formati." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/it/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
