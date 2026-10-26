---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ का उपयोग करके ODP प्रेजेंटेशन सुरक्षित करें
url: /hi/cpp/protect/odp/
description: C++ में ODP प्रेजेंटेशन सुरक्षित करें। फ़ाइलें एन्क्रिप्ट करने और राइट प्रोटेक्शन सेट करने के लिए Aspose.Slides for C++ का उपयोग करें।
keywords: ODP राइट प्रोटेक्शन, ODP एन्क्रिप्ट करें, ODP प्रेजेंटेशन लॉक करें, ODP सुरक्षित करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ का उपयोग करके ODP लॉक करें या पासवर्ड से सुरक्षित करें" h2="Microsoft PowerPoint के बिना प्रेजेंटेशन एन्क्रिप्ट करने और राइट प्रोटेक्शन सेट करने के लिए Aspose.Slides for C++ का उपयोग करें।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ के ज़रिए ODP प्रेजेंटेशन सुरक्षित करना" variant="code" %}}

Aspose.Slides for C++ से आप ODP प्रेजेंटेशन को खुलने या बदले जाने से सुरक्षित कर सकते हैं। `Encrypt` से फ़ाइल एन्क्रिप्ट करने या `SetWriteProtection` से संपादन सीमित करने के लिए `Presentation` क्लास के `ProtectionManager` ऑब्जेक्ट का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ का उपयोग करके ODP प्रेजेंटेशन एन्क्रिप्ट करना" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ का उपयोग करके ODP प्रेजेंटेशन पर राइट प्रोटेक्शन सेट करना" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ के ज़रिए ODP को पासवर्ड से कैसे सुरक्षित करें" intro="ODP प्रेजेंटेशन सुरक्षित करने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से ODP फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` ऑब्जेक्ट से प्रेजेंटेशन सुरक्षित करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पासवर्ड सुरक्षा के लिए `Encrypt` या राइट प्रोटेक्शन के लिए `SetWriteProtection` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सुरक्षित फ़ाइल को `SaveFormat::Odp` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलों को ऑनलाइन पासवर्ड से सुरक्षित करें" description="मुफ़्त Aspose.Slides Lock ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Lock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रेजेंटेशन को कैसे सुरक्षित करता है।
- अपनी ODP फ़ाइल खोलने या संपादित करने के लिए पासवर्ड सेट करें।
- सुरक्षित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="सुरक्षा के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C++ का उपयोग करके आप निम्न फ़ॉर्मेट भी सुरक्षित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
