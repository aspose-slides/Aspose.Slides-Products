---
title: Converti HTML in PNG in Java
url: /it/java/conversion/html-to-png/
keywords: HTML in PNG, conversione di HTML in PNG, API Java, libreria Java, HTML, PNG
description: Converti HTML in PNG in Java. Utilizza l'API della libreria Java per convertire i file HTML in PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti HTML in PNG in Java" h2="Libreria Java ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti HTML in PNG in Java" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) è una potente libreria Java per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire HTML in PNG. Utilizzando **Aspose.Slides per Java**, qualsiasi sviluppatore o applicazione può convertire i file HTML in PNG con poche righe di codice Java.

Come moderna API per l'elaborazione dei documenti, Aspose.Slides per Java esporta rapidamente file HTML in formati di file PNG. La libreria Aspose PowerPoint ti consente di convertire HTML in PNG se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti HTML in PNG utilizzando Java" %}}
Per convertire HTML in PNG, dovrai creare una presentazione dal file HTML e salvarla come PNG.

{{% blocks/products/pf/agp/code-block title="Codice Java per convertire HTML in PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire HTML in PNG utilizzando Aspose.Slides per l'API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire HTML in PNG in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine HTML in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti HTML in altri formati supportati" subTitle="Puoi anche convertire HTML e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}