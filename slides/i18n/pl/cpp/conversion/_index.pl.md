---
title: Konwersja prezentacji programu Microsoft PowerPoint do różnych formatów przy użyciu C++
url: /pl/cpp/conversion/
description: Konwertuj slajdy programu Microsoft PowerPoint do wielu plików, w tym HTML, PDF i obrazów w aplikacjach opartych na C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja prezentacji Microsoft<sup>®</sup> PowerPoint za pomocą C++" h2="Przykładowe kody C++ dla różnych scenariuszy konwersji do konwersji slajdów do obrazów, HTML, PDF i innych formatów." >}}

{{% blocks/products/pf/feature-page-summary %}}

Proces konwersji formatów Microsoft<sup>®</sup> PowerPoint jest prosty i łatwy do zautomatyzowania procesów przy użyciu biblioteki C++ PowerPoint. Deweloperzy mogą ulepszać odpowiedni kod źródłowy i integrować go w swoich aplikacjach. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja między formatami Microsoft PowerPoint" %}}
Programowa konwersja dokumentów Microsoft<sup>®</sup> PowerPoint, w tym PPT, PPTX, to tylko dwuwierszowy kod. Załaduj plik, używając [klasy prezentacji](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) i wywołując [metodę Save](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) z plikiem wyjściowym i parametrami SaveFormat.OutputFormats.

{{% blocks/products/pf/feature-page-code h3="Kod konwersji C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Konwertuj pliki PowerPoint do formatu PDF" %}}

Konwersja programu Microsoft<sup>®</sup> PowerPoint do formatu PDF to typowy scenariusz ze względu na ogromne udostępnianie dokumentów PDF. Programiści mogą to zautomatyzować i ustawić odpowiednie ustawienia konwersji PDF za pomocą [klasy PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Kilka konkretnych ustawień, takich jak poziom kompresji tekstu, jakość JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), poziom zgodności PDF [Zgodność](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), konwertowanie ukrytych slajdów [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), wybrane slajdy i generowanie zablokowanych [hasła](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab4653900cc4598 chronionych plików PDF .

{{% blocks/products/pf/feature-page-code h3="Kod konwersji C++ PowerPoint do PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Zapisz slajdy programu Microsoft PowerPoint jako obrazy" %}}
zawsze, gdy zachodzi potrzeba wyświetlenia treści prezentacji w Internecie, należy renderować pliki jako HTML lub obrazy JPG, TIFF, PNG itp. Proces konwersji slajdów jako obrazów jest prosty. Pobierz wszystkie slajdy za pomocą [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) i powtarzaj każdy slajd jeden po drugim. Podczas każdej iteracji użyj [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) dla obrazu slajdu, a następnie zapisz w wymaganym formacie obrazu. 

{{% blocks/products/pf/feature-page-code h3="C++ Konwersja PowerPoint do obrazu" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}