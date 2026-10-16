---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावास्क्रिप्ट में POTM को SVG में बदलें
url: /hi/nodejs-net/conversion/potm-to-svg/
keywords: POTM से SVG, POTM को SVG में बदलें, Node.js API, JavaScript लाइब्रेरी, POTM, SVG
description: जावास्क्रिप्ट में POTM को SVG में बदलें। POTM फ़ाइलों को SVG में बदलने के लिए Node.js लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावास्क्रिप्ट में POTM को SVG में बदलें" h2=".NET के माध्यम से Node.js के लिए Aspose.Slides एक शक्तिशाली और उपयोग में आसान लाइब्रेरी है जो आपको PowerPoint प्रस्तुतियों को जावास्क्रिप्ट में विभिन्न प्रारूपों में परिवर्तित करने की अनुमति देती है। यह सभी प्रेजेंटेशन तत्वों और प्रारूपों का समर्थन करता है और उन तक पहुंचने और संशोधित करने के लिए एक समृद्ध एपीआई प्रदान करता है। यह आपको आगे की प्रक्रिया या साझा करने के लिए अपनी स्लाइड्स को विभिन्न प्रारूपों में निर्यात करने की भी अनुमति देता है।" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावास्क्रिप्ट का उपयोग करके POTM को SVG में बदलें" variant="code" %}}

POTM को SVG में बदलने के लिए, आपको POTM फ़ाइल से प्रेजेंटेशन बनाना होगा और इसे SVG के रूप में सहेजना होगा।

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM को SVG में बदलने के लिए जावास्क्रिप्ट कोड" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potm");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js में POTM को SVG में बदलें" %}}

[**.NET के माध्यम से Node.js के लिए Aspose.Slides**](https://products.aspose.com/slides/hi/nodejs-net/) प्रेजेंटेशन फ़ाइलें बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली Node.js लाइब्रेरी है। इसके अलावा, यह POTM को SVG में बदलने के लचीले तरीके प्रदान करता है। .NET** के माध्यम से Node.js के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन कोड की कुछ पंक्तियों के साथ POTM को SVG फ़ाइलों में परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, .NET के माध्यम से Node.js के लिए Aspose.Slides POTM फ़ाइलों को SVG फ़ाइल स्वरूपों में शीघ्रता से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको POTM को SVGs और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके POTM को SVG में कैसे परिवर्तित करें" intro=".NET के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके POTM को SVG में बदलने के लिए, आपको अपनी JavaScript फ़ाइल में पैकेज आयात करना होगा और प्रेजेंटेशन क्लास का एक उदाहरण बनाना होगा। प्रेजेंटेशन क्लास एक पावरपॉइंट दस्तावेज़ का प्रतिनिधित्व करता है और इसके तत्वों तक पहुंचने और हेरफेर करने के तरीके प्रदान करता है।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}.NET के माध्यम से Node.js के लिए [**Aspose.Slides स्थापित करें**](https://products.aspose.com/slides/hi/nodejs-net/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपने Node.js प्रोजेक्ट में एक लाइब्रेरी संदर्भ जोड़ें (लाइब्रेरी आयात करें)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js में स्रोत POTM फ़ाइलें खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणाम को SVG फ़ाइल के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="POTM को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप POTM को कनवर्ट भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-bmp/" name="POTM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
