---
title: Converti HTML in PPT in PHP
url: /it/php-java/conversion/html-to-ppt/
keywords: HTML in PPT, conversione di HTML in PPT, API PHP, libreria PHP, HTML, PPT
description: Converti HTML in PPT in PHP. Utilizza l'API PHP di PowerPoint per convertire i file HTML in PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti HTML in PPT in PHP" h2="Potente libreria PHP PowerPoint che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti HTML in PPT in PHP" %}}

[**Aspose.Slides per PHP via Java**](https://products.aspose.com/slides/it/php-java/) è una potente libreria PHP per creare e manipolare file di presentazione. Inoltre, fornisce modi flessibili per convertire HTML in PPT. Utilizzando **Aspose.Slides per PHP via Java**, qualsiasi sviluppatore o applicazione può convertire i file HTML in PPT con poche righe di codice PHP.

Come una moderna API di elaborazione dei documenti, Aspose.Slides per PHP esporta rapidamente i file HTML nei formati di file PPT. La libreria Aspose PowerPoint ti consente di convertire HTML in PPT se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti HTML in PPT utilizzando PHP" %}}
Per convertire HTML in PPT, dovrai creare una presentazione dal file HTML e salvarla come PPT.

{{% blocks/products/pf/agp/code-block title="Codice PHP per convertire HTML in PPT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
    $pres->save("output.ppt", SaveFormat::Ppt);        
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire HTML in PPT utilizzando Aspose.Slides per l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire HTML in PPT in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per PHP tramite Java**](https://products.aspose.com/slides/it/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente HTML in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti HTML in altri formati supportati" subTitle="Puoi anche convertire HTML e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}