---
title: Microsoft PowerPoint prezentáció konvertálása különféle formátumokra C++ használatával
url: /hu/cpp/conversion/
description: Konvertálja a Microsoft PowerPoint diákat több fájllá, beleértve a HTML-t, PDF-t és képformátumokat a C++ alapú alkalmazásokban.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PowerPoint-bemutatókonverzió C++-on keresztül" h2="C++ példakódok különböző konverziós forgatókönyvekhez a diák képek, HTML, PDF és más formátumokká konvertálásához." >}}

{{% blocks/products/pf/feature-page-summary %}}

A Microsoft<sup>®</sup> PowerPoint formátumok konvertálási folyamata egyszerű és könnyen automatizálható a C++ PowerPoint könyvtár használatával. A fejlesztők javíthatják a releváns forráskódot, és integrálhatják alkalmazásaikba. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint formátumok interkonverziója" %}}
A Microsoft<sup>®</sup> PowerPoint dokumentumok, köztük a PPT és a PPTX programozott konvertálása mindössze egy kétsoros kód. Töltse be a fájlt a [Presentation class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) segítségével, és hívja meg a [Mentés módszert](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e), amelynek paraméterei a kimeneti fájl és a SaveFormat.OutputFormats.

{{% blocks/products/pf/feature-page-code h3="C++ konverziós kód" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PowerPoint fájlokat PDF-be" %}}

A Microsoft<sup>®</sup> PowerPoint PDF-be konvertálása gyakori forgatókönyv a PDF-dokumentumok hatalmas megosztása miatt. A programozók automatizálhatják, és beállíthatják a vonatkozó PDF-konverziós beállításokat a [PdfOptions class] segítségével (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Néhány konkrét beállítás, például szövegtömörítési szint, JPEG minőség [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), PDF-megfelelőségi szint [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), rejtett diák konvertálása [ShowHiddenSlides](https://aposdeslidese.com/s /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), kiválasztott diák és zárolt [jelszó] generálása (https://apireference.aspose.com/slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides/cpp/class/aspose.slides. .

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint PDF konvertáló kód" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Mentse a Microsoft PowerPoint diákat képként" %}}
Amikor bármikor meg kell jeleníteni a prezentációs tartalmat a weben, akkor a fájlokat HTML-ként vagy képeket JPG, TIFF, PNG stb. formátumban kell renderelni. A diák képpé konvertálása egyszerű. Szerezze be az összes diát a [get_Slides()] segítségével (https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c), és egyenként iterálja végig az egyes diákat. Minden iteráció során használja az [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) elemet a kívánt diaképhez, majd mentse el a kívánt diaképet. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint konvertálás képpé" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}