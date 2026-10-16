---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावा के माध्यम से OTP को PPSX में बदलें
weight: 2910
url: /hi/java/conversion/otp-to-ppsx/ 
description: PPSX फ़ाइल में OTP प्रारूप के लिए नमूना जावा रूपांतरण कोड। किसी भी वेब या डेस्कटॉप जावा आधारित एप्लिकेशन के भीतर PPSX को PowerPoint और OpenOffice प्रस्तुतियों को निर्यात करने के लिए इस उदाहरण कोड का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावा के माध्यम से OTP को PPSX में बदलें" h2="ऑन-प्रिमाइसेस जावा लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को PPSX में बदलने के लिए OTP से PPSX जावा रूपांतरण।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा का उपयोग करके OTP को PPSX में कैसे बदलें" %}}

PPSX को OTP प्रदान करने के लिए, हम उपयोग करेंगे
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP से PPSX जावा रूपांतरण स्रोत कोड" >}}
```cs
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("template.otp");
// save the presentation as PPSX
presentation.save("output.ppsx", SaveFormat.Ppsx);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="जावा के माध्यम से OTP को PPSX में बदलने के चरण" intro="जावा डेवलपर कोड की कुछ ही पंक्तियों में आसानी से OTP फ़ाइल को PPSX में बदल सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास के उदाहरण के साथ ओटीपी फाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat निर्दिष्ट करते समय Presentation.save विधि को कॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="जावा रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- माइक्रोसॉफ्ट विंडोज या जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए जावा रनटाइम एनवायरनमेंट के साथ संगत ओएस।
- मावेन से सीधे जावा के लिए Aspose.Slides का नवीनतम संस्करण प्राप्त करें।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऐप OTP को PPSX में कन्वर्ट करने के लिए"
  description="[हमारी मुफ्त Collage ऐप आज़माएं](https://products.aspose.app/slides/collage/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप नीचे सूचीबद्ध कुछ सहित ओटीपी को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-bmp/" name="OTP TO BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-gif/" name="OTP TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-html/" name="OTP TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-jpeg/" name="OTP TO JPEG" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-pdf/" name="OTP TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-png/" name="OTP TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-potx/" name="OTP TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-pps/" name="OTP TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-ppt/" name="OTP TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-svg/" name="OTP TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-swf/" name="OTP TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/otp-to-xps/" name="OTP TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
