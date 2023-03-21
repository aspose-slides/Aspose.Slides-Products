---
title: Converti PNG in JPG in Java
url: /it/java/conversion/png-to-jpg/
keywords: PNG in JPG, conversione di PNG in JPG, API Java, libreria Java, PNG, JPG
description: Converti PNG in JPG in Java. Utilizza l'API della libreria Java per convertire i file PNG in JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PNG in JPG in Java" h2="Libreria Java ad alta velocità e multipiattaforma che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PNG in JPG in Java" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) è una potente libreria Java per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire PNG in JPG. Utilizzando **Aspose.Slides per Java**, qualsiasi sviluppatore o applicazione può convertire i file PNG in JPG con poche righe di codice Java.

Come moderna API per l'elaborazione dei documenti, Aspose.Slides per Java esporta rapidamente file PNG in formati di file JPG. La libreria Aspose PowerPoint ti consente di convertire PNG in JPG se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PNG in JPG utilizzando Java" %}}
Per convertire PNG in JPG, dovrai creare una presentazione dal file PNG e salvarla come JPG.

{{% blocks/products/pf/agp/code-block title="Codice Java per convertire PNG in JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire PNG in JPG utilizzando Aspose.Slides per l'API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire PNG in JPG in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file di origine PNG in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PNG in altri formati supportati" subTitle="Puoi anche convertire PNG e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}