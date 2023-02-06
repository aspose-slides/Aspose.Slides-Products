---
title: Modifica POTX in PHP
url: /it/php-java/editor/potx/
keywords: Modifica POTX, modifica PowerPoint, POTX, PowerPoint, API PHP, libreria PHP
description: Modifica POTX in PHP. Usa l'API della libreria PHP per modificare i file POTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Modifica POTX in PHP" h2="Libreria PHP ad alta velocità e multipiattaforma per la modifica di POTX utilizzando il codice PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Modifica POTX utilizzando Aspose.Slides" %}}

[**Aspose.Slides per PHP via Java**](https://products.aspose.com/slides/it/php-java/) è una potente libreria PHP per modificare le presentazioni in modo rapido e semplice. Fornisce agli utenti una vasta gamma di funzionalità per aiutarli a creare diapositive dall'aspetto professionale in pochissimo tempo. Con Aspose, gli utenti possono modificare il testo, aggiungere immagini, animazioni e transizioni alla loro presentazione, nonché applicare varie opzioni di formattazione come il tipo di carattere e la selezione del colore. Inoltre, la libreria offre supporto sia per i file PowerPoint (PPT) che per i formati OpenOffice Presentation (ODP), il che rende più semplice che mai la condivisione di presentazioni su piattaforme diverse senza che si verifichino problemi di compatibilità. Sfruttando la potenza della libreria di Aspose quando crei o modifichi la tua prossima presentazione, sarai sicuro che le tue diapositive avranno sempre un bell'aspetto!
Puoi modificare un file POTX aggiungendovi una nuova riga di testo. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Modifica POTX in PHP" %}}
Usando [**Aspose.Slides per PHP via Java**](https://products.aspose.com/slides/it/php-java/), puoi aggiungere una nuova riga di testo al documento POTX con solo un poche righe di codice.

{{% blocks/products/pf/agp/code-block title="Codice PHP per modificare POTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potx", SaveFormat::Potx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come modificare POTX in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installa **Aspose.Slides per PHP tramite Java**. Vedi [**Installazione**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi la libreria come riferimento nel tuo progetto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica la presentazione POTX che desideri modificare.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi una nuova riga di testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il file modificato.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Modifica altri file" subTitle="Puoi anche modificare i file in altri formati" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}