---
title: Converti PDF in Image in PHP
url: /it/php-java/conversion/pdf-to-image/
keywords: PDF in Image, conversione di PDF in Image, API PHP, libreria PHP, PDF, Image
description: Converti PDF in Image in PHP. Utilizza l'API PHP di PowerPoint per convertire i file PDF in Image
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PDF in Image in PHP" h2="Potente libreria PHP PowerPoint che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti PDF in Image in PHP" %}}

[**Aspose.Slides per PHP via Java**](https://products.aspose.com/slides/it/php-java/) è una potente libreria PHP per creare e manipolare file di presentazione. Inoltre, fornisce modi flessibili per convertire PDF in Image. Utilizzando **Aspose.Slides per PHP via Java**, qualsiasi sviluppatore o applicazione può convertire i file PDF in Image con poche righe di codice PHP.

Come una moderna API di elaborazione dei documenti, Aspose.Slides per PHP esporta rapidamente i file PDF nei formati di file Image. La libreria Aspose PowerPoint ti consente di convertire PDF in Image se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PDF in Image utilizzando PHP" %}}
Per convertire PDF in Image, dovrai creare una presentazione dal file PDF e salvarla come Image.

{{% blocks/products/pf/agp/code-block title="Codice PHP per convertire PDF in Image" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire PDF in Image utilizzando Aspose.Slides per l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire PDF in Image in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per PHP tramite Java**](https://products.aspose.com/slides/it/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente PDF in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti PDF in altri formati supportati" subTitle="Puoi anche convertire PDF e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}