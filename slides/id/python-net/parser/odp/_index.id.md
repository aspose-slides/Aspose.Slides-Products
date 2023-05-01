---
title: Ekstrak Teks dan Gambar dari File ODP menggunakan Python
url: /id/python-net/parser/odp/
keywords: parse ODP menggunakan Python, ODP parser Python, ekstrak data dari ODP dalam Python, ekstrak teks dari ODP menggunakan Python, ekstrak gambar dari ODP menggunakan Python
description: Kode sumber Python untuk mengurai Presentasi ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ekstrak Teks dan Gambar dari presentasi ODP menggunakan Python" h2="Bangun aplikasi Python Anda sendiri untuk mengekstrak file teks, gambar, video, dan audio dari PowerPoint menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ekstrak Teks dari Presentasi ODP melalui Python" %}}
Untuk memindai teks dari seluruh presentasi, gunakan metode statis [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) yang diekspos oleh kelas SlideUtil. Kode di bawah memindai teks dan memformat informasi dari presentasi, termasuk slide master.
{{% blocks/products/pf/agp/code-block title="Mengekstrak Teks dari Presentasi ODP menggunakan Python" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Cara Mengekstrak Teks dari ODP melalui Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mengurai file ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat ODP dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dapatkan Array objek TextFrame dari semua slide di ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi Array dari TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi paragraf dalam TextFrame saat ini
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ulangi bagian-bagian dalam Paragraf saat ini
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Dapatkan teks di bagian saat ini
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Parse Lain yang Didukung" subTitle="Menggunakan Python, Anda juga dapat memindai format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}