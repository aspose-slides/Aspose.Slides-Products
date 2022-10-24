---
title: Konwertuj PPTM na FODP w PHP
weight: 2330
url: /pl/php-java/conversion/pptm-to-fodp/ 
keywords: "Convert, PowerPoint, PPTM, FODP, Presentation, PHP"
description: Przykładowy kod konwersji PHP z PPTM do FODP. Użyj PowerPoint PHP API do konwersji wsadowej plików {z_formatu} na pliki {do_formatu}.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj PPTM na FODP w PHP" h2="Potężna biblioteka PowerPoint PHP do konwersji PPTM na FODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konwertuj PPTM na FODP w PHP" %}}

Chcesz programowo przekonwertować pliki PPTM na FODP? Używając [*Aspose.Slides dla PHP przez Javę*](https://products.aspose.com/slides/pl/php-java/) każdy programista może przekonwertować format PPTM na FODP za pomocą zaledwie kilku linii kodu PHP .

Jako nowoczesny interfejs API do przetwarzania prezentacji, Aspose.Slides for PHP szybko tworzy FODP z PPTM. Przetestuj jakość konwersji PPTM na FODP bezpośrednio w [przeglądarce](https://products.aspose.app/slides/conversion). Biblioteka Aspose PowerPoint PPTX umożliwia konwersję plików PPTM do wielu popularnych formatów.

Bibliotekę możesz zainstalować z [Composer](https://packagist.org/packages/aspose/slides) za pomocą następującego polecenia:

{{% blocks/products/pf/agp/code-block title="Konsola/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Jak przekonwertować PPTM na FODP w PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby przekonwertować plik PPTM na FODP za pomocą PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Załaduj plik PPTM z instancją klasy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wywołaj metodę `save`, określając ścieżkę pliku wyjściowego i SaveFormat.FODP jako parametry
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Plik PPTM zostanie zapisany pod określoną ścieżką
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu źródłowego konwersji PHP upewnij się, że spełnione są następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

1. Zainstaluj PHP 7, dodaj ścieżkę do PHP do systemowej zmiennej `PATH` i ustaw `allow_url_include` na `On` w pliku `php.ini`.
1. Zainstaluj JRE 8. Ustaw zmienną środowiskową `JAVA_HOME` jako ścieżkę do lokalizacji zainstalowanego środowiska JRE.
1. Zainstaluj Apache Tomcat 8.0 (zobacz [więcej](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję PPTM na FODP PHP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.fodp", SaveFormat::Fodp);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Zapisz PPTM jako FODP w PHP" %}}
Skorzystaj z bezpłatnej aplikacji, aby zobaczyć demonstrację procesu konwersji formatu PPTM na FODP. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPTM to FODP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować PPTM na wiele innych formatów plików. Zobacz inne obsługiwane konwersje poniżej" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmapa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Graficzny format wymiany" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="hipertekstowy język znaczników" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="Obraz JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Format prezentacji OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Standardowy format OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="format dokumentu przenośnego" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Przenośna Grafika Sieciowa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Pokaz slajdów z obsługą makr" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Otwórz format prezentacji XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Skalowalna Grafika wektorowa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Oznaczony format obrazu" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Specyfikacje papieru XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}