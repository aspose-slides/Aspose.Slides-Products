---
title: Konverze prezentace Microsoft PowerPoint do různých formátů pomocí C++
url: /cs/cpp/conversion/
description: Převeďte prezentace Microsoft PowerPoint do více souborů včetně HTML, PDF a obrazových formátů v aplikacích založených na C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konverze prezentací Microsoft<sup>®</sup> PowerPoint přes C++" h2="C++ ukázkové kódy pro různé scénáře převodu pro převod snímků do obrázků, HTML, PDF a dalších formátů." >}}

{{% blocks/products/pf/feature-page-summary %}}

Proces převodu formátů Microsoft<sup>®</sup> PowerPoint je jednoduchý a lze jej snadno automatizovat pomocí knihovny C++ PowerPoint. Vývojáři mohou vylepšit relevantní zdrojový kód a integrovat jej do svých aplikací. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter převod formátů Microsoft PowerPoint" %}}
Vzájemná konverze dokumentů Microsoft<sup>®</sup> PowerPoint včetně PPT, PPTX je programově pouze dvouřádkový kód. Načtěte soubor pomocí [Presentation class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) a voláním [Save method](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) s výstupním souborem a SaveFormat.OutputFormats jako parametry.

{{% blocks/products/pf/feature-page-code h3="C++ převodní kód" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Převeďte soubory PowerPoint do PDF" %}}

Převod Microsoft<sup>®</sup> PowerPoint do PDF je běžným scénářem kvůli obrovskému sdílení dokumentů PDF. Programátoři jej mohou automatizovat a nastavit příslušná nastavení převodu PDF pomocí [třídy PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Několik specifických nastavení, jako je úroveň komprese textu, kvalita JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), úroveň souladu s PDF (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), převod skrytých snímků [ShowHiddenSlides](https://com/apireference.aspose/classes. /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), vybrané snímky a generování zamčených [hesla](https://apireference.aspose.com/slides/cpp/class/aspose.slides4598383 PDF3 PDF6 chráněných souborů PDFcc9 .

{{% blocks/products/pf/feature-page-code h3="Kód pro převod C++ PowerPoint do PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Uložit snímky aplikace Microsoft PowerPoint jako obrázky" %}}
když někdy nastane případ zobrazení obsahu prezentace na webu, pak je potřeba vykreslit soubory jako HTML nebo obrázky JPG, TIFF, PNG atd. Proces převodu snímků na obrázky je jednoduchý. Získejte všechny snímky pomocí [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) a procházejte každý snímek jeden po druhém. Během každé iterace použijte [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) pro snímek snímku a poté jej uložte do požadovaného formátu obrázku. 

{{% blocks/products/pf/feature-page-code h3="Převod C++ PowerPoint na obrázek" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}