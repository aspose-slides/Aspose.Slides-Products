---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPTM in JPG in JavaScript
url: /it/nodejs-net/conversion/pptm-to-jpg/
keywords: Da PPTM a JPG, Converti {da_format} a JPG, API Node.js, Libreria JavaScript, PPTM, JPG
description: Converti PPTM in JPG in JavaScript. Utilizza l'API della libreria Node.js per convertire i file PPTM in JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPTM in JPG in JavaScript" h2="Aspose.Slides per Node.js tramite .NET è una libreria potente e facile da usare che ti consente di convertire presentazioni PowerPoint in vari formati in JavaScript. Supporta tutti gli elementi e i formati di presentazione e fornisce una ricca API per accedervi e modificarli. Ti consente inoltre di esportare le tue diapositive in vari formati per ulteriori elaborazioni o condivisioni." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PPTM in JPG utilizzando JavaScript" variant="code" %}}

Per convertire PPTM in JPG, dovrai creare la presentazione dal file PPTM e salvarla come JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice JavaScript per convertire PPTM in JPG" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptm");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".jpg", ImageFormat.Jpeg); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PPTM in JPG in Node.js" %}}

[**Aspose.Slides per Node.js tramite .NET**](https://products.aspose.com/slides/it/nodejs-net/) è una potente libreria Node.js per creare e manipolare file di presentazione. Inoltre, fornisce modi flessibili per convertire PPTM in JPG. Utilizzando **Aspose.Slides per Node.js tramite .NET**, qualsiasi sviluppatore o applicazione può convertire file da PPTM a JPG con solo poche righe di codice.

Come moderna API di elaborazione dei documenti, Aspose.Slides per Node.js tramite .NET esporta rapidamente file PPTM in formati di file JPG. La libreria Aspose PowerPoint ti consente di convertire PPTM in JPG e molti altri formati di file

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPTM in JPG utilizzando Aspose.Slides per Node.js tramite API .NET" intro="Per convertire PPTM in JPG utilizzando Aspose.Slides per Node.js tramite .NET, è necessario importare il pacchetto nel file JavaScript e creare un'istanza della classe Presentation. La classe Presentation rappresenta un documento PowerPoint e fornisce metodi per accedere e manipolare i suoi elementi." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa [**Aspose.Slides per Node.js tramite .NET**](https://products.aspose.com/slides/it/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri i file sorgente PPTM in Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il risultato come file JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converti PPTM in altri formati supportati" subTitle="Puoi anche convertire PPTM e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-svg/" name="PPTM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/nodejs-net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
