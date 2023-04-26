---
title: Proteggi i file di presentazione PPTX utilizzando C++
url: /it/cpp/protect/pptx/
keywords: Protezione da scrittura PPTX, crittografia di una presentazione PPTX, blocco PPTX, protezione PPTX
description: C++ codice sorgente per proteggere la presentazione PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Blocca o proteggi con password PPTX utilizzando C++" h2="Crea le tue app C++ per proteggere i file di presentazione utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Protezione di una presentazione PPTX tramite C++" %}}
Utilizzando Aspose.Slides for C++, puoi proteggere la tua presentazione PPTX dall'apertura o dalla modifica impostando una password. Quindi, per aprire o modificare la presentazione bloccata, un utente deve fornire la password.
{{% blocks/products/pf/agp/code-block title="Crittografia di una presentazione PPTX utilizzando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Impostazione della protezione da scrittura su una presentazione PPTX utilizzando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come proteggere con password PPTX tramite C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per proteggere i file PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica PPTX con un'istanza di Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteggi la presentazione usando la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di protezione supportati" subTitle="Utilizzando C++, puoi anche proteggere i seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}