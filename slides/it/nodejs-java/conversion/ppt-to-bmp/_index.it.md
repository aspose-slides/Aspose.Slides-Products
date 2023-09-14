---
title: Converti PPT in BMP in Node.js
url: /it/nodejs-java/conversion/ppt-to-bmp/
keywords: PPT in BMP, Converti PPT in BMP, API Node.js, Libreria Node.js, PPT, BMP
description: Converti PPT in BMP in Node.js. Utilizza l'API della libreria Node.js per convertire i file PPT in BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PPT in BMP in Node.js" h2="Aspose.Slides per Node.js tramite Java è una libreria potente e facile da usare che ti consente di convertire presentazioni PowerPoint in vari formati in Node.js. Supporta tutti gli elementi e i formati di presentazione e fornisce una ricca API per accedervi e modificarli. Ti consente inoltre di esportare le tue diapositive in vari formati per ulteriori elaborazioni o condivisioni." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PPT in BMP in Node.js" %}}

[**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/) è una potente libreria Node.js per la creazione e la manipolazione di file di presentazione. Inoltre, fornisce modi flessibili per convertire PPT in BMP. Utilizzando **Aspose.Slides per Node.js tramite Java**, qualsiasi sviluppatore o applicazione può convertire file da PPT a BMP con solo poche righe di codice.

Essendo una moderna API di elaborazione dei documenti, Aspose.Slides per Node.js esporta rapidamente i file PPT nei formati di file BMP. La libreria Aspose PowerPoint ti consente di convertire PPT in BMP e molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PPT in BMP utilizzando Node.js" %}}
Per convertire PPT in BMP, dovrai creare la presentazione dal file PPT e salvarla come BMP.

{{% blocks/products/pf/agp/code-block title="Codice Node.js per convertire PPT in BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppt");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire PPT in BMP utilizzando Aspose.Slides per Node.js tramite API Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Per convertire PPT in BMP utilizzando Aspose.Slides per Node.js tramite Java, è necessario importare il pacchetto nel file JavaScript e creare un'istanza della classe Presentation. La classe Presentation rappresenta un documento PowerPoint e fornisce metodi per accedere e manipolare i suoi elementi." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per Node.js tramite Java**](https://products.aspose.com/slides/it/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente PPT in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PPT in altri formati supportati" subTitle="Puoi anche convertire PPT e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/nodejs-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}