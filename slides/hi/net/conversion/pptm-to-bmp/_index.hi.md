---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTM को C# के माध्यम से BMP में बदलें
weight: 6790
url: /hi/net/conversion/pptm-to-bmp/ 
description: पीपीटीएम से बीएमपी सी# रूपांतरण के लिए नमूना कोड। VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन के भीतर PPTM फ़ाइलों को BMP रूपांतरण में बैच के लिए API उदाहरण कोड का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTM को C# के माध्यम से BMP में बदलें" h2="PowerPoint® PPTM फ़ाइलों को .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर BMP में निर्यात करें"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके PPTM को BMP में कैसे बदलें" %}}

PPTM को BMP में बदलने के लिए, हम उपयोग करेंगे
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net)
 एपीआई जो एक सुविधा संपन्न, शक्तिशाली और सी # प्लेटफॉर्म के लिए दस्तावेज़ हेरफेर और रूपांतरण एपीआई का उपयोग करने में आसान है। खुला
 [नुगेट](https://www.nuget.org/packages/aspose.slides.net)
 पैकेज मैनेजर, खोजें
 Aspose.Slides
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="पैकेज मैनेजर कंसोल कमांड" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड PPTM को BMP C# रूपांतरण दिखाता है" >}}
```cs
using (var presentation = new Presentation("template.pptm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in BMP format
        bitmap.Save(string.Format("Slide_{0}.bmp", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Bmp);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTM को C# के माध्यम से BMP में बदलने के चरण" intro=".NET डेवलपर कोड की कुछ ही पंक्तियों में आसानी से PPTM फ़ाइलों को BMP में लोड और परिवर्तित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ PPTM फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति में प्रत्येक स्लाइड के माध्यम से पुनरावृति{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रत्येक पुनरावृत्ति के साथ बिटमैप के रूप में एक पूर्ण पैमाने की छवि बनाएं{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}बिटमैप को कॉल करें। बीएमपी फ़ाइल एक्सटेंशन और इमेजफॉर्मेट के साथ विधि सहेजें। पैरामीटर के रूप में बीएमपी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro=".NET रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS।
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल।
- Aspose.Slides for .NET DLL आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऐप PPTM को BMP में कन्वर्ट करने के लिए"
  description="[PPT को BMP को रूपांतरित करने के लिए हमारे निःशुल्क ऐप को आज़माएं](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप पीपीटीएम को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-html/" name="PPTM TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-png/" name="PPTM TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
