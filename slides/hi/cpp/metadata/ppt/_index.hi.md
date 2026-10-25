---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ से PPT मेटाडेटा देखें या संपादित करें
url: /hi/cpp/metadata/ppt/
description: C++ में PPT मेटाडेटा देखें और संपादित करें। प्रेज़ेंटेशन की बिल्ट-इन और कस्टम प्रॉपर्टी अपडेट करने के लिए Aspose.Slides for C++ का उपयोग करें।
keywords: PPT मेटाडेटा संपादित करें, PPT मेटाडेटा देखें, PPT प्रॉपर्टी संपादित करें, PPT प्रॉपर्टी देखें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ से PPT मेटाडेटा संपादित करें" h2="प्रेज़ेंटेशन फ़ाइलों की बिल्ट-इन और कस्टम प्रॉपर्टी देखने और अपडेट करने के लिए Aspose.Slides for C++ का उपयोग करें।" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ से PPT प्रॉपर्टी बदलें" variant="code" %}}

Aspose.Slides for C++ से आप Microsoft PowerPoint के बिना PPT फ़ाइलों का मेटाडेटा पढ़ और अपडेट कर सकते हैं। `Author` और `Title` जैसी बिल्ट-इन प्रॉपर्टी बदलने या `idx_set`, `GetCustomPropertyName` और `RemoveCustomProperty` से कस्टम प्रॉपर्टी प्रबंधित करने के लिए `Presentation::get_DocumentProperties` से मिलने वाले [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) ऑब्जेक्ट का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT की बिल्ट-इन प्रॉपर्टी बदलें – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT में कस्टम प्रॉपर्टी जोड़ें – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ में PPT मेटाडेटा कैसे देखें या संपादित करें" intro="PPT मेटाडेटा देखने या संपादित करने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से PPT फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_DocumentProperties` से `DocumentProperties` ऑब्जेक्ट प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author` और `Title` जैसी बिल्ट-इन प्रॉपर्टी पढ़ें या अपडेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`idx_set`, `GetCustomPropertyName` और `RemoveCustomProperty` से कस्टम प्रॉपर्टी जोड़ें, पढ़ें या हटाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides से निर्मित" title="PPT मेटाडेटा ऑनलाइन देखें और संपादित करें" description="मुफ़्त Aspose.Slides Metadata ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Metadata खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रॉपर्टी कैसे पढ़ता और लिखता है।
- अपनी PPT फ़ाइल की बिल्ट-इन और कस्टम प्रॉपर्टी देखें और संपादित करें।
- अपडेट की गई फ़ाइल सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित मेटाडेटा फ़ॉर्मैट" subTitle="C++ से आप निम्नलिखित फ़ॉर्मैट का मेटाडेटा भी प्रबंधित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
