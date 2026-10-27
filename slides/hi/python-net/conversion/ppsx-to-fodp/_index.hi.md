---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSX को Python में FODP में बदलें
weight: 2010
url: /hi/python-net/conversion/ppsx-to-fodp/ 
keywords: "Convert, PowerPoint, PPSX, FODP, Presentation, Python"
description: PPSX से FODP पायथन रूपांतरण के लिए नमूना कोड। PPSX फ़ाइलों को FODP फ़ाइलों में बैच रूपांतरण के लिए PowerPoint Python API का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSX को Python में FODP में बदलें" h2="PPSX को FODP में बदलने के लिए शक्तिशाली पॉवरपॉइंट पायथन लाइब्रेरी"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSX को Python में FODP में बदलें" %}}

PPSX फ़ाइलों को प्रोग्रामेटिक रूप से FODP में बदलने की आवश्यकता है? .NET*](https://products.aspose.com/slides/hi/python-net/) के माध्यम से पाइथॉन के लिए [*Aspose.Slides का उपयोग करके कोई भी डेवलपर PPSX को FODP फॉर्मेट में सिर्फ पायथन कोड की कुछ पंक्तियों के साथ बदल सकता है।

एक आधुनिक प्रेजेंटेशन प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for Python जल्दी से PPSX से FODP बनाता है। सीधे अपने [ब्राउज़र](https://products.aspose.app/slides/conversion) में PPSX से FODP रूपांतरण की गुणवत्ता का परीक्षण करें। Aspose PowerPoint PPTX लाइब्रेरी आपको PPSX फ़ाइलों को कई लोकप्रिय प्रारूपों में बदलने की अनुमति देती है।

आप निम्न पाइप कमांड का उपयोग करके [PyPI](https://pypi.org/project/Aspose.Slides/) से पुस्तकालय स्थापित कर सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कंसोल/टर्मिनल" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPSX को Python में FODP के रूप में सहेजें" %}}

PPSX से FODP रूपांतरण प्रक्रिया का प्रदर्शन देखने के लिए निःशुल्क ऐप का उपयोग करें।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड पीपीएसएक्स को एफओडीपी पायथन रूपांतरण दिखाता है" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsx") as presentation:
    presentation.save("presentation.fodp", slides.export.SaveFormat.FODP)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="पायथन में PPSX को FODP में कैसे बदलें" intro="ये PPSX फ़ाइल को Python का उपयोग करके FODP में बदलने के चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX फ़ाइल को प्रेजेंटेशन क्लास के उदाहरण के साथ लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat.FODP को पैरामीटर के रूप में निर्दिष्ट करते समय `सेव` विधि को कॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="पायथन रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- माइक्रोसॉफ्ट विंडोज या लिनक्स आधारित ओएस (देखें [अधिक](https://docs.aspose.com/slides/python-net/system-requirements/))।
- पायथन 3.5 या बाद में
- Aspose.Slides for Python आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides से निर्मित" title="PPSX को FODP में ऑनलाइन बदलें" description="मुफ़्त Aspose.Slides Conversion ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPSX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Conversion खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" upload="अपनी फ़ाइल छोड़ें या अपलोड करें" saveAs="इस रूप में सहेजें" convert="बदलें" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides फ़ाइलों को कैसे बदलता है।
- PPSX फ़ाइलें अपलोड करें और उन्हें FODP के रूप में सहेजें।
- परिणाम डाउनलोड करें या और फ़ाइलें बदलें।
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप PPSX को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं। अन्य समर्थित रूपांतरण नीचे देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="बिटमैप चित्र" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="जेपीईजी छवि" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument मानक प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-png/" name="PPSX TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="टैग की गई छवि प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
