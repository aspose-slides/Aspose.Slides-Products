---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python से PPTM मेटाडेटा देखें या संपादित करें
url: /hi/python-net/metadata/pptm/
description: Python से PPTM फ़ाइलों की बिल्ट-इन और कस्टम मेटाडेटा प्रॉपर्टी देखें और संपादित करें।
keywords: PPTM मेटाडेटा संपादित करें, PPTM मेटाडेटा देखें, PPTM प्रॉपर्टी संपादित करें, PPTM प्रॉपर्टी देखें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python से PPTM मेटाडेटा देखें और संपादित करें" h2="ऐसे Python ऐप्लिकेशन बनाएँ जो Aspose.Slides से प्रेज़ेंटेशन की बिल्ट-इन और कस्टम प्रॉपर्टी पढ़ें और बदलें।" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python से PPTM मेटाडेटा देखें और बदलें" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/hi/python-net/) से आप PPTM प्रेज़ेंटेशन में बिल्ट-इन मेटाडेटा पढ़ और अपडेट कर सकते हैं, और कस्टम दस्तावेज़ प्रॉपर्टी जोड़, अपडेट या हटा सकते हैं। `Presentation.document_properties` से [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) ऑब्जेक्ट तक पहुँचें, उसे बदलें और प्रेज़ेंटेशन को PPTM फ़ॉर्मैट में सहेजें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM की बिल्ट-इन प्रॉपर्टी अपडेट करें – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM की कस्टम प्रॉपर्टी जोड़ें और हटाएँ – Python" >}}
```python
with slides.Presentation("presentation.pptm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pptm", slides.export.SaveFormat.PPTM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python से PPTM मेटाडेटा कैसे संपादित करें" intro="PPTM फ़ाइल का मेटाडेटा संपादित करने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से PPTM फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.document_properties` से उसके `IDocumentProperties` ऑब्जेक्ट तक पहुँचें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}बिल्ट-इन प्रॉपर्टी अपडेट करें या कस्टम प्रॉपर्टी के लिए `set_custom_property_value` और `remove_custom_property` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.save` और `SaveFormat.PPTM` से प्रेज़ेंटेशन सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides से निर्मित" title="PPTM मेटाडेटा ऑनलाइन देखें और संपादित करें" description="मुफ़्त Aspose.Slides Metadata ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTM फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Metadata खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रॉपर्टी कैसे पढ़ता और लिखता है।
- अपनी PPTM फ़ाइल की बिल्ट-इन और कस्टम प्रॉपर्टी देखें और संपादित करें।
- अपडेट की गई फ़ाइल सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित मेटाडेटा फ़ॉर्मैट" subTitle="Python से आप अन्य समर्थित प्रेज़ेंटेशन फ़ॉर्मैट का मेटाडेटा भी प्रबंधित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
