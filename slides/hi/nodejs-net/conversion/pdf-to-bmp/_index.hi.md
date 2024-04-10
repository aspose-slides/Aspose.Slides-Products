---
title: जावास्क्रिप्ट में PDF को BMP में बदलें
url: /hi/nodejs-net/conversion/pdf-to-bmp/
keywords: PDF से BMP, PDF को BMP में बदलें, Node.js API, JavaScript लाइब्रेरी, PDF, BMP
description: जावास्क्रिप्ट में PDF को BMP में बदलें। PDF फ़ाइलों को BMP में बदलने के लिए Node.js लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जावास्क्रिप्ट में PDF को BMP में बदलें" h2=".NET के माध्यम से Node.js के लिए Aspose.Slides एक शक्तिशाली और उपयोग में आसान लाइब्रेरी है जो आपको PowerPoint प्रस्तुतियों को जावास्क्रिप्ट में विभिन्न प्रारूपों में परिवर्तित करने की अनुमति देती है। यह सभी प्रेजेंटेशन तत्वों और प्रारूपों का समर्थन करता है और उन तक पहुंचने और संशोधित करने के लिए एक समृद्ध एपीआई प्रदान करता है। यह आपको आगे की प्रक्रिया या साझा करने के लिए अपनी स्लाइड्स को विभिन्न प्रारूपों में निर्यात करने की भी अनुमति देता है।" >}}

{{% blocks/products/pf/feature-page-section h2="Node.js में PDF को BMP में बदलें" %}}

[**.NET के माध्यम से Node.js के लिए Aspose.Slides**](https://products.aspose.com/slides/hi/nodejs-net/) प्रेजेंटेशन फ़ाइलें बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली Node.js लाइब्रेरी है। इसके अलावा, यह PDF को BMP में बदलने के लचीले तरीके प्रदान करता है। .NET** के माध्यम से Node.js के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन कोड की कुछ पंक्तियों के साथ PDF को BMP फ़ाइलों में परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, .NET के माध्यम से Node.js के लिए Aspose.Slides PDF फ़ाइलों को BMP फ़ाइल स्वरूपों में शीघ्रता से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको PDF को BMPs और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावास्क्रिप्ट का उपयोग करके PDF को BMP में बदलें" %}}
PDF को BMP में बदलने के लिए, आपको PDF फ़ाइल से प्रेजेंटेशन बनाना होगा और इसे BMP के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="PDF को BMP में बदलने के लिए जावास्क्रिप्ट कोड" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके PDF को BMP में कैसे परिवर्तित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET के माध्यम से Node.js के लिए Aspose.Slides का उपयोग करके PDF को BMP में बदलने के लिए, आपको अपनी JavaScript फ़ाइल में पैकेज आयात करना होगा और प्रेजेंटेशन क्लास का एक उदाहरण बनाना होगा। प्रेजेंटेशन क्लास एक पावरपॉइंट दस्तावेज़ का प्रतिनिधित्व करता है और इसके तत्वों तक पहुंचने और हेरफेर करने के तरीके प्रदान करता है।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
.NET के माध्यम से Node.js के लिए [**Aspose.Slides स्थापित करें**](https://products.aspose.com/slides/hi/nodejs-net/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने Node.js प्रोजेक्ट में एक लाइब्रेरी संदर्भ जोड़ें (लाइब्रेरी आयात करें)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Node.js में स्रोत PDF फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को BMP फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PDF को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप PDF को कनवर्ट भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}