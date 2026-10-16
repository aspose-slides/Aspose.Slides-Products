---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावा के माध्यम से PPTM को POT में बदलें
weight: 7470
url: /hi/java/conversion/pptm-to-pot/ 
description: पीपीटीएम प्रारूप के लिए पीओटी फ़ाइल के लिए नमूना जावा रूपांतरण कोड। किसी भी वेब या डेस्कटॉप जावा आधारित एप्लिकेशन के भीतर पावरपॉइंट और ओपनऑफिस प्रस्तुतियों को पीओटी में निर्यात करने के लिए इस उदाहरण कोड का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावा के माध्यम से PPTM को POT में बदलें" h2="PPTM से POT जावा रूपांतरण ऑन-प्रिमाइसेस जावा लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को POT में बदलने के लिए।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा का उपयोग करके PPTM को POT में कैसे बदलें" %}}

PPTM को POT में रेंडर करने के लिए, हम उपयोग करेंगे
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM से POT जावा रूपांतरण स्रोत कोड" >}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("template.pptm");
// save the presentation as POT
presentation.save("output.pot", SaveFormat.Pot);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="जावा के माध्यम से PPTM को POT में बदलने के चरण" intro="जावा डेवलपर कोड की कुछ ही पंक्तियों में आसानी से PPTM फ़ाइल को POT में बदल सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ PPTM फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat निर्दिष्ट करते समय Presentation.save विधि को कॉल करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पीओटी फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="जावा रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- माइक्रोसॉफ्ट विंडोज या जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए जावा रनटाइम एनवायरनमेंट के साथ संगत ओएस।
- मावेन से सीधे जावा के लिए Aspose.Slides का नवीनतम संस्करण प्राप्त करें।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऐप PPTM को POT में कन्वर्ट करने के लिए"
  description="[हमारी मुफ्त Text To Gif ऐप आज़माएं](https://products.aspose.app/slides/text-to-gif/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप पीपीटीएम को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-html/" name="PPTM TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-png/" name="PPTM TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
