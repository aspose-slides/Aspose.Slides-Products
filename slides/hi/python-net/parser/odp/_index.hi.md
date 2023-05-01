---
title: Python का इस्तेमाल करके ODP फ़ाइलों से टेक्स्ट और इमेज निकालें
url: /hi/python-net/parser/odp/
keywords: Python का उपयोग करके ODP को पार्स करें, ODP पार्सर Python, Python में ODP से डेटा निकालें, Python का उपयोग करके ODP से टेक्स्ट निकालें, Python का उपयोग करके ODP से चित्र निकालें
description: ODP प्रस्तुति को पार्स करने के लिए Python स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python का उपयोग करके ODP प्रस्तुतिकरण से पाठ और छवियां निकालें" h2="सर्वर-साइड API का उपयोग करके PowerPoint से पाठ, छवि, वीडियो और ऑडियो फ़ाइलें निकालने के लिए अपना स्वयं का Python एप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python के माध्यम से ODP प्रस्तुतिकरण से पाठ निकालें" %}}
संपूर्ण प्रस्तुति से पाठ को स्कैन करने के लिए, [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) स्थिर विधि का उपयोग करें, जिसे SlideUtil वर्ग द्वारा प्रदर्शित किया गया है। नीचे दिया गया कोड मास्टर स्लाइड सहित प्रस्तुति से पाठ और स्वरूपण जानकारी को स्कैन करता है।
{{% blocks/products/pf/agp/code-block title="Python का उपयोग करके ODP प्रस्तुतिकरण से टेक्स्ट निकाला जा रहा है" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="ODP से Python के ज़रिए टेक्स्ट कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये ODP फ़ाइलों को पार्स करने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ ODP लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP में सभी स्लाइड्स से टेक्स्टफ्रेम ऑब्जेक्ट्स की एक सरणी प्राप्त करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
TextFrames की सरणी के माध्यम से लूप करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
वर्तमान टेक्स्टफ्रेम में अनुच्छेदों के माध्यम से लूप करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
वर्तमान अनुच्छेद में भागों के माध्यम से लूप करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
वर्तमान भाग में पाठ प्राप्त करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित पार्स प्रारूप" subTitle="{Product_lang} का उपयोग करके, आप निम्न स्वरूपों को भी स्कैन कर सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}