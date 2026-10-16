---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti HTML in TIFF in Java
url: /it/java/conversion/html-to-tiff/
keywords: HTML in TIFF, conversione di HTML in TIFF, API Java, libreria Java, HTML, TIFF
description: Converti HTML in TIFF in Java. Utilizza l'API della libreria Java per convertire i file HTML in TIFF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti HTML in TIFF in Java" h2="Libreria Java ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti HTML in TIFF utilizzando Java" variant="code" %}}

Per convertire HTML in TIFF, dovrai creare una presentazione dal file HTML e salvarla come TIFF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice Java per convertire HTML in TIFF" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream tr = new FileInputStream("file.html");
    pres.getSlides().addFromHtml(tr);
    pres.save("doc.tiff", SaveFormat.Tiff);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti HTML in TIFF in Java" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) è una potente libreria Java per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire HTML in TIFF. Utilizzando **Aspose.Slides per Java**, qualsiasi sviluppatore o applicazione può convertire i file HTML in TIFF con poche righe di codice Java.

Come moderna API per l'elaborazione dei documenti, Aspose.Slides per Java esporta rapidamente file HTML in formati di file TIFF. La libreria Aspose PowerPoint ti consente di convertire HTML in TIFF se molti altri formati di file

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire HTML in TIFF utilizzando Aspose.Slides per l'API Java" intro="Questi sono i passaggi per convertire HTML in TIFF in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa [**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri i file di origine HTML in Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il risultato come file TIFF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertitore online gratuito"
  description="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converti HTML in altri formati supportati" subTitle="Puoi anche convertire HTML e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
