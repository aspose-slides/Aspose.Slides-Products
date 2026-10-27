---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET . के माध्यम से पॉट फ़ाइलें मर्ज करें
weight: 7360
url: /hi/net/merger/pot/ 
description: C# स्रोत कोड .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर POT दस्तावेज़ों को संयोजित करने के लिए।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="सी # में पीओटी प्रारूप मर्ज करें" h2="सर्वर-साइड Aspose.Slides का उपयोग करके मूल और उच्च प्रदर्शन POT दस्तावेज़ विलय, Microsoft या Open Office, Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना .NET API के लिए स्लाइड।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके POT फ़ाइल को कैसे मर्ज करें" %}}

POT फ़ाइल को मर्ज करने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net)
 एपीआई जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और सी # प्लेटफॉर्म के लिए एपीआई को मर्ज करना है। खुला
 [नुगेट](https://www.nuget.org/packages/aspose.slides.net)
 पैकेज मैनेजर, खोजें
 **अनुमान करें।स्लाइड्स**
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="आज्ञा" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="पीओटी फाइलों को मर्ज करें - सी #" >}}
```cs
var ps1 = new Presentation("presen1.pot");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first POT presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="सी # में पीओटी फाइलों को मर्ज करने के लिए कदम" intro="[Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net) API के साथ विलय और संयोजन करने वाला एक मूल दस्तावेज़ कोड की कुछ पंक्तियों के साथ किया जा सकता है।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सभी पॉट फ़ाइलों को पूर्ण पथ के साथ लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आधार फ़ाइल के रूप में एक दस्तावेज़ बनाएं{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}फ़ाइलों को एक-एक करके संयोजित और मर्ज करने के लिए प्रासंगिक विधि को कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सहेजें() विधि को कॉल करें और फ़ाइल नाम (पूर्ण पथ) और प्रारूप (पीओटी) को पैरामीटर के रूप में पास करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अब आप POT फ़ाइल को Microsoft Office, Adobe PDF या किसी अन्य संगत प्रोग्राम में खोल और उपयोग कर सकते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="हमारे एपीआई सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल
- आपके प्रोजेक्ट में संदर्भित .NET DLL के लिए Aspose.Slides - ऊपर दिए गए डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides से निर्मित" title="POT फ़ाइलों को ऑनलाइन मर्ज करें" description="मुफ़्त Aspose.Slides Merger ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी POT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Merger खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides फ़ाइलों को कैसे मर्ज करता है।
- कई POT फ़ाइलें अपलोड करें और उन्हें एक में मिलाएँ।
- मर्ज किया गया परिणाम एक फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POT" readMoreLink="https://docs.fileformat.com/presentation/pot/" %}}

.POT एक्सटेंशन वाली फ़ाइलें बाइनरी Microsoft PowerPoint प्रेज़ेंटेशन टेम्पलेट हैं। यह फ़ॉर्मैट PowerPoint 97-2003 फ़ाइल फ़ॉर्मैट परिवार का हिस्सा है। POT फ़ाइलें नए प्रेज़ेंटेशन बनाने के लिए दोबारा उपयोग किए जा सकने वाले स्लाइड लेआउट, थीम, स्टाइल, बैकग्राउंड, कलर स्कीम, फ़ॉन्ट और अन्य फ़ॉर्मैटिंग संग्रहीत करती हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित विलय प्रारूप" subTitle="C# का उपयोग करके, कोई भी कई अन्य फ़ाइल स्वरूपों को मर्ज कर सकता है, जिनमें शामिल हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/odp/" name="ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/otp/" name="OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/potm/" name="POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/potx/" name="POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/pps/" name="PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/ppsm/" name="PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/ppsx/" name="PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/ppt/" name="PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/pptm/" name="PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/pptx/" name="PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
