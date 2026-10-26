---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET का उपयोग करके ODP प्रेजेंटेशन फ़ाइलें अनलॉक करें
url: /hi/net/unlock/odp/
description: ODP प्रेजेंटेशन से पासवर्ड सुरक्षा हटाने के लिए C# सोर्स कोड।
keywords: ODP राइट प्रोटेक्शन हटाएं, ODP डिक्रिप्ट करें, ODP प्रेजेंटेशन अनलॉक करें, ODP की सुरक्षा हटाएं
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# का उपयोग करके ODP फ़ाइलें अनलॉक करें" h2="ऐसे .NET ऐप बनाएं जो सर्वर-साइड API से प्रेजेंटेशन का एन्क्रिप्शन और राइट प्रोटेक्शन हटाएं।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# का उपयोग करके ODP प्रेजेंटेशन से सुरक्षा हटाएं" variant="code" %}}

[Aspose.Slides for .NET](/slides/hi/net/) के साथ आप ODP प्रेजेंटेशन से एन्क्रिप्शन या राइट प्रोटेक्शन हटा सकते हैं। एन्क्रिप्शन हटाने के लिए सही पासवर्ड के साथ प्रेजेंटेशन लोड करें और `ProtectionManager.RemoveEncryption` कॉल करें। राइट प्रोटेक्शन हटाने के लिए `ProtectionManager.RemoveWriteProtection` कॉल करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# का उपयोग करके ODP प्रेजेंटेशन से एन्क्रिप्शन हटाएं" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# का उपयोग करके ODP प्रेजेंटेशन से राइट प्रोटेक्शन हटाएं" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# का उपयोग करके ODP प्रेजेंटेशन से सुरक्षा कैसे हटाएं" intro="ODP प्रेजेंटेशन से सुरक्षा हटाने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से ODP फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एन्क्रिप्टेड फ़ाइल के लिए, लोड करने से पहले `LoadOptions.Password` के ज़रिए पासवर्ड दें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}लागू सुरक्षा के अनुसार `ProtectionManager.RemoveEncryption` या `ProtectionManager.RemoveWriteProtection` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अनलॉक किए गए प्रेजेंटेशन को `SaveFormat.Odp` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलें ऑनलाइन अनलॉक करें" description="मुफ़्त Aspose.Slides Unlock ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Unlock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides सुरक्षा कैसे हटाता है।
- अपनी ODP फ़ाइल से पासवर्ड या राइट प्रोटेक्शन हटाएं।
- अनलॉक की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अनलॉक करने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C# का उपयोग करके आप निम्न फ़ॉर्मेट से भी सुरक्षा हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
