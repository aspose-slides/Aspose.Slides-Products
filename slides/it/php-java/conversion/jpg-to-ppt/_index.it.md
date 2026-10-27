---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti JPG in PPT in PHP
url: /it/php-java/conversion/jpg-to-ppt/
keywords: JPG in PPT, conversione di JPG in PPT, API PHP, libreria PHP, JPG, PPT
description: Converti JPG in PPT in PHP. Utilizza l'API PHP di PowerPoint per convertire i file JPG in PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti JPG in PPT in PHP" h2="Potente libreria PHP PowerPoint che aiuta nello sviluppo di applicazioni con la possibilità di creare, unire, ispezionare o convertire file di presentazione Microsoft PowerPoint e OpenOffice senza l'uso di software come Microsoft o Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti JPG in PPT utilizzando PHP" variant="code" %}}

Per convertire JPG in PPT, dovrai creare una presentazione dal file JPG e salvarla come PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice PHP per convertire JPG in PPT" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti JPG in PPT in PHP" %}}

[**Aspose.Slides per PHP via Java**](https://products.aspose.com/slides/it/php-java/) è una potente libreria PHP per creare e manipolare file di presentazione. Inoltre, fornisce modi flessibili per convertire JPG in PPT. Utilizzando **Aspose.Slides per PHP via Java**, qualsiasi sviluppatore o applicazione può convertire i file JPG in PPT con poche righe di codice PHP.

Come una moderna API di elaborazione dei documenti, Aspose.Slides per PHP esporta rapidamente i file JPG nei formati di file PPT. La libreria Aspose PowerPoint ti consente di convertire JPG in PPT se molti altri formati di file

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire JPG in PPT utilizzando Aspose.Slides per l'API PHP" intro="Questi sono i passaggi per convertire JPG in PPT in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa [**Aspose.Slides per PHP tramite Java**](https://products.aspose.com/slides/it/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi un riferimento alla libreria (importa la libreria) al tuo progetto PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Apri i file sorgente JPG in PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il risultato come file PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Realizzato con Aspose.Slides" title="Converti JPG in PPT online" description="L'app gratuita Aspose.Slides Conversion è realizzata con [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/it/php-java/), la stessa API del codice sopra. Aprila e scopri cosa può fare l'API con i tuoi file JPG." button="Apri Aspose.Slides Conversion" note="[Tutte le app gratuite](https://products.aspose.app/slides/family)" upload="Trascina o carica il tuo file" saveAs="Salva come" convert="Converti" >}}
- Funziona nel browser, senza installare nulla.
- Scopri come Aspose.Slides converte i file prima di scrivere codice.
- Carica file JPG e salvali come PPT.
- Scarica il risultato o converti altri file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converti JPG in altri formati supportati" subTitle="Puoi anche convertire JPG e salvare in altri formati di file. Vedi tutti i formati supportati di seguito" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
