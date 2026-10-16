---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: सी # के माध्यम से ओडीपी को जीआईएफ में कनवर्ट करें
weight: 2280
url: /hi/net/conversion/odp-to-gif/ 
description: ओडीपी के लिए जीआईएफ सी # रूपांतरण के लिए नमूना कोड। VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन के भीतर GIF रूपांतरण के लिए बैच ODP फ़ाइलों के लिए API उदाहरण कोड का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="सी # के माध्यम से ओडीपी को जीआईएफ में कनवर्ट करें" h2="PowerPoint® ODP फ़ाइलों को .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर GIF में निर्यात करें"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके ODP को GIF में कैसे बदलें" %}}

ODP को GIF में बदलने के लिए, हम उपयोग करेंगे
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड ओडीपी को जीआईएफ सी # रूपांतरण दिखाता है" >}}
```cs
using (var presentation = new Presentation("template.odp"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# के माध्यम से ODP को GIF में बदलने के चरण" intro=".NET डेवलपर कोड की कुछ ही पंक्तियों में आसानी से ODP फ़ाइलों को GIF में लोड और परिवर्तित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ ODP फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति में प्रत्येक स्लाइड के माध्यम से पुनरावृति{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रत्येक पुनरावृत्ति के साथ बिटमैप के रूप में एक पूर्ण पैमाने की छवि बनाएं{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}बिटमैप को कॉल करें। जीआईएफ फ़ाइल एक्सटेंशन और इमेजफॉर्मेट के साथ विधि सहेजें। पैरामीटर के रूप में जीआईएफ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro=".NET रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS।
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल।
- Aspose.Slides for .NET DLL आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऐप ODP को GIF में कन्वर्ट करने के लिए"
  description="[हमारी मुफ्त Editor ऐप आज़माएं](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप नीचे सूचीबद्ध कुछ सहित ओडीपी को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-bmp/" name="ODP TO BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-emf/" name="ODP TO EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-html/" name="ODP TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument मानक प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-pdf/" name="ODP TO PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-png/" name="ODP TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-potx/" name="ODP TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-pps/" name="ODP TO PPS" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-ppt/" name="ODP TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-svg/" name="ODP TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-swf/" name="ODP TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/odp-to-xps/" name="ODP TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
