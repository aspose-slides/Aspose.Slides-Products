---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET का उपयोग करके ODP प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट खोजें
url: /hi/net/search/odp/
description: ODP प्रेज़ेंटेशन में टेक्स्ट खोजने के लिए C# सोर्स कोड।
keywords: ODP में टेक्स्ट खोजें, ODP में टेक्स्ट ढूँढें, ODP प्रेज़ेंटेशन का टेक्स्ट खोजें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# का उपयोग करके ODP फ़ाइलों में टेक्स्ट खोजें" h2="सर्वर-साइड API के साथ प्रेज़ेंटेशन में टेक्स्ट ढूँढने वाले .NET ऐप बनाएँ।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके ODP प्रेज़ेंटेशन में टेक्स्ट खोजें" variant="code" %}}

[Aspose.Slides for .NET](/slides/hi/net/) के साथ, आप ODP प्रेज़ेंटेशन में टेक्स्ट खोज सकते हैं। `SlideUtil.GetAllTextBoxes` से किसी स्लाइड के टेक्स्ट फ़्रेम प्राप्त करें, फिर आवश्यक वाक्यांश के लिए उनके `Text` मान जाँचें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# का उपयोग करके ODP प्रेज़ेंटेशन में टेक्स्ट खोजें" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# का उपयोग करके ODP प्रेज़ेंटेशन में टेक्स्ट कैसे खोजें" intro="ODP प्रेज़ेंटेशन में टेक्स्ट खोजने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` के साथ ODP फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.Slides` से आवश्यक स्लाइड प्राप्त करें और उसे एक वेरिएबल में असाइन करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/) से उसके टेक्स्ट फ़्रेम प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}जाँचें कि हर फ़्रेम के `Text` मान में आवश्यक वाक्यांश है या नहीं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलों में ऑनलाइन टेक्स्ट खोजें" description="मुफ़्त Aspose.Slides Search ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Search खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट कैसे ढूँढता है।
- अपनी ODP फ़ाइल में सादा टेक्स्ट या रेगुलर एक्सप्रेशन खोजें।
- मिले परिणामों को टेक्स्ट फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="खोज के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C# का उपयोग करके, आप निम्न फ़ॉर्मेट में भी टेक्स्ट खोज सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
