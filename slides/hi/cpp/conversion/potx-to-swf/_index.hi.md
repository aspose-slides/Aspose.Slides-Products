---
title: C++ एप्लिकेशन के माध्यम से POTX को SWF में बदलें
url: /hi/cpp/conversion/potx-to-swf/ 
description: POTX दस्तावेज़ के लिए SWF प्रारूप में नमूना C++ रूपांतरण कोड। किसी भी सी++ एप्लिकेशन में बैच POTX से SWF रूपांतरण के लिए उदाहरण कोड का उपयोग करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="POTX को C++ के माध्यम से SWF में बदलें" h2="Microsoft PowerPoint स्थापना की आवश्यकता के बिना C++ लाइब्रेरी का उपयोग करके उच्च प्रदर्शन POTX से SWF रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SWF" pfName="Aspose.SLIDES" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="SLIDES" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.SLIDES " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके POTX को SWF में कैसे बदलें?" %}}

POTX को SWF में बदलने के लिए, हम <a href="https://products.aspose.com/slides/cpp">Aspose.Slides for C++</a> API का उपयोग करेंगे जो एक सुविधा संपन्न, शक्तिशाली है और सी ++ प्लेटफॉर्म के लिए दस्तावेज़ हेरफेर और रूपांतरण एपीआई का उपयोग करना आसान है। आप इसका नवीनतम संस्करण सीधे डाउनलोड कर सकते हैं, बस <a href="https://www.nuget.org/packages/aspose.slides">NuGet</a> पैकेज मैनेजर खोलें, <b>Aspose.Slides.Cpp खोजें। </b> और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.SLIDES.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="POTX को C++ के माध्यम से SWF में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.SLIDES API डेवलपर्स के लिए POTX फ़ाइल को SWF में कोड की कुछ ही पंक्तियों में कनवर्ट करना आसान बनाता है।

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Slides के साथ C++ प्रेजेंटेशन ऑब्जेक्ट के साथ POTX फ़ाइल लोड करें।
1. सेव () विधि को कॉल करें।
1. आउटपुट फ़ाइल पथ को (SWF) फ़ाइल एक्सटेंशन के साथ पास करें।
1. SWF फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी।
1. संगत प्रोग्राम में SWF फ़ाइल खोलें।



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.SLIDES for C++ सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर सपोर्ट करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज या विंडोज 32 बिट, विंडोज 64 बिट और लिनक्स 64 बिट के लिए सी ++ रनटाइम एनवायरनमेंट के साथ संगत ओएस।
- Aspose.Slides for C++ DLL आपके प्रोजेक्ट में संदर्भित।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POTX से SWF C++ रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// Load the POTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.potx");
// Save in SWF format.
prs->Save(u"convertedFile.swf", Aspose::Slides::Export::SaveFormat::Swf);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="potx-to-swf"
        sectionTitle="मुफ्त ऐप POTX को SWF में कन्वर्ट करने के लिए" 
        sectionDescription="[हमारी मुफ्त Collage ऐप आज़माएं](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप नीचे सूचीबद्ध कुछ सहित कई अन्य फ़ाइल स्वरूपों में POTX को भी परिवर्तित कर सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-bmp/" name="POTX TO BMP" description="Bitmap Image" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-emf/" name="POTX TO EMF" description="Enhanced Metafile Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-gif/" name="POTX TO GIF" description="Graphical Interchange Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-html/" name="POTX TO HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="JPEG Image" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument Presentation Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument Standard Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pdf/" name="POTX TO PDF" description="Portable Document Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-png/" name="POTX TO PNG" description="Portable Network Graphics" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pot/" name="POTX TO POT" description="Microsoft PowerPoint Template Files" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-potm/" name="POTX TO POTM" description="Microsoft PowerPoint Template File" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pps/" name="POTX TO PPS" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Macro-enabled Slide Show" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="PowerPoint Slide Show" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Macro-enabled Presentation File" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Open XML presentation Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-svg/" name="POTX TO SVG" description="Scalable Vector Graphics" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Tagged Image Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-xml/" name="POTX TO XML" description="Extensible Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potx-to-xps/" name="POTX TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}