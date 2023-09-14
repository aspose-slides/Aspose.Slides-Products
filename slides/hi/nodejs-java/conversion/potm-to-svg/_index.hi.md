---
title: Node.js में POTM को SVG में बदलें
url: /hi/nodejs-java/conversion/potm-to-svg/
keywords: POTM से SVG, POTM को SVG में बदलें, Node.js API, Node.js लाइब्रेरी, POTM, SVG
description: Node.js में POTM को SVG में बदलें। POTM फ़ाइलों को SVGs में बदलने के लिए Node.js लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Node.js में POTM को SVG में बदलें" h2="जावा के माध्यम से Node.js के लिए Aspose.Slides एक शक्तिशाली और उपयोग में आसान लाइब्रेरी है जो आपको PowerPoint प्रस्तुतियों को Node.js में विभिन्न प्रारूपों में परिवर्तित करने की अनुमति देती है। यह सभी प्रेजेंटेशन तत्वों और प्रारूपों का समर्थन करता है और उन तक पहुंचने और संशोधित करने के लिए एक समृद्ध एपीआई प्रदान करता है। यह आपको आगे की प्रक्रिया या साझा करने के लिए अपनी स्लाइड्स को विभिन्न प्रारूपों में निर्यात करने की भी अनुमति देता है।" >}}

{{% blocks/products/pf/feature-page-section h2="Node.js में POTM को SVG में बदलें" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/hi/nodejs-java/) प्रेजेंटेशन फ़ाइलें बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली Node.js लाइब्रेरी है। इसके अलावा, यह POTM को SVG में बदलने के लचीले तरीके प्रदान करता है। Java** के माध्यम से Node.js के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन कोड की कुछ पंक्तियों के साथ POTM को SVG फ़ाइलों में परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, Node.js के लिए Aspose.Slides POTM फ़ाइलों को SVG फ़ाइल स्वरूपों में शीघ्रता से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको POTM को SVGs और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Node.js का उपयोग करके POTM को SVG में बदलें" %}}
POTM को SVG में बदलने के लिए, आपको POTM फ़ाइल से प्रेजेंटेशन बनाना होगा और इसे SVG के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="POTM को SVG में बदलने के लिए Node.js कोड" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potm");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="जावा एपीआई के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके POTM को SVG में कैसे परिवर्तित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="जावा के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके POTM को SVG में बदलने के लिए, आपको अपनी जावास्क्रिप्ट फ़ाइल में पैकेज आयात करना होगा और प्रेजेंटेशन क्लास का एक उदाहरण बनाना होगा। प्रेजेंटेशन क्लास एक पावरपॉइंट दस्तावेज़ का प्रतिनिधित्व करता है और इसके तत्वों तक पहुंचने और हेरफेर करने के तरीके प्रदान करता है।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
जावा के माध्यम से Node.js के लिए [**Aspose.Slides स्थापित करें**](https://products.aspose.com/slides/hi/nodejs-java/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने Node.js प्रोजेक्ट में एक लाइब्रेरी संदर्भ जोड़ें (लाइब्रेरी आयात करें)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js में स्रोत POTM फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को SVG फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="POTM को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप POTM को कनवर्ट भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-java/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}