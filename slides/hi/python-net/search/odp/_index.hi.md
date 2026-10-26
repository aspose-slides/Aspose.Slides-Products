---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python के साथ ODP प्रेज़ेंटेशन में टेक्स्ट खोजें
url: /hi/python-net/search/odp/
description: Python और Aspose.Slides के साथ ODP प्रेज़ेंटेशन में टेक्स्ट खोजें।
keywords: ODP में टेक्स्ट खोजें, ODP में शब्द ढूँढें, Python के साथ ODP प्रेज़ेंटेशन खोजें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python के साथ ODP प्रेज़ेंटेशन में टेक्स्ट खोजें" h2="Aspose.Slides के साथ OpenDocument प्रेज़ेंटेशन में टेक्स्ट ढूँढने वाले Python एप्लिकेशन बनाएँ।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python के साथ किसी ODP प्रेज़ेंटेशन में टेक्स्ट खोजें" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/hi/python-net/) के साथ, आप हर स्लाइड पर किसी दी गई स्ट्रिंग वाले टेक्स्ट फ़्रेम ढूँढने के लिए [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) का उपयोग कर सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP प्रेज़ेंटेशन में टेक्स्ट खोजें – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python के साथ ODP में टेक्स्ट कैसे खोजें" intro="ODP प्रेज़ेंटेशन में टेक्स्ट खोजने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` के साथ ODP फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}स्लाइड्स पर इटरेट करें और हर स्लाइड के लिए [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर मेल खाने वाले टेक्स्ट फ़्रेम की `text` प्रॉपर्टी पढ़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलों में ऑनलाइन टेक्स्ट खोजें" description="मुफ़्त Aspose.Slides Search ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Search खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट कैसे ढूँढता है।
- अपनी ODP फ़ाइल में सादा टेक्स्ट या रेगुलर एक्सप्रेशन खोजें।
- मिले परिणामों को टेक्स्ट फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="खोज के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="अन्य समर्थित प्रेज़ेंटेशन फ़ॉर्मेट में टेक्स्ट खोजने के लिए Python का उपयोग करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
