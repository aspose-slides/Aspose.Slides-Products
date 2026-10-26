---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ का उपयोग करके PPT प्रेजेंटेशन अनलॉक करें
url: /hi/cpp/unlock/ppt/
description: C++ में PPT प्रेजेंटेशन अनलॉक करें। प्रेजेंटेशन फ़ाइलों से एन्क्रिप्शन और राइट प्रोटेक्शन हटाने के लिए Aspose.Slides for C++ का उपयोग करें।
keywords: PPT राइट प्रोटेक्शन हटाएं, PPT डिक्रिप्ट करें, PPT प्रेजेंटेशन अनलॉक करें, PPT की सुरक्षा हटाएं
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ का उपयोग करके PPT अनलॉक करें" h2="Microsoft PowerPoint के बिना प्रेजेंटेशन फ़ाइलों से एन्क्रिप्शन और राइट प्रोटेक्शन हटाने के लिए Aspose.Slides for C++ का उपयोग करें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ के ज़रिए PPT प्रेजेंटेशन से सुरक्षा हटाना" variant="code" %}}

Aspose.Slides for C++ से आप PPT प्रेजेंटेशन से एन्क्रिप्शन या राइट प्रोटेक्शन हटा सकते हैं। एन्क्रिप्टेड फ़ाइल खोलने के लिए `LoadOptions` का उपयोग करें, फिर `RemoveEncryption` या `RemoveWriteProtection` कॉल करने के लिए `Presentation` क्लास के `ProtectionManager` ऑब्जेक्ट का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ का उपयोग करके PPT से पासवर्ड सुरक्षा हटाना" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.ppt", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ का उपयोग करके PPT प्रेजेंटेशन से राइट प्रोटेक्शन हटाना" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.ppt");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ के ज़रिए PPT से पासवर्ड कैसे हटाएं" intro="PPT प्रेजेंटेशन से सुरक्षा हटाने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से PPT फ़ाइल लोड करें, और पासवर्ड ज़रूरी होने पर `LoadOptions` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सुरक्षा हटाने के लिए `ProtectionManager` ऑब्जेक्ट का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एन्क्रिप्टेड फ़ाइलों के लिए `RemoveEncryption` या राइट-प्रोटेक्टेड फ़ाइलों के लिए `RemoveWriteProtection` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अनलॉक की गई फ़ाइल को `SaveFormat::Ppt` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides से निर्मित" title="PPT फ़ाइलें ऑनलाइन अनलॉक करें" description="मुफ़्त Aspose.Slides Unlock ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Unlock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides सुरक्षा कैसे हटाता है।
- अपनी PPT फ़ाइल से पासवर्ड या राइट प्रोटेक्शन हटाएं।
- अनलॉक की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अनलॉक करने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C++ का उपयोग करके आप निम्न फ़ॉर्मेट से भी सुरक्षा हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
