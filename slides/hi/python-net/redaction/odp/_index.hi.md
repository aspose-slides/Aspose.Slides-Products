---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python के साथ ODP प्रेज़ेंटेशन में टेक्स्ट छिपाएँ
url: /hi/python-net/redaction/odp/
description: Python के साथ ODP प्रेज़ेंटेशन में संवेदनशील टेक्स्ट खोजें और बदलें।
keywords: ODP में गोपनीय जानकारी छिपाएँ, ODP में टेक्स्ट खोजें और बदलें, ODP प्रेज़ेंटेशन अपडेट करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python के साथ ODP प्रेज़ेंटेशन में टेक्स्ट छिपाएँ" h2="Aspose.Slides के साथ प्रेज़ेंटेशन में संवेदनशील टेक्स्ट खोजने और बदलने वाले Python एप्लिकेशन बनाएँ।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python के साथ किसी ODP प्रेज़ेंटेशन में टेक्स्ट छिपाएँ" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/hi/python-net/) के साथ, आप पूरी ODP प्रेज़ेंटेशन में संवेदनशील टेक्स्ट बदल सकते हैं। खोज को नियंत्रित करने के लिए `TextSearchOptions` के साथ `Presentation.replace_text` का उपयोग करें, फिर बदली गई प्रेज़ेंटेशन सहेजें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP प्रेज़ेंटेशन में टेक्स्ट छिपाएँ – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python के साथ ODP प्रेज़ेंटेशन में टेक्स्ट कैसे छिपाएँ" intro="ODP प्रेज़ेंटेशन में संवेदनशील टेक्स्ट बदलने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` के साथ ODP फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आवश्यक टेक्स्ट बदलने के लिए `TextSearchOptions` के साथ [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}बदली गई प्रेज़ेंटेशन को `SaveFormat.ODP` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलों में ऑनलाइन गोपनीय जानकारी छिपाएँ" description="मुफ़्त Aspose.Slides Redaction ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Redaction खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट को कैसे खोजता और बदलता है।
- अपनी ODP फ़ाइल में टेक्स्ट खोजें और बदलें, रेगुलर एक्सप्रेशन सहित।
- संसाधित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="गोपनीय जानकारी छिपाने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="अन्य समर्थित प्रेज़ेंटेशन फ़ॉर्मेट में टेक्स्ट छिपाने के लिए Python का उपयोग करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
