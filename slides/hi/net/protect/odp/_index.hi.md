---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET का उपयोग करके ODP प्रेजेंटेशन फ़ाइलें सुरक्षित करें
url: /hi/net/protect/odp/
description: ODP प्रेजेंटेशन को पासवर्ड से सुरक्षित करने के लिए C# सोर्स कोड।
keywords: ODP राइट प्रोटेक्शन, ODP एन्क्रिप्ट करें, ODP प्रेजेंटेशन लॉक करें, ODP सुरक्षित करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# का उपयोग करके ODP फ़ाइलें लॉक करें या पासवर्ड से सुरक्षित करें" h2="ऐसे .NET ऐप बनाएं जो सर्वर-साइड API से प्रेजेंटेशन एन्क्रिप्ट करें और बदलाव सीमित करें।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके ODP प्रेजेंटेशन सुरक्षित करें" variant="code" %}}

[Aspose.Slides for .NET](/slides/hi/net/) के साथ आप ODP प्रेजेंटेशन को एन्क्रिप्ट कर सकते हैं या पासवर्ड से उसमें बदलाव सीमित कर सकते हैं। `ProtectionManager.Encrypt` से एन्क्रिप्ट किए गए प्रेजेंटेशन को खोलने के लिए पासवर्ड चाहिए। प्रेजेंटेशन खोलने की अनुमति देते हुए बदलाव सीमित करने के लिए `ProtectionManager.SetWriteProtection` का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# का उपयोग करके ODP प्रेजेंटेशन एन्क्रिप्ट करें" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# का उपयोग करके ODP प्रेजेंटेशन के लिए राइट प्रोटेक्शन सेट करें" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# का उपयोग करके ODP प्रेजेंटेशन को पासवर्ड से कैसे सुरक्षित करें" intro="ODP प्रेजेंटेशन को पासवर्ड से सुरक्षित करने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से ODP फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager.Encrypt` से प्रेजेंटेशन एन्क्रिप्ट करें या `ProtectionManager.SetWriteProtection` से बदलाव सीमित करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सुरक्षित फ़ाइल को `SaveFormat.Odp` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलों को ऑनलाइन पासवर्ड से सुरक्षित करें" description="मुफ़्त Aspose.Slides Lock ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Lock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रेजेंटेशन को कैसे सुरक्षित करता है।
- अपनी ODP फ़ाइल खोलने या संपादित करने के लिए पासवर्ड सेट करें।
- सुरक्षित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="सुरक्षा के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C# का उपयोग करके आप निम्न फ़ॉर्मेट भी सुरक्षित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
