---
title: जावास्क्रिप्ट में ODP को PNG में बदलें
url: /hi/nodejs-net/conversion/odp-to-png/
keywords: ODP से PNG, ODP को PNG में बदलें, Node.js API, JavaScript लाइब्रेरी, ODP, PNG
description: जावास्क्रिप्ट में ODP को PNG में बदलें। ODP फ़ाइलों को PNG में बदलने के लिए Node.js लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जावास्क्रिप्ट में ODP को PNG में बदलें" h2=".NET के माध्यम से Node.js के लिए Aspose.Slides एक शक्तिशाली और उपयोग में आसान लाइब्रेरी है जो आपको PowerPoint प्रस्तुतियों को जावास्क्रिप्ट में विभिन्न प्रारूपों में परिवर्तित करने की अनुमति देती है। यह सभी प्रेजेंटेशन तत्वों और प्रारूपों का समर्थन करता है और उन तक पहुंचने और संशोधित करने के लिए एक समृद्ध एपीआई प्रदान करता है। यह आपको आगे की प्रक्रिया या साझा करने के लिए अपनी स्लाइड्स को विभिन्न प्रारूपों में निर्यात करने की भी अनुमति देता है।" >}}

{{% blocks/products/pf/feature-page-section h2="Node.js में ODP को PNG में बदलें" %}}

[**.NET के माध्यम से Node.js के लिए Aspose.Slides**](https://products.aspose.com/slides/hi/nodejs-net/) प्रेजेंटेशन फ़ाइलें बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली Node.js लाइब्रेरी है। इसके अलावा, यह ODP को PNG में बदलने के लचीले तरीके प्रदान करता है। .NET** के माध्यम से Node.js के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन कोड की कुछ पंक्तियों के साथ ODP को PNG फ़ाइलों में परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, .NET के माध्यम से Node.js के लिए Aspose.Slides ODP फ़ाइलों को PNG फ़ाइल स्वरूपों में शीघ्रता से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको ODP को PNGs और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावास्क्रिप्ट का उपयोग करके ODP को PNG में बदलें" %}}
ODP को PNG में बदलने के लिए, आपको ODP फ़ाइल से प्रेजेंटेशन बनाना होगा और इसे PNG के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="ODP को PNG में बदलने के लिए जावास्क्रिप्ट कोड" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.odp");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".png", ImageFormat.Png); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके ODP को PNG में कैसे परिवर्तित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके ODP को PNG में बदलने के लिए, आपको अपनी JavaScript फ़ाइल में पैकेज आयात करना होगा और प्रेजेंटेशन क्लास का एक उदाहरण बनाना होगा। प्रेजेंटेशन क्लास एक पावरपॉइंट दस्तावेज़ का प्रतिनिधित्व करता है और इसके तत्वों तक पहुंचने और हेरफेर करने के तरीके प्रदान करता है।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
.NET के माध्यम से Node.js के लिए [**Aspose.Slides स्थापित करें**](https://products.aspose.com/slides/hi/nodejs-net/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने Node.js प्रोजेक्ट में एक लाइब्रेरी संदर्भ जोड़ें (लाइब्रेरी आयात करें)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js में स्रोत ODP फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को PNG फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="ODP को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप ODP को कनवर्ट भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}