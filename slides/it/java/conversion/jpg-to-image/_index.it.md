---
title: Converti JPG in Image in Java
url: /it/java/conversion/jpg-to-image/
keywords: JPG in Image, conversione di JPG in Image, API Java, libreria Java, JPG, Image
description: Converti JPG in Image in Java. Utilizza l'API della libreria Java per convertire i file JPG in Image
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti JPG in Image in Java" h2="Libreria Java ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti JPG in Image in Java" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) è una potente libreria Java per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire JPG in Image. Utilizzando **Aspose.Slides per Java**, qualsiasi sviluppatore o applicazione può convertire i file JPG in Image con poche righe di codice Java.

Come moderna API per l'elaborazione dei documenti, Aspose.Slides per Java esporta rapidamente file JPG in formati di file Image. La libreria Aspose PowerPoint ti consente di convertire JPG in Image se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti JPG in Image utilizzando Java" %}}
Per convertire JPG in Image, dovrai creare una presentazione dal file JPG e salvarla come Image.

{{% blocks/products/pf/agp/code-block title="Codice Java per convertire JPG in Image" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
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

{{< blocks/products/pf/feature-page-section  h2="Come convertire JPG in Image utilizzando Aspose.Slides per l'API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire JPG in Image in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine JPG in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti JPG in altri formati supportati" subTitle="Puoi anche convertire JPG e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}