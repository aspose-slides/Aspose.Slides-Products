---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET के माध्यम से POTM फाइलों को संपादित करें
url: /hi/net/editor/potm/ 
description: सी # स्रोत कोड .NET फ्रेमवर्क, .NET कोर, विंडोज़ एज़ूर, मोनो या ज़ामरीन प्लेटफॉर्म पर पीओटीएम दस्तावेज़ को संपादित करने के लिए।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="सी # में पीओटीएम प्रारूप संपादित करें" h2="Microsoft या Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना सर्वर-साइड Aspose.Slides के लिए मूल और उच्च प्रदर्शन POTM दस्तावेज़ संपादन।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके POTM फ़ाइल को कैसे संपादित करें" %}}

POTM फ़ाइल को संपादित करने के लिए, हम <a href="https://products.aspose.com/slides/hi/net">Aspose.Slides for .NET</a> API का उपयोग करेंगे जो एक सुविधा संपन्न, शक्तिशाली है और किसी भी संपादक के लिए सी # प्लेटफॉर्म के लिए एपीआई का उपयोग करना आसान है। <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> पैकेज मैनेजर खोलें, <b>Aspose.Slides</b> खोजें और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="आज्ञा" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM फ़ाइलें संपादित करें - C#" >}}
```cs
using var presentation = new Presentation("document.potm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.potm", SaveFormat.Potm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="सी#में पीओटीएम फाइलों को संपादित करने के चरण" intro="के साथ एक मूल दस्तावेज़ संपादन [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net) एपीआई कोड की कुछ ही पंक्तियों के साथ किया जा सकता है।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POTM फ़ाइल को `Presentation` ऑब्जेक्ट के साथ लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वेरिएबल्स के माध्यम से लक्षित स्लाइड और आकृति तक पहुँचें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`TextFrame` के माध्यम से टेक्स्ट अपडेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}संपादित प्रस्तुति को `SaveFormat.Potm` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="हमारे एपीआई सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल
- आपके प्रोजेक्ट में संदर्भित .NET DLL के लिए Aspose.Slides - ऊपर दिए गए डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलें ऑनलाइन संपादित करें" description="मुफ़्त Aspose.Slides Editor ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Editor खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलों को कैसे संभालता है।
- अपनी PPTX फ़ाइलें अपलोड करें और तुरंत संपादित करें।
- संपादित फ़ाइल को सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. These settings can include styles, backgrounds, colour palette, fonts and defaults along with macros that consist of custom functions for doing particular task. They may also be opened by a previous version of PowerPoint with Open XML document support installed. POTM files can be opened in Microsoft PowerPoint for editing like any other PowerPoint file.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
