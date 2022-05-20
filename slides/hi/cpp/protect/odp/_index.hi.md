---
title: C++ के माध्यम से ODP दस्तावेज़ को सुरक्षित और लॉक करें
weight: 670
url: /hi/cpp/protect/odp/ 
description: विंडोज 32 बिट, विंडोज 64 बिट और लिनक्स 64 बिट के लिए सी ++ रनटाइम एनवायरनमेंट पर पासवर्ड का उपयोग करके ओडीपी फाइल को लॉक करने के लिए सी ++ उदाहरण कोड।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="सी ++ के माध्यम से ओडीपी फाइलों को एन्क्रिप्ट करें" h2=".NET लाइब्रेरी का उपयोग करके ओडीपी प्रारूप सहित पावरपॉइंट प्रस्तुतियों को पासवर्ड से सुरक्षित रखें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके ODP फ़ाइल को कैसे सुरक्षित करें" %}}

 ODP फ़ाइल की सुरक्षा के लिए, हम उपयोग करेंगे
 [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp)
 एपीआई जो एक सुविधा संपन्न, शक्तिशाली और सी ++ प्लेटफॉर्म के लिए दस्तावेज़ एन्क्रिप्शन एपीआई का उपयोग करने में आसान है। आप इसका नवीनतम संस्करण सीधे डाउनलोड कर सकते हैं, बस खोलें
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 पैकेज मैनेजर, खोजें
 **आसमान करें।स्लाइड।सीपीपी**
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="Aspose.Slides" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C++ के माध्यम से ODP फ़ाइलों को सुरक्षित रखने के चरण" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides API का उपयोग करके दस्तावेज़ सुरक्षा कोड की कुछ पंक्तियों के साथ की जा सकती है।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ओडीपी फ़ाइल लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Get\_ProtectionManager()->Encrypt(.) विधि का उपयोग करके पासवर्ड सेट करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
संरक्षित ओडीपी प्रस्तुति सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C++ सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर सपोर्ट करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज या विंडोज 32 बिट, विंडोज 64 बिट और लिनक्स 64 बिट के लिए सी ++ रनटाइम एनवायरनमेंट के साथ संगत ओएस।
- Aspose.Slides for C++ DLL आपके प्रोजेक्ट में संदर्भित।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.odp";
const String outputFilePath = u"OutputPath\OutPutFile.odp";

// Load the ODP file
SharedPtr<Presentation> odpFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
odpFile->get_ProtectionManager()->Encrypt(u"password");

// Save the ODP
odpFile->Save(outputFilePath, SaveFormat::Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose के बारे में। C++ API के लिए स्लाइड्स" %}}

 Aspose.Slides API का उपयोग Microsoft PowerPoint दस्तावेज़ों को PDF, XPS, HTML, TIFF, ODP और अन्य विभिन्न स्वरूपों में पढ़ने, लिखने, हेरफेर करने और परिवर्तित करने के लिए किया जा सकता है। कोई नए सिरे से नई फाइलें बना सकता है और उन्हें संबंधित समर्थित प्रारूपों में सहेज सकता है। Aspose.Slides प्रस्तुतियों, स्लाइडों और तत्वों को बनाने, पार्स करने या हेरफेर करने के लिए एक स्टैंडअलोन एपीआई है और यह माइक्रोसॉफ्ट या ओपनऑफिस जैसे किसी भी सॉफ्टवेयर पर निर्भर नहीं करता है।  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect ODP" sectionDescription="Check our live demos to [encrypt ODP files](https://products.aspose.app/slides/protect/odp) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुरक्षा दस्तावेज" subTitle="C++ का उपयोग करके, कोई अन्य फ़ाइलों की सुरक्षा कर सकता है, जिनमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/protect/ppt/" name="PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/protect/pptx/" name="PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}