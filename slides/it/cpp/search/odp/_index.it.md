---
title: Cerca testo nei file di presentazione ODP utilizzando C++
url: /it/cpp/search/odp/
keywords: cerca parole in ODP, cerca e sostituisci testo in ODP, cerca testo ODP Presentazione
description: C++ codice sorgente per cercare testo nella presentazione ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Cerca testo ODP utilizzando C++" h2="Crea le tue app C++ per cercare e sostituire il testo nei file di presentazione utilizzando le API lato server. Scopri come trovare tutte le entrate di una determinata parola o frase nei documenti di presentazione. Cerca il testo in base alla corrispondenza esatta dei dati e alla corrispondenza delle espressioni regolari." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Cerca e sostituisci testo ODP Presentazione tramite C++" %}}
Una ricerca di documenti di base e la sostituzione del testo nei contenuti, nei commenti, nelle note delle diapositive o nei metadati con le API di Aspose.Slides for C++ possono essere eseguite con poche righe di codice. Usa la corrispondenza delle espressioni regolari, abbina maiuscole e minuscole per cercare il testo nella presentazione. Cerca testo in titoli, contenuto, piè di pagina o intestazione.
{{% blocks/products/pf/agp/code-block title="Cerca testo ODP Presentazione utilizzando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come cercare testo in ODP tramite C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per cercare file di testo ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica ODP con un'istanza di Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilizza il metodo [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) per trovare e sostituire il testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato nel formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Cerca demo dal vivo" sectionDescription="Cerca e sostituisci subito il testo nei contenuti, nei commenti o nei metadati nei documenti ODP." >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di ricerca supportati" subTitle="Utilizzando C++, puoi anche cercare testo nei seguenti formati:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}