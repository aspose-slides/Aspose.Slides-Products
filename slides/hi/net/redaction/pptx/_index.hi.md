---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET का उपयोग करके PPTX प्रेज़ेंटेशन फ़ाइलों में गोपनीय जानकारी छिपाएँ
url: /hi/net/redaction/pptx/
description: PPTX प्रेज़ेंटेशन में टेक्स्ट खोजने और बदलने के लिए C# सोर्स कोड।
keywords: PPTX में गोपनीय जानकारी छिपाएँ, PPTX में टेक्स्ट खोजें और बदलें, PPTX प्रेज़ेंटेशन अपडेट करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# का उपयोग करके PPTX फ़ाइलों में गोपनीय जानकारी छिपाएँ" h2="सर्वर-साइड API के साथ प्रेज़ेंटेशन में टेक्स्ट खोजने और बदलने वाले .NET ऐप बनाएँ।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके PPTX प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ" variant="code" %}}

[Aspose.Slides for .NET](/slides/hi/net/) के साथ, आप PPTX प्रेज़ेंटेशन में टेक्स्ट खोज और बदल सकते हैं। खोज को नियंत्रित करने के लिए `TextSearchOptions` के साथ `Presentation.ReplaceText` का उपयोग करें, फिर बदली गई प्रेज़ेंटेशन सहेजें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# का उपयोग करके PPTX प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# का उपयोग करके PPTX प्रेज़ेंटेशन में गोपनीय जानकारी कैसे छिपाएँ" intro="PPTX प्रेज़ेंटेशन में टेक्स्ट बदलने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` के साथ PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आवश्यक टेक्स्ट बदलने के लिए `TextSearchOptions` के साथ [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}बदली गई प्रेज़ेंटेशन को `SaveFormat.Pptx` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलों में ऑनलाइन गोपनीय जानकारी छिपाएँ" description="मुफ़्त Aspose.Slides Redaction ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Redaction खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट को कैसे खोजता और बदलता है।
- अपनी PPTX फ़ाइल में टेक्स्ट खोजें और बदलें, रेगुलर एक्सप्रेशन सहित।
- संसाधित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="गोपनीय जानकारी छिपाने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C# का उपयोग करके, आप निम्न फ़ॉर्मेट में भी गोपनीय जानकारी छिपा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
