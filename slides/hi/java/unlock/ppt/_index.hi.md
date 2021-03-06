---
title: जावा के माध्यम से पीपीटी दस्तावेज़ अनलॉक करें
weight: 1760
url: /hi/java/unlock/ppt/ 
description: जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए जावा रनटाइम एनवायरनमेंट पर पासवर्ड से सुरक्षित पीपीटी फाइल को अनलॉक करने के लिए जावा सैंपल कोड।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="जावा के माध्यम से पीपीटी फाइलों को अनलॉक करें" h2="जावा लाइब्रेरी का उपयोग करके पीपीटी फ़ाइल सहित पावरपॉइंट प्रस्तुतियों से सुरक्षा निकालें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="जावा का उपयोग करके सुरक्षा पीपीटी फ़ाइल कैसे निकालें" %}}

 PPT फ़ाइल को अनलॉक करने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java)
 एपीआई जो एक सुविधा संपन्न, शक्तिशाली और जावा प्लेटफॉर्म के लिए उपयोग में आसान सुरक्षा एपीआई है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
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


{{< blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से पीपीटी अनलॉक करने के चरण" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन के उदाहरण के साथ लोड लॉक पीपीटी
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
isWriteProtected बूलियन प्रकार की संपत्ति का उपयोग करके सुरक्षा की जाँच करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
RemoveWriteProtection () विधि का उपयोग करके सुरक्षा निकालें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पीपीटी प्रारूप में परिणाम सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर सपोर्ट करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="सी # के माध्यम से पीपीटी फाइलों को अनलॉक करें" offSpacer="" %}}

```cs

// Open the PPT file
Presentation pres = new Presentation("WriteProtectedFile.ppt");

// Checking if presentation is write protected
if (pres.getProtectionManager().isWriteProtected())
	// Removing Write protection
	pres.getProtectionManager().removeWriteProtection();

// Saving presentation
pres.save("output.ppt", com.aspose.slides.SaveFormat.Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="जावा एपीआई के लिए Aspose.Slides के बारे में" %}}

 Aspose.Slides API का उपयोग Microsoft PowerPoint दस्तावेज़ों को PDF, XPS, HTML, TIFF, ODP और अन्य विभिन्न स्वरूपों में पढ़ने, लिखने, हेरफेर करने और परिवर्तित करने के लिए किया जा सकता है। कोई नए सिरे से नई फाइलें बना सकता है और उन्हें संबंधित समर्थित प्रारूपों में सहेज सकता है। Aspose.Slides प्रस्तुतियों, स्लाइडों और तत्वों को बनाने, पार्स करने या हेरफेर करने के लिए एक स्टैंडअलोन एपीआई है और यह माइक्रोसॉफ्ट या ओपनऑफिस जैसे किसी भी सॉफ्टवेयर पर निर्भर नहीं करता है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Unlock PPT" sectionDescription="Check our live demos to [unlock PPT files](https://products.aspose.app/slides/unlock/ppt) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPT file and hit the \"Unlock\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PPT file from the link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित अनलॉकिंग प्रारूप" subTitle="जावा का उपयोग करके, कोई भी आसानी से विभिन्न स्वरूपों की सुरक्षा/अनलॉकिंग को हटा सकता है, जिसमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/unlock/odp/" name="ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/unlock/pptx/" name="PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}