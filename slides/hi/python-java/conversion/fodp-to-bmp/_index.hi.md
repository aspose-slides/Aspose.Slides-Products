---
title: पायथन में FODP को BMP में बदलें
url: /hi/python-java/conversion/fodp-to-bmp/
keywords: पायथन प्रस्तुति रूपांतरण, प्रस्तुतियों को पायथन में परिवर्तित करें, प्रस्तुतियों के लिए पायथन, Aspose.Slides Python, FODP से BMP रूपांतरण, पायथन प्रस्तुति लाइब्रेरी
description: पायथन में FODP को BMP में बदलें। FODP फ़ाइलों को BMP में बदलने के लिए पायथन लाइब्रेरी एपीआई का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पाइथॉन के साथ आसानी से FODP को BMP में कनवर्ट करें: Aspose.Slides टू द रेस्क्यू!" h2="पायथन के साथ अपनी प्रस्तुतियों में नई जान फूंकें। हमारा गाइड आपको मौजूदा पावरपॉइंट स्लाइड्स को आकर्षक पायथन प्रस्तुतियों में परिवर्तित करने के बारे में बताता है।" >}}

{{% blocks/products/pf/feature-page-section h2="पायथन में FODP को BMP में बदलें" %}}

क्या आप जटिल प्रेजेंटेशन सॉफ़्टवेयर से जूझने से थक गए हैं? [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/hi/python-java/) से आगे न देखें! यह शक्तिशाली लाइब्रेरी आपको आसानी से विभिन्न प्रारूपों के बीच प्रस्तुतियाँ बनाने, संपादित करने और परिवर्तित करने में सक्षम बनाती है। FODP से BMP पर स्विच करने की आवश्यकता है? Aspose.Slides इसे आसान बनाता है, इसके लिए केवल Python कोड की कुछ पंक्तियों की आवश्यकता होती है।

एक अत्याधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, **Aspose.Slides for Python via Java** बिजली की तेज़ रूपांतरण गति का दावा करता है, जो आपके FODP प्रस्तुतियों को BMP प्रारूप में तेजी से परिवर्तन सुनिश्चित करता है। पारंपरिक उपकरणों की सीमाओं को त्यागें - Aspose.Slides आपको प्रस्तुतियों को न केवल FODP से BMP में, बल्कि अन्य प्रारूपों की एक विस्तृत श्रृंखला में परिवर्तित करने की सुविधा देता है, जो आपको किसी भी स्थिति के लिए अपनी प्रस्तुतियों को दोषरहित रूप से अनुकूलित करने के लिए सशक्त बनाता है।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="पायथन का उपयोग करके FODP को BMP में बदलें" %}}
FODP को BMP में बदलने के लिए, आपको FODP फ़ाइल से प्रेजेंटेशन बनाना होगा और इसे BMP के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="FODP को BMP में बदलने के लिए पायथन ट्यूटोरियल" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.fodp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="पायथन ट्यूटोरियल। जावा एपीआई के माध्यम से पायथन के लिए Aspose.Slides का उपयोग करके FODP को BMP में कैसे परिवर्तित करें।" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="जावा के माध्यम से पायथन के लिए Aspose.Slides का उपयोग करके FODP को BMP में बदलने के लिए, आपको पैकेज को अपनी पायथन स्क्रिप्ट में आयात करना होगा और प्रेजेंटेशन क्लास का एक उदाहरण बनाना होगा। प्रेजेंटेशन क्लास एक पावरपॉइंट दस्तावेज़ का प्रतिनिधित्व करता है और इसके तत्वों तक पहुंचने और हेरफेर करने के तरीके प्रदान करता है।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**जावा के माध्यम से पायथन के लिए Aspose.Slides**](https://products.aspose.com/slides/hi/python-java/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने पायथन प्रोजेक्ट में एक लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पायथन में स्रोत FODP फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को BMP फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप FODP को कनवर्ट भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}