---
title: सी # के माध्यम से खोले बिना पीपीटी दस्तावेज़ खोजें
weight: 6250
url: /hi/net/search/ppt/ 
description: C# सोर्स कोड .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर PPT फाइल में पैटर्न वाले शब्दों को खोजने के लिए।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="सी # में पीपीटी प्रारूप खोजें" h2="Microsoft या Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना सर्वर-साइड Aspose.Slides के लिए मूल और उच्च प्रदर्शन PPT दस्तावेज़ खोज।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके PPT फ़ाइल कैसे खोजें" %}}

 PPT फ़ाइल को खोजने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net)
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान Microsoft PowerPoint दस्तावेज़ है जो C# प्लेटफॉर्म के लिए API खोजता है। खुला
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


{{< blocks/products/pf/agp/feature-section-col title="सी#में पीपीटी फाइलों को खोजने के लिए कदम" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="[Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net) API के साथ एक बुनियादी दस्तावेज़ खोज कोड की कुछ पंक्तियों के साथ की जा सकती है।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
पीपीटी फ़ाइल लोड करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन में सभी टेक्स्ट बॉक्स प्राप्त करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ खोजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ बदलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पीपीटी प्रस्तुति लिखें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 हमारे एपीआई सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल
- आपके प्रोजेक्ट में संदर्भित .NET DLL के लिए Aspose.Slides - ऊपर दिए गए डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="पीपीटी फाइलें खोजें - सी #" offSpacer="" %}}

```cs
Presentation pres = new Presentation("filetobesearched.ppt");

//Get all text boxes in the presentation

ITextFrame[] tb = SlideUtil.GetAllTextBoxes(pres.Slides[0]);

for (int i = 0; i < tb.Length; i++)

foreach (Paragraph para in tb[i].Paragraphs)

    foreach (Portion port in para.Portions)

        //Search text to be replaced

        if (port.Text.Contains(strToFind))

        //Replace exisitng text with the new text

        {

            string str = port.Text;

            int idx = str.IndexOf(strToFind);

            string strStartText = str.Substring(0, idx);

            string strEndText = str.Substring(idx + strToFind.Length, str.Length - 1 - (idx + strToFind.Length - 1));

            port.Text = strStartText + strToReplaceWith + strEndText;

        }

pres.Save("filetobesearched.ppt",Aspose.Slides.Export.SaveFormat.Ppt);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 स्लाइड एपीआई का उपयोग माइक्रोसॉफ्ट पावरपॉइंट दस्तावेजों को पीडीएफ, एक्सपीएस, एचटीएमएल, टीआईएफएफ, ओडीपी और विभिन्न अन्य प्रारूपों में पढ़ने, लिखने, हेरफेर करने और परिवर्तित करने के लिए किया जा सकता है। कोई नए सिरे से नई फाइलें बना सकता है और उन्हें संबंधित समर्थित प्रारूपों में सहेज सकता है। Aspose.Slides प्रस्तुतियों, स्लाइडों और तत्वों को बनाने, पार्स करने या हेरफेर करने के लिए एक स्टैंडअलोन एपीआई है और यह माइक्रोसॉफ्ट या ओपनऑफिस जैसे किसी भी सॉफ्टवेयर पर निर्भर नहीं करता है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Search Live Demos" sectionDescription="Search text, words, phrases within PPT documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/search). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPT files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT " readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित खोज प्रारूप" subTitle="सी # का उपयोग करके, कोई अन्य प्रारूप भी खोज सकता है जिसमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/search/odp/" name="ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/search/pptx/" name="PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}