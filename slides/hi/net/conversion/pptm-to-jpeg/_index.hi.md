---
title: पीपीटीएम को जेपीईजी में सी # के माध्यम से कनवर्ट करें
weight: 7860
url: /hi/net/conversion/pptm-to-jpeg/ 
description: PPTM से JPEG C# रूपांतरण के लिए नमूना कोड। VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन के भीतर JPEG रूपांतरण के लिए PPTM फ़ाइलों के बैच के लिए API उदाहरण कोड का उपयोग करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="पीपीटीएम को जेपीईजी में सी # के माध्यम से कनवर्ट करें" h2="PowerPoint® PPTM फ़ाइलों को .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर JPEG में निर्यात करें" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके PPTM को JPEG में कैसे बदलें" %}}

 PPTM को JPEG में बदलने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net)
 एपीआई जो एक सुविधा संपन्न, शक्तिशाली और सी # प्लेटफॉर्म के लिए दस्तावेज़ हेरफेर और रूपांतरण एपीआई का उपयोग करने में आसान है। खुला
 [नुगेट](https://www.nuget.org/packages/aspose.slides.net)
 पैकेज मैनेजर, खोजें
 Aspose.Slides
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="PPTM को C# के माध्यम से JPEG में बदलने के चरण" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET डेवलपर कोड की कुछ ही पंक्तियों में आसानी से PPTM फ़ाइलों को JPEG में लोड और परिवर्तित कर सकते हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति वर्ग के उदाहरण के साथ PPTM फ़ाइल लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति में प्रत्येक स्लाइड के माध्यम से पुनरावृति
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रत्येक पुनरावृत्ति के साथ बिटमैप के रूप में एक पूर्ण पैमाने की छवि बनाएं
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
बिटमैप को कॉल करें। JPEG फ़ाइल एक्सटेंशन और ImageFormat.Jpeg के साथ पैरामीटर के रूप में विधि सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS।
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल।
- Aspose.Slides for .NET DLL आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड PPTM से JPEG C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pptm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="मुफ्त ऐप PPTM को JPEG में कन्वर्ट करने के लिए" 
        sectionDescription="[PPT को JPG को रूपांतरित करने के लिए हमारे निःशुल्क ऐप को आज़माएं](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप पीपीटीएम को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-html/" name="PPTM TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-png/" name="PPTM TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}