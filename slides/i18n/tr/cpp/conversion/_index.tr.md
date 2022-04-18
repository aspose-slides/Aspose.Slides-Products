---
title: Microsoft PowerPoint Sunumunu C++ Kullanarak Çeşitli Biçimlere Dönüştürme
url: /tr/cpp/conversion/
description: Microsoft PowerPoint Slaytlarını, C++ tabanlı uygulamalarda HTML, PDF ve görüntü formatları dahil olmak üzere birden çok dosyaya dönüştürün.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++ ile Microsoft<sup>®</sup> PowerPoint Sunum Dönüşümü" h2="Slaytları Görüntüler, HTML, PDF ve diğer biçimlere dönüştürmek için farklı dönüştürme senaryoları için C++ örnek kodları." >}}

{{% blocks/products/pf/feature-page-summary %}}

Microsoft<sup>®</sup> PowerPoint biçimlerinin dönüştürme işlemi basit ve C++ PowerPoint kitaplığını kullanarak işlemleri otomatikleştirmek kolaydır. Geliştiriciler, ilgili kaynak kodunu geliştirebilir ve uygulamalarına entegre edebilir. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint Formatlarının Ara Dönüşümü" %}}
PPT, PPTX dahil olmak üzere Microsoft<sup>®</sup> PowerPoint belgelerinin programlı olarak birbirine dönüştürülmesi sadece iki satırlık bir koddur. [Sunum sınıfını](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) kullanarak ve [Kaydetme yöntemini](https://apireference.aspose.com/slides) çağırarak dosyayı yükleyin /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) çıktı dosyasına ve parametre olarak SaveFormat.OutputFormats'a sahip.

{{% blocks/products/pf/feature-page-code h3="C++ Dönüşüm Kodu" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint Dosyalarını PDF'ye Dönüştür" %}}

Microsoft<sup>®</sup> PowerPoint'i PDF'ye dönüştürmek, PDF belgelerinin büyük ölçüde paylaşılması nedeniyle yaygın bir senaryodur. Programcılar [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) kullanarak bunu otomatikleştirebilir ve ilgili PDF dönüştürme ayarlarını yapabilir. Metin sıkıştırma düzeyi, JPEG kalitesi [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), PDF uyumluluk düzeyi [Uyum] gibi belirli ayarlardan birkaçı (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), gizli slaytları dönüştürme [ShowHiddenSlides](https://apireference.aspose.com/pp/classes) /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), seçili slaytlar ve kilitli [Parola] oluşturma (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab983afe00d91)protected PDF_options#ab983afe600d91 .

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint'ten PDF'ye Dönüştürme Kodu" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint Slaytlarını Görüntü Olarak Kaydet" %}}
Sunum içeriğini web'de görüntülemek için bir durum olduğunda, dosyaları HTML veya JPG, TIFF, PNG, vb. olarak işlemek gerekir. Slaytları resim olarak dönüştürme işlemi basittir. [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) kullanarak tüm slaytları alın ve her slaytta tek tek yineleyin. Her yineleme sırasında slayt görüntüsü için [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) kullanın ve ardından gerekli görüntü formatına kaydedin. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint'ten Görüntüye Dönüştürme" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}