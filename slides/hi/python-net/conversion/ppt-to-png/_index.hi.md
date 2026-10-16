---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT को Python में PNG में बदलें
weight: 2300
url: /hi/python-net/conversion/ppt-to-png/ 
keywords: "Convert, PowerPoint, PPT, PNG, Presentation, Python"
description: पीपीटी से पीएनजी पायथन रूपांतरण के लिए नमूना कोड। PPT फ़ाइलों को PNG फ़ाइलों में बैच रूपांतरण के लिए PowerPoint Python API का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT को Python में PNG में बदलें" h2="पीपीटी को पीएनजी में परिवर्तित करने के लिए शक्तिशाली पावरपॉइंट पायथन पुस्तकालय"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT को Python में PNG में बदलें" %}}

PPT फ़ाइलों को प्रोग्रामेटिक रूप से PNG में बदलने की आवश्यकता है? .NET*](https://products.aspose.com/slides/hi/python-net/) के माध्यम से पाइथॉन के लिए [*Aspose.Slides का उपयोग करके कोई भी डेवलपर PPT को PNG प्रारूप में केवल कुछ पंक्तियों में Python कोड के साथ परिवर्तित कर सकता है।

एक आधुनिक प्रस्तुति प्रसंस्करण API के रूप में, Aspose.Slides for Python जल्दी से PPT से PNG बनाता है। सीधे अपने [ब्राउज़र](https://products.aspose.app/slides/conversion/ppt-to-png) में PPT से PNG रूपांतरण की गुणवत्ता का परीक्षण करें। एस्पोज पॉवरपॉइंट पीपीटीएक्स लाइब्रेरी आपको पीपीटी फाइलों को कई लोकप्रिय प्रारूपों में बदलने की अनुमति देती है।

आप निम्न पाइप कमांड का उपयोग करके [PyPI](https://pypi.org/project/Aspose.Slides/) से पुस्तकालय स्थापित कर सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कंसोल/टर्मिनल" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT को Python में PNG के रूप में सहेजें" %}}

पीपीटी से पीएनजी रूपांतरण प्रक्रिया का प्रदर्शन देखने के लिए मुफ्त ऐप का उपयोग करें।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड पीपीटी को पीएनजी पायथन रूपांतरण में दिखाता है" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="पायथन में पीपीटी को पीएनजी में कैसे बदलें" intro="पायथन का उपयोग करके पीपीटी फ़ाइल को पीएनजी में बदलने के लिए ये चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास के उदाहरण के साथ पीपीटी फाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat.PNG को पैरामीटर के रूप में निर्दिष्ट करते समय `सहेजें` विधि को कॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पीपीटी फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="पायथन रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस (देखें [अधिक](https://docs.aspose.com/slides/python-net/system-requirements/))।
- पायथन 3.5 या बाद में
- Aspose.Slides for Python आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="ppt-to-png"
  title="मुफ्त ऐप PPT को PNG में कन्वर्ट करने के लिए"
  description="[PPT को PNG को रूपांतरित करने के लिए हमारे निःशुल्क ऐप को आज़माएं](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप पीपीटी को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं। अन्य समर्थित रूपांतरण नीचे देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="बिटमैप चित्र" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-emf/" name="PPT TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-fodp/" name="PPT TO FODP" description="ओपन डॉक्यूमेंट फ्लैट एक्सएमएल प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-gif/" name="PPT TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/" name="PPT TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-jpg/" name="PPT TO JPG" description="जेपीईजी छवि" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument मानक प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-potx/" name="PPT TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-pps/" name="PPT TO PPS" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-svg/" name="PPT TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-swf/" name="PPT TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="टैग की गई छवि प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-xps/" name="PPT TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
