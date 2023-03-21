---
title: Converti Image in PPTX in PHP
url: /it/php-java/conversion/image-to-pptx/
keywords: Image in PPTX, conversione di Image in PPTX, API PHP, libreria PHP, Image, PPTX
description: Converti Image in PPTX in PHP. Utilizza l'API PHP di PowerPoint per convertire i file Image in PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti Image in PPTX in PHP" h2="Potente libreria PHP PowerPoint che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converti Image in PPTX in PHP" %}}

[**Aspose.Slides per PHP via Java**](https://products.aspose.com/slides/it/php-java/) è una potente libreria PHP per creare e manipolare file di presentazione. Inoltre, fornisce modi flessibili per convertire Image in PPTX. Utilizzando **Aspose.Slides per PHP via Java**, qualsiasi sviluppatore o applicazione può convertire i file Image in PPTX con poche righe di codice PHP.

Come una moderna API di elaborazione dei documenti, Aspose.Slides per PHP esporta rapidamente i file Image nei formati di file PPTX. La libreria Aspose PowerPoint ti consente di convertire Image in PPTX se molti altri formati di file

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti Image in PPTX utilizzando PHP" %}}
Per convertire Image in PPTX, dovrai creare una presentazione dal file Image e salvarla come PPTX.

{{% blocks/products/pf/agp/code-block title="Codice PHP per convertire Image in PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come convertire Image in PPTX utilizzando Aspose.Slides per l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per convertire Image in PPTX in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installa [**Aspose.Slides per PHP tramite Java**](https://products.aspose.com/slides/it/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Apri i file sorgente Image in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il risultato come file PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converti Image in altri formati supportati" subTitle="Puoi anche convertire Image e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}