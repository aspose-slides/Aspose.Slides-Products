---
lastmod: 2023-02-06
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edytuj PPSM w PHP
url: /pl/php-java/editor/ppsm/
keywords: Edytuj PPSM, Edytuj PowerPoint, PPSM, PowerPoint, PHP API, PHP Library
description: Edytuj PPSM w PHP. Użyj API biblioteki PHP do edycji plików PPSM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edytuj PPSM w PHP" h2="Szybka i wieloplatformowa biblioteka PHP do edycji PPSM przy użyciu kodu PHP" related="FODP,HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edytuj PPSM w PHP" variant="code" %}}

Używając [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/), możesz dodać nowy wiersz tekstu do dokumentu PPSM za pomocą zaledwie kilka linijek kodu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod PHP do edycji PPSM" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.ppsm", SaveFormat::Ppsm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edytuj PPSM za pomocą Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/pl/php-java/) to potężna biblioteka PHP do szybkiej i łatwej edycji prezentacji. Zapewnia użytkownikom szeroką gamę funkcji, które pomagają im błyskawicznie tworzyć profesjonalnie wyglądające slajdy. Dzięki Aspose użytkownicy mogą edytować tekst, dodawać obrazy, animacje i przejścia do swojej prezentacji, a także stosować różne opcje formatowania, takie jak rodzaj czcionki i wybór koloru. Ponadto biblioteka obsługuje zarówno pliki PowerPoint (PPT), jak i formaty OpenOffice Presentation (ODP), co ułatwia udostępnianie prezentacji na różnych platformach bez żadnych problemów ze zgodnością. Wykorzystując moc biblioteki Aspose podczas tworzenia lub edytowania następnej prezentacji, będziesz mieć pewność, że Twoje slajdy będą wyglądać świetnie za każdym razem!
Możesz edytować plik PPSM, dodając do niego nowy wiersz tekstu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak edytować PPSM w PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla PHP przez Javę**. Zobacz [**Instalacja**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj bibliotekę jako odniesienie w swoim projekcie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utwórz wystąpienie klasy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Załaduj prezentację PPSM, którą chcesz edytować.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dodaj nowy wiersz tekstu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz zmieniony plik.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edytuj inne pliki" subTitle="Możesz także edytować pliki w innych formatach" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
