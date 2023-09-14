---
title: Converti PPSX in PNG in Node.js
url: /it/nodejs-java/conversion/ppsx-to-png/
keywords: PPSX in PNG, Converti PPSX in PNG, API Node.js, Libreria Node.js, PPSX, PNG
description: Converti PPSX in PNG in Node.js. Utilizza l'API della libreria Node.js per convertire i file PPSX in PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PPSX in PNG in Node.js" h2="Aspose.Slides per Node.js tramite Java è una libreria potente e facile da usare che ti consente di convertire presentazioni PowerPoint in vari formati in Node.js. Supporta tutti gli elementi e i formati di presentazione e fornisce una ricca API per accedervi e modificarli. Ti consente inoltre di esportare le tue diapositive in vari formati per ulteriori elaborazioni o condivisioni." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PPSX in PNG in Node.js" %}}

[**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/) è una potente libreria Node.js per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire PPSX in PNG. Utilizzando **Aspose.Slides per Node.js tramite Java**, qualsiasi sviluppatore o applicazione può convertire file da PPSX a PNG con solo poche righe di codice.

Essendo una moderna API di elaborazione dei documenti, Aspose.Slides per Node.js esporta rapidamente i file PPSX nei formati di file PNG. La libreria Aspose PowerPoint ti consente di convertire PPSX in PNG e molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PPSX in PNG utilizzando Node.js" %}}
Per convertire PPSX in PNG, dovrai creare la presentazione dal file PPSX e salvarla come PNG.

{{% blocks/products/pf/agp/code-block title="Codice Node.js per convertire PPSX in PNG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsx");
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

{{< blocks/products/pf/feature-page-section  h2="Come convertire PPSX in PNG utilizzando Aspose.Slides per Node.js tramite API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Per convertire PPSX in PNG utilizzando Aspose.Slides per Node.js tramite Java, è necessario importare il pacchetto nel file JavaScript e creare un'istanza della classe Presentation. La classe Presentation rappresenta un documento PowerPoint e fornisce metodi per accedere e manipolare i suoi elementi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente PPSX in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PPSX in altri formati supportati" subTitle="Puoi anche convertire PPSX e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}