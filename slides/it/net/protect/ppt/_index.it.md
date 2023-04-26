---
title: Proteggi i file di presentazione PPT utilizzando .NET
url: /it/net/protect/ppt/
keywords: Protezione da scrittura PPT, crittografia di una presentazione PPT, blocco PPT, protezione PPT
description: C# codice sorgente per proteggere la presentazione PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Blocca o proteggi con password PPT utilizzando C#" h2="Crea le tue app .NET per proteggere i file di presentazione utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protezione di una presentazione PPT tramite C#" %}}
Utilizzando Aspose.Slides for .NET, puoi proteggere la tua presentazione PPT dall'apertura o dalla modifica impostando una password. Quindi, per aprire o modificare la presentazione bloccata, un utente deve fornire la password.
{{% blocks/products/pf/agp/code-block title="Crittografia di una presentazione PPT utilizzando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Impostazione della protezione da scrittura su una presentazione PPT utilizzando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come proteggere con password PPT tramite C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per proteggere i file PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPT con un'istanza di Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteggi la presentazione usando la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di protezione supportati" subTitle="Utilizzando C#, puoi anche proteggere i seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}