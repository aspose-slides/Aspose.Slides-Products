---
title: Converti POTX in PNG in Node.js
url: /it/nodejs-java/conversion/potx-to-png/
keywords: POTX in PNG, Converti POTX in PNG, API Node.js, Libreria Node.js, POTX, PNG
description: Converti POTX in PNG in Node.js. Utilizza l'API della libreria Node.js per convertire i file POTX in PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti POTX in PNG in Node.js" h2="Aspose.Slides per Node.js tramite Java è una libreria potente e facile da usare che ti consente di convertire presentazioni PowerPoint in vari formati in Node.js. Supporta tutti gli elementi e i formati di presentazione e fornisce una ricca API per accedervi e modificarli. Ti consente inoltre di esportare le tue diapositive in vari formati per ulteriori elaborazioni o condivisioni." >}}

{{% blocks/products/pf/feature-page-section h2="Converti POTX in PNG in Node.js" %}}

[**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/) è una potente libreria Node.js per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire POTX in PNG. Utilizzando **Aspose.Slides per Node.js tramite Java**, qualsiasi sviluppatore o applicazione può convertire file da POTX a PNG con solo poche righe di codice.

Essendo una moderna API di elaborazione dei documenti, Aspose.Slides per Node.js esporta rapidamente i file POTX nei formati di file PNG. La libreria Aspose PowerPoint ti consente di convertire POTX in PNG e molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti POTX in PNG utilizzando Node.js" %}}
Per convertire POTX in PNG, dovrai creare la presentazione dal file POTX e salvarla come PNG.

{{% blocks/products/pf/agp/code-block title="Codice Node.js per convertire POTX in PNG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potx");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".png");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "png", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire POTX in PNG utilizzando Aspose.Slides per Node.js tramite API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Per convertire POTX in PNG utilizzando Aspose.Slides per Node.js tramite Java, è necessario importare il pacchetto nel file JavaScript e creare un'istanza della classe Presentation. La classe Presentation rappresenta un documento PowerPoint e fornisce metodi per accedere e manipolare i suoi elementi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente POTX in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti POTX in altri formati supportati" subTitle="Puoi anche convertire POTX e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}