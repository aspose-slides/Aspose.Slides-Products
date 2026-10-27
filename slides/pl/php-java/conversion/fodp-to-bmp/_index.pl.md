---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj FODP na BMP w PHP
weight: 10
url: /pl/php-java/conversion/fodp-to-bmp/ 
keywords: "Convert, PowerPoint, FODP, BMP, Presentation, PHP"
description: Przykładowy kod konwersji PHP z FODP do BMP. Użyj PowerPoint PHP API do konwersji wsadowej plików {z_formatu} na pliki {do_formatu}.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj FODP na BMP w PHP" h2="Potężna biblioteka PowerPoint PHP do konwersji FODP na BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj FODP na BMP w PHP" %}}

Chcesz programowo przekonwertować pliki FODP na BMP? Używając [*Aspose.Slides dla PHP przez Javę*](https://products.aspose.com/slides/pl/php-java/) każdy programista może przekonwertować format FODP na BMP za pomocą zaledwie kilku linii kodu PHP .

Jako nowoczesny interfejs API do przetwarzania prezentacji, Aspose.Slides for PHP szybko tworzy BMP z FODP. Przetestuj jakość konwersji FODP na BMP bezpośrednio w [przeglądarce](https://products.aspose.app/slides/conversion). Biblioteka Aspose PowerPoint PPTX umożliwia konwersję plików FODP do wielu popularnych formatów.

Bibliotekę możesz zainstalować z [Composer](https://packagist.org/packages/aspose/slides) za pomocą następującego polecenia:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsola/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Zapisz FODP jako BMP w PHP" %}}

Skorzystaj z bezpłatnej aplikacji, aby zobaczyć demonstrację procesu konwersji formatu FODP na BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ten przykładowy kod pokazuje konwersję FODP na BMP PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować FODP na BMP w PHP" intro="Oto kroki, aby przekonwertować plik FODP na BMP za pomocą PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj plik FODP z instancją klasy Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `save`, określając ścieżkę pliku wyjściowego i SaveFormat.BMP jako parametry{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Plik FODP zostanie zapisany pod określoną ścieżką{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="wymagania systemowe" intro="Przed uruchomieniem przykładowego kodu źródłowego konwersji PHP upewnij się, że spełnione są następujące wymagania wstępne." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj PHP 7, dodaj ścieżkę do PHP do systemowej zmiennej `PATH` i ustaw `allow_url_include` na `On` w pliku `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj JRE 8. Ustaw zmienną środowiskową `JAVA_HOME` jako ścieżkę do lokalizacji zainstalowanego środowiska JRE.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj Apache Tomcat 8.0 (zobacz [więcej](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Zbudowano z Aspose.Slides" title="Konwertuj FODP na BMP online" description="Bezpłatna aplikacja Aspose.Slides Conversion została zbudowana z użyciem [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/pl/php-java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami FODP." button="Otwórz Aspose.Slides Conversion" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" upload="Upuść lub prześlij plik" saveAs="Zapisz jako" convert="Konwertuj" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides konwertuje pliki, zanim napiszesz kod.
- Prześlij pliki FODP i zapisz je jako BMP.
- Pobierz wynik lub przekonwertuj kolejne pliki.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować FODP na wiele innych formatów plików. Zobacz inne obsługiwane konwersje poniżej" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Graficzny format wymiany" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="hipertekstowy język znaczników" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="Obraz JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="Format prezentacji OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="Standardowy format OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="format dokumentu przenośnego" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Przenośna Grafika Sieciowa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Pliki szablonów programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Plik szablonu programu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Prezentacja szablonu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Pokaz slajdów z obsługą makr" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="Pokaz slajdów programu PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Plik prezentacji z obsługą makr" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Otwórz format prezentacji XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Skalowalna Grafika wektorowa" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Oznaczony format obrazu" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="Specyfikacje papieru XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
