---
title: पायथन में POTX को PPSM में बदलें
weight: 1460
url: /hi/python-net/conversion/potx-to-ppsm/ 
keywords: "Convert, PowerPoint, POTX, PPSM, Presentation, Python"
description: POTX से PPSM पायथन रूपांतरण के लिए नमूना कोड। POTX फ़ाइलों को PPSM फ़ाइलों में बैच रूपांतरण के लिए PowerPoint Python API का उपयोग करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="पायथन में POTX को PPSM में बदलें" h2="POTX को PPSM में बदलने के लिए शक्तिशाली पावरपॉइंट पायथन लाइब्रेरी" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="पायथन में POTX को PPSM में बदलें" %}}

POTX फ़ाइलों को प्रोग्रामेटिक रूप से PPSM में बदलने की आवश्यकता है? .NET*](https://products.aspose.com/slides/python-net/) के माध्यम से [*Aspose.Slides for Python का उपयोग करके कोई भी डेवलपर POTX को PPSM प्रारूप में केवल कुछ पंक्तियों के साथ Python कोड में बदल सकता है।

एक आधुनिक प्रेजेंटेशन प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for Python जल्दी से POTX से PPSM बनाता है। अपने [ब्राउज़र](https://products.aspose.app/slides/conversion) में POTX से PPSM रूपांतरण की गुणवत्ता का परीक्षण करें। Aspose PowerPoint PPTX लाइब्रेरी आपको POTX फ़ाइलों को कई लोकप्रिय प्रारूपों में बदलने की अनुमति देती है।

आप निम्न पाइप कमांड का उपयोग करके [PyPI](https://pypi.org/project/Aspose.Slides/) से पुस्तकालय स्थापित कर सकते हैं:

{{% blocks/products/pf/agp/code-block title="कंसोल/टर्मिनल" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="पायथन में POTX को PPSM में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="पायथन का उपयोग करके POTX फ़ाइल को PPSM में बदलने के लिए ये चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति वर्ग के उदाहरण के साथ POTX फ़ाइल लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
आउटपुट फ़ाइल पथ और SaveFormat.PPSM को पैरामीटर के रूप में निर्दिष्ट करते समय `सहेजें` विधि को कॉल करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
POTX फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 पायथन रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस (देखें [अधिक](https://docs.aspose.com/slides/python-net/system-requirements/))।
- पायथन 3.5 या बाद में
- Aspose.Slides for Python आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड POTX को PPSM पायथन रूपांतरण दिखाता है" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potx") as presentation:
    presentation.save("presentation.ppsm", slides.export.SaveFormat.PPSM)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="पायथन में POTX को PPSM के रूप में सहेजें" %}}
POTX से PPSM रूपांतरण प्रक्रिया का प्रदर्शन देखने के लिए मुफ्त ऐप का उपयोग करें। 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="potx-to-ppsm"
        sectionTitle="मुफ्त ऐप POTX को PPSM में कन्वर्ट करने के लिए" 
        sectionDescription="[हमारी मुफ्त Video ऐप आज़माएं](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप POTX को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं। अन्य समर्थित रूपांतरण नीचे देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-bmp/" name="POTX TO BMP" description="बिटमैप चित्र" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-emf/" name="POTX TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-fodp/" name="POTX TO FODP" description="ओपन डॉक्यूमेंट फ्लैट एक्सएमएल प्रेजेंटेशन" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-gif/" name="POTX TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-html/" name="POTX TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-jpg/" name="POTX TO JPG" description="जेपीईजी छवि" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument मानक प्रारूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-pdf/" name="POTX TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-png/" name="POTX TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-pot/" name="POTX TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-potm/" name="POTX TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-pps/" name="POTX TO PPS" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-ppt/" name="POTX TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-pptm/" name="POTX TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-pptx/" name="POTX TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-svg/" name="POTX TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-swf/" name="POTX TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-tiff/" name="POTX TO TIFF" description="टैग की गई छवि प्रारूप" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/potx-to-xps/" name="POTX TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}