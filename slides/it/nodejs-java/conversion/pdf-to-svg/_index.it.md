---
title: Converti PDF in SVG in Node.js
url: /it/nodejs-java/conversion/pdf-to-svg/
keywords: PDF in SVG, Converti PDF in SVG, API Node.js, Libreria Node.js, PDF, SVG
description: Converti PDF in SVG in Node.js. Utilizza l'API della libreria Node.js per convertire i file PDF in SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PDF in SVG in Node.js" h2="Aspose.Slides per Node.js tramite Java è una libreria potente e facile da usare che ti consente di convertire presentazioni PowerPoint in vari formati in Node.js. Supporta tutti gli elementi e i formati di presentazione e fornisce una ricca API per accedervi e modificarli. Ti consente inoltre di esportare le tue diapositive in vari formati per ulteriori elaborazioni o condivisioni." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PDF in SVG in Node.js" %}}

[**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/) è una potente libreria Node.js per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire PDF in SVG. Utilizzando **Aspose.Slides per Node.js tramite Java**, qualsiasi sviluppatore o applicazione può convertire file da PDF a SVG con solo poche righe di codice.

Essendo una moderna API di elaborazione dei documenti, Aspose.Slides per Node.js esporta rapidamente i file PDF nei formati di file SVG. La libreria Aspose PowerPoint ti consente di convertire PDF in SVG e molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PDF in SVG utilizzando Node.js" %}}
Per convertire PDF in SVG, dovrai creare la presentazione dal file PDF e salvarla come SVG.

{{% blocks/products/pf/agp/code-block title="Codice Node.js per convertire PDF in SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire PDF in SVG utilizzando Aspose.Slides per Node.js tramite API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Per convertire PDF in SVG utilizzando Aspose.Slides per Node.js tramite Java, è necessario importare il pacchetto nel file JavaScript e creare un'istanza della classe Presentation. La classe Presentation rappresenta un documento PowerPoint e fornisce metodi per accedere e manipolare i suoi elementi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente PDF in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PDF in altri formati supportati" subTitle="Puoi anche convertire PDF e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}