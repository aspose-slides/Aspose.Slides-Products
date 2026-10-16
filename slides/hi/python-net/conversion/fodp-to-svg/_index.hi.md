---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: पायथन में FODP को SVG में बदलें
weight: 190
url: /hi/python-net/conversion/fodp-to-svg/ 
keywords: "Convert, PowerPoint, FODP, SVG, Presentation, Python"
description: एफओडीपी के लिए एसवीजी पायथन रूपांतरण के लिए नमूना कोड। FODP फ़ाइलों को SVG फ़ाइलों में बैच रूपांतरण के लिए PowerPoint Python API का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="पायथन में FODP को SVG में बदलें" h2="एफओडीपी को एसवीजी में परिवर्तित करने के लिए शक्तिशाली पावरपॉइंट पायथन पुस्तकालय"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="पायथन में FODP को SVG में बदलें" %}}

एफओडीपी फाइलों को प्रोग्रामेटिक रूप से एसवीजी में बदलने की जरूरत है? .NET*](https://products.aspose.com/slides/hi/python-net/) के माध्यम से पाइथॉन के लिए [*Aspose.Slides का उपयोग करके कोई भी डेवलपर FODP को SVG प्रारूप में केवल कुछ पंक्तियों के साथ पायथन कोड में बदल सकता है।

एक आधुनिक प्रेजेंटेशन प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for Python जल्दी से FODP से SVG बनाता है। सीधे अपने [ब्राउज़र](https://products.aspose.app/slides/conversion) में FODP से SVG रूपांतरण की गुणवत्ता का परीक्षण करें। Aspose PowerPoint PPTX लाइब्रेरी आपको FODP फ़ाइलों को कई लोकप्रिय प्रारूपों में बदलने की अनुमति देती है।

आप निम्न पाइप कमांड का उपयोग करके [PyPI](https://pypi.org/project/Aspose.Slides/) से पुस्तकालय स्थापित कर सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कंसोल/टर्मिनल" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="FODP को Python में SVG के रूप में सहेजें" %}}

एफओडीपी से एसवीजी रूपांतरण प्रक्रिया का प्रदर्शन देखने के लिए मुफ्त ऐप का उपयोग करें।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड FODP को SVG पायथन रूपांतरण में दिखाता है" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.fodp") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="पायथन में FODP को SVG में कैसे बदलें" intro="पायथन का उपयोग करके FODP फ़ाइल को SVG में बदलने के लिए ये चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ FODP फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat.SVG को पैरामीटर के रूप में निर्दिष्ट करते समय `सहेजें` विधि को कॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FODP फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="पायथन रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस (देखें [अधिक](https://docs.aspose.com/slides/python-net/system-requirements/))।
- पायथन 3.5 या बाद में
- Aspose.Slides for Python आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऐप FODP को SVG में कन्वर्ट करने के लिए"
  description="[हमारी मुफ्त Video ऐप आज़माएं](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप FODP को कई अन्य फ़ाइल स्वरूपों में भी बदल सकते हैं। अन्य समर्थित रूपांतरण नीचे देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-bmp/" name="FODP TO BMP" description="बिटमैप चित्र" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-emf/" name="FODP TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-gif/" name="FODP TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-html/" name="FODP TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-jpg/" name="FODP TO JPG" description="जेपीईजी छवि" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument मानक प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-pdf/" name="FODP TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-png/" name="FODP TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-potx/" name="FODP TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-pps/" name="FODP TO PPS" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-ppt/" name="FODP TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-swf/" name="FODP TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="टैग की गई छवि प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/fodp-to-xps/" name="FODP TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
