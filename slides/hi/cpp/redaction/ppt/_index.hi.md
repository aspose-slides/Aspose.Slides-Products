---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ का उपयोग करके PPT प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ
url: /hi/cpp/redaction/ppt/
description: C++ में PPT प्रेज़ेंटेशन से गोपनीय जानकारी छिपाएँ। प्रेज़ेंटेशन फ़ाइलों में संवेदनशील टेक्स्ट खोजने और बदलने के लिए Aspose.Slides for C++ का उपयोग करें।
keywords: PPT में गोपनीय जानकारी छिपाएँ, PPT में टेक्स्ट खोजें और बदलें, PPT प्रेज़ेंटेशन अपडेट करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ का उपयोग करके PPT में गोपनीय जानकारी छिपाएँ" h2="Microsoft PowerPoint के बिना प्रेज़ेंटेशन फ़ाइलों में संवेदनशील टेक्स्ट खोजने और बदलने के लिए Aspose.Slides for C++ का उपयोग करें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ के माध्यम से PPT प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ" variant="code" %}}

Aspose.Slides for C++ आपको स्लाइड्स में संवेदनशील टेक्स्ट बदलकर PPT प्रेज़ेंटेशन में गोपनीय जानकारी छिपाने देता है। प्रेज़ेंटेशन में खोजने और अपडेट की गई फ़ाइल सहेजने से पहले मेल खाने वाले टेक्स्ट को बदलने के लिए `Presentation` ऑब्जेक्ट के साथ `SlideUtil::FindAndReplaceText` का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ के साथ PPT प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ के माध्यम से PPT में गोपनीय जानकारी कैसे छिपाएँ" intro="PPT प्रेज़ेंटेशन में गोपनीय जानकारी छिपाने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास के साथ PPT फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}संवेदनशील टेक्स्ट खोजने और बदलने के लिए [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) मेथड का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}संसाधित फ़ाइल को `SaveFormat::Ppt` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides से निर्मित" title="PPT फ़ाइलों में ऑनलाइन गोपनीय जानकारी छिपाएँ" description="मुफ़्त Aspose.Slides Redaction ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Redaction खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट को कैसे खोजता और बदलता है।
- अपनी PPT फ़ाइल में टेक्स्ट खोजें और बदलें, रेगुलर एक्सप्रेशन सहित।
- संसाधित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="गोपनीय जानकारी छिपाने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C++ का उपयोग करके, आप निम्न फ़ॉर्मेट में भी गोपनीय जानकारी छिपा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
