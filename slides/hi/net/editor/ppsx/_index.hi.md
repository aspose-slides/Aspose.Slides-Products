---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPSX फ़ाइलों को .NET के माध्यम से संपादित करें
url: /hi/net/editor/ppsx/ 
description: C# स्रोत कोड .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर PPSX दस्तावेज़ को संपादित करने के लिए।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="सी # में पीपीएसएक्स प्रारूप संपादित करें" h2="सर्वर-साइड Aspose.Slides का उपयोग करके मूल और उच्च प्रदर्शन PPSX दस्तावेज़ संपादन, Microsoft या Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना .NET API के लिए।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके PPSX फ़ाइल को कैसे संपादित करें" %}}

PPSX फ़ाइल को संपादित करने के लिए, हम <a href="https://products.aspose.com/slides/hi/net">Aspose.Slides for .NET</a> API का उपयोग करेंगे जो एक सुविधा संपन्न, शक्तिशाली है और किसी भी संपादक के लिए सी # प्लेटफॉर्म के लिए एपीआई का उपयोग करना आसान है। <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> पैकेज मैनेजर खोलें, <b>Aspose.Slides</b> खोजें और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="आज्ञा" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX फ़ाइलें संपादित करें - C#" >}}
```cs
using var presentation = new Presentation("document.ppsx");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.ppsx", SaveFormat.Ppsx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="सी # में पीपीएसएक्स फाइलों को संपादित करने के लिए कदम" intro="के साथ एक मूल दस्तावेज़ संपादन [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net) एपीआई कोड की कुछ ही पंक्तियों के साथ किया जा सकता है।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX फ़ाइल को `Presentation` ऑब्जेक्ट के साथ लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वेरिएबल्स के माध्यम से लक्षित स्लाइड और आकृति तक पहुँचें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`TextFrame` के माध्यम से टेक्स्ट अपडेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}संपादित प्रस्तुति को `SaveFormat.Ppsx` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएं" intro="हमारे एपीआई सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल
- आपके प्रोजेक्ट में संदर्भित .NET DLL के लिए Aspose.Slides - ऊपर दिए गए डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
