---
title: Python kullanarak ODP Dosyalarından Metin ve Görüntüleri Çıkarın
url: /tr/python-net/parser/odp/
keywords: Python kullanarak ODP ayrıştırma, ODP Python ayrıştırıcı, Python içindeki ODP'dan veri çıkarma, Python kullanarak ODP'dan metin çıkarma, Python kullanarak ODP'dan görsel çıkarma
description: ODP Sunumunu ayrıştırmak için Python kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python kullanarak ODP sunumundan Metin ve Resimleri Çıkarın" h2="Sunucu tarafı API'lerini kullanarak PowerPoint'ten metin, resim, video ve ses dosyalarını ayıklamak için kendi Python uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python aracılığıyla ODP Sunumundan Metin Çıkarın" %}}
Metni sununun tamamından taramak için SlideUtil sınıfı tarafından sunulan [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) statik yöntemini kullanın. Aşağıdaki kod, ana slaytlar da dahil olmak üzere bir sunudaki metni ve biçimlendirme bilgilerini tarar.
{{% blocks/products/pf/agp/code-block title="Python Kullanarak ODP Sunumundan Metin Çıkarma" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a ODP file
with slides.Presentation("pres.odp") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the ODP
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python aracılığıyla ODP'dan Metin Çıkarma" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, ODP dosyalarını Ayrıştırma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP içindeki tüm slaytlardan bir dizi TextFrame nesnesi alın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
TextFrames Dizisinde Döngü
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Geçerli TextFrame'deki paragraflar arasında geçiş yapın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Geçerli Paragraftaki bölümler arasında geçiş yapın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Geçerli kısımda metni al
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Ayrıştırma Biçimleri" subTitle="Python kullanarak aşağıdaki biçimleri de tarayabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}