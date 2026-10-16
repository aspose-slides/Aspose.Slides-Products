---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावा के माध्यम से ODP को SVG में बदलें
weight: 8550
url: /hi/java/conversion/odp-to-svg/ 
description: SVG फ़ाइल में ODP प्रारूप के लिए नमूना जावा रूपांतरण कोड। किसी भी वेब या डेस्कटॉप जावा आधारित एप्लिकेशन के भीतर एसवीजी को पावरपॉइंट और ओपनऑफिस प्रस्तुतियों को निर्यात करने के लिए इस उदाहरण कोड का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावा के माध्यम से ODP को SVG में बदलें" h2="ऑन-प्रिमाइसेस जावा लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को एसवीजी में परिवर्तित करने के लिए ओडीपी से एसवीजी जावा रूपांतरण।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा का उपयोग करके ODP को SVG में कैसे बदलें" %}}

SVG को ODP रेंडर करने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/)
 एपीआई जो जावा प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण एपीआई है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
 [मेवेन](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने मावेन-आधारित प्रोजेक्ट में स्थापित करें।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कोष" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="निर्भरता" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP से SVG जावा रूपांतरण स्रोत कोड" >}}
```cs
// instantiate a Presentation object that represents a ODP file
Presentation pres = new Presentation("template.odp");
try {
    // Access the first slide
    ISlide sld = pres.getSlides().get_Item(0);

    // Create a memory stream object
    FileOutputStream svgStream = new FileOutputStream("output.svg");

    // Create SVG image of slide and save in memory stream
    sld.writeAsSvg(svgStream);

    svgStream.close();
} catch (IOException e) {
} finally {
    pres.dispose();
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="जावा के माध्यम से ODP को SVG में बदलने के चरण" intro="जावा डेवलपर कोड की कुछ ही पंक्तियों में आसानी से ODP फ़ाइल को SVG में बदल सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ ODP फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat निर्दिष्ट करते समय Presentation.save विधि को कॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एसवीजी फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="जावा रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- माइक्रोसॉफ्ट विंडोज या जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए जावा रनटाइम एनवायरनमेंट के साथ संगत ओएस।
- मावेन से सीधे जावा के लिए Aspose.Slides का नवीनतम संस्करण प्राप्त करें।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension="odp-to-svg"
  title="मुफ्त ऐप ODP को SVG में कन्वर्ट करने के लिए"
  description="[हमारी मुफ्त Editor ऐप आज़माएं](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप नीचे सूचीबद्ध कुछ सहित ओडीपी को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-gif/" name="ODP TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-html/" name="ODP TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-png/" name="ODP TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-potx/" name="ODP TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-pps/" name="ODP TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-swf/" name="ODP TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/odp-to-xps/" name="ODP TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
