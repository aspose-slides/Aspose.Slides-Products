---
title: जावा के माध्यम से PPSM को JPEG में बदलें
weight: 5070
url: /hi/java/conversion/ppsm-to-jpeg/ 
description: जेपीईजी फ़ाइल में पीपीएसएम प्रारूप के लिए नमूना जावा रूपांतरण कोड। किसी भी वेब या डेस्कटॉप जावा आधारित एप्लिकेशन के भीतर जेपीईजी को पावरपॉइंट और ओपनऑफिस प्रस्तुतियों को निर्यात करने के लिए इस उदाहरण कोड का उपयोग करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="जावा के माध्यम से PPSM को JPEG में बदलें" h2="PPSM से JPEG जावा रूपांतरण ऑन-प्रिमाइसेस जावा लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को JPEG में बदलने के लिए।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="जावा का उपयोग करके PPSM को JPEG में कैसे बदलें" %}}

 PPSM को JPEG में रेंडर करने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 एपीआई जो जावा प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण एपीआई है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
 [मेवेन](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने मावेन-आधारित प्रोजेक्ट में स्थापित करें।

{{% blocks/products/pf/agp/code-block title="कोष" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से PPSM को JPEG में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 जावा डेवलपर कोड की कुछ ही पंक्तियों में आसानी से PPSM फ़ाइल को JPEG में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. प्रस्तुति वर्ग के उदाहरण के साथ PPSM फ़ाइल लोड करें
1. प्रस्तुति में प्रत्येक स्लाइड के माध्यम से पुनरावृति
1. प्रत्येक पुनरावृत्ति के साथ बिटमैप के रूप में एक पूर्ण पैमाने की छवि बनाएं
1. JPEG फ़ाइल एक्सटेंशन और ImageFormat के साथ Bitmap.save विधि को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 जावा रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज या जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए जावा रनटाइम एनवायरनमेंट के साथ संगत ओएस।
- मावेन से सीधे जावा के लिए Aspose.Slides का नवीनतम संस्करण प्राप्त करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPSM से JPEG जावा रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// load PPSM with Aspose.Slides
Presentation presentation = new Presentation("template.ppsm");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type JPEG for every slide
  File outputfile = new File(sld.getSlideNumber() + ".jpeg");
  
  // save the slide image to disk
  ImageIO.write(bi, "jpeg", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="ppsm-to-jpeg"
        sectionTitle="मुफ्त ऐप PPSM को JPEG में कन्वर्ट करने के लिए" 
        sectionDescription="[PPT को JPG को रूपांतरित करने के लिए हमारे निःशुल्क ऐप को आज़माएं](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप PPSM को नीचे सूचीबद्ध कुछ सहित कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}