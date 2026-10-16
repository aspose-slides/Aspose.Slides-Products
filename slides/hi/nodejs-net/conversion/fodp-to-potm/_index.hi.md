---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावास्क्रिप्ट में FODP को POTM में बदलें
url: /hi/nodejs-net/conversion/fodp-to-potm/
keywords: FODP से POTM, FODP को POTM में बदलें, Node.js API, JavaScript लाइब्रेरी, FODP, POTM
description: जावास्क्रिप्ट में FODP को POTM में बदलें। FODP फ़ाइलों को POTM में बदलने के लिए Node.js लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावास्क्रिप्ट में FODP को POTM में बदलें" h2=".NET के माध्यम से Node.js के लिए Aspose.Slides एक शक्तिशाली और उपयोग में आसान लाइब्रेरी है जो आपको PowerPoint प्रस्तुतियों को जावास्क्रिप्ट में विभिन्न प्रारूपों में परिवर्तित करने की अनुमति देती है। यह सभी प्रेजेंटेशन तत्वों और प्रारूपों का समर्थन करता है और उन तक पहुंचने और संशोधित करने के लिए एक समृद्ध एपीआई प्रदान करता है। यह आपको आगे की प्रक्रिया या साझा करने के लिए अपनी स्लाइड्स को विभिन्न प्रारूपों में निर्यात करने की भी अनुमति देता है।" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावास्क्रिप्ट का उपयोग करके FODP को POTM में बदलें" variant="code" %}}

FODP को POTM में बदलने के लिए, आपको FODP फ़ाइल से प्रेजेंटेशन बनाना होगा और इसे POTM के रूप में सहेजना होगा।

{{< blocks/products/pf/slides-design-update-10-2026/code title="FODP को POTM में बदलने के लिए जावास्क्रिप्ट कोड" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.fodp");
try
{
    pres.save("output.potm", SaveFormat.Potm);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Node.js में FODP को POTM में बदलें" %}}

[**.NET के माध्यम से Node.js के लिए Aspose.Slides**](https://products.aspose.com/slides/hi/nodejs-net/) प्रेजेंटेशन फ़ाइलें बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली Node.js लाइब्रेरी है। इसके अलावा, यह FODP को POTM में बदलने के लचीले तरीके प्रदान करता है। .NET** के माध्यम से Node.js के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन कोड की कुछ पंक्तियों के साथ FODP को POTM फ़ाइलों में परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, .NET के माध्यम से Node.js के लिए Aspose.Slides FODP फ़ाइलों को POTM फ़ाइल स्वरूपों में शीघ्रता से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको FODP को POTMs और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title=".NET API के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके FODP को POTM में कैसे परिवर्तित करें" intro=".NET के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके FODP को POTM में बदलने के लिए, आपको अपनी JavaScript फ़ाइल में पैकेज आयात करना होगा और प्रेजेंटेशन क्लास का एक उदाहरण बनाना होगा। प्रेजेंटेशन क्लास एक पावरपॉइंट दस्तावेज़ का प्रतिनिधित्व करता है और इसके तत्वों तक पहुंचने और हेरफेर करने के तरीके प्रदान करता है।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}.NET के माध्यम से Node.js के लिए [**Aspose.Slides स्थापित करें**](https://products.aspose.com/slides/hi/nodejs-net/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपने Node.js प्रोजेक्ट में एक लाइब्रेरी संदर्भ जोड़ें (लाइब्रेरी आयात करें)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Node.js में स्रोत FODP फ़ाइलें खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणाम को POTM फ़ाइल के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="FODP को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप FODP को कनवर्ट भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/nodejs-net/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
