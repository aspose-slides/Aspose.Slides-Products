---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PDF do XML v PHP
url: /cs/php-java/conversion/pdf-to-xml/
keywords: PDF do XML, Převést PDF do XML, PHP API, PHP Library, PDF, XML
description: Převeďte PDF do XML v PHP. Použijte PowerPoint PHP API k převodu souborů PDF do XML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PDF do XML v PHP" h2="Výkonná knihovna PowerPoint PHP, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF do XML pomocí PHP" variant="code" %}}

Chcete-li převést PDF do XML, budete muset vytvořit prezentaci ze souboru PDF a uložit ji jako XML.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP kód pro převod PDF do XML" >}}
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
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".xml");
        $slide->writeAsSvg($javafos);
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF do XML v PHP" %}}

[**Aspose.Slides pro PHP přes Javu**](https://products.aspose.com/slides/cs/php-java/) je výkonná PHP knihovna pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PDF do XML. Pomocí **Aspose.Slides for PHP přes Java** může každý vývojář nebo aplikace převést soubory PDF do XML pomocí několika řádků kódu PHP.

Aspose.Slides pro PHP jako moderní API pro zpracování dokumentů rychle exportuje soubory PDF do formátů souborů XML. Knihovna Aspose PowerPoint vám umožňuje převést PDF do XMLs a mnoho dalších formátů souborů

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PDF do XML pomocí Aspose.Slides for PHP API" intro="Toto jsou kroky pro převod PDF do XML v PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [**Aspose.Slides for PHP přes Java**](https://products.aspose.com/slides/cs/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete zdrojové soubory PDF v PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložit výsledek jako soubor XML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Vytvořeno pomocí Aspose.Slides" title="Převod PDF na XML online" description="Bezplatná aplikace Aspose.Slides Conversion je vytvořena pomocí [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/cs/php-java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PDF." button="Otevřít Aspose.Slides Conversion" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" upload="Přetáhněte nebo nahrajte soubor" saveAs="Uložit jako" convert="Převést" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides převádí soubory, ještě než začnete psát kód.
- Nahrajte soubory PDF a uložte je jako XML.
- Stáhněte výsledek nebo převeďte další soubory.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Převést PDF do jiných podporovaných formátů" subTitle="Můžete také převést PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
