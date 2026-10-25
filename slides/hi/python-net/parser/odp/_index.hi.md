---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python से ODP फ़ाइलों से टेक्स्ट निकालें
url: /hi/python-net/parser/odp/
description: Python से ODP प्रेज़ेंटेशन से टेक्स्ट और टेक्स्ट फ़ॉर्मैटिंग का विवरण निकालें।
keywords: Python से ODP पार्स करें, ODP पार्सर Python, Python में ODP से डेटा निकालें, Python से ODP से टेक्स्ट निकालें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python से ODP प्रेज़ेंटेशन से टेक्स्ट निकालें" h2="ऐसे Python ऐप्लिकेशन बनाएँ जो Aspose.Slides से OpenDocument प्रेज़ेंटेशन से टेक्स्ट और फ़ॉर्मैटिंग का विवरण निकालें।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python से ODP प्रेज़ेंटेशन से टेक्स्ट निकालने का उदाहरण" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/hi/python-net/) `SlideUtil` पर स्टैटिक मेथड [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) देता है। यह पूरे प्रेज़ेंटेशन के `TextFrame` ऑब्जेक्ट लौटाता है और मास्टर स्लाइड का टेक्स्ट भी शामिल कर सकता है। नीचे दिया गया उदाहरण ODP प्रेज़ेंटेशन से टेक्स्ट और संबंधित फ़ॉन्ट विवरण निकालता है।

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP प्रेज़ेंटेशन से टेक्स्ट निकालें – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python से ODP से टेक्स्ट कैसे निकालें" intro="ODP फ़ाइल से टेक्स्ट निकालने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से ODP फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.get_all_text_frames` कॉल करें और बताएँ कि मास्टर स्लाइड शामिल करनी हैं या नहीं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}लौटाए गए `TextFrame` ऑब्जेक्ट पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर टेक्स्ट फ़्रेम के `paragraphs` कलेक्शन पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर पैराग्राफ़ के `portions` कलेक्शन पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}मौजूदा हिस्से का `text` और फ़ॉर्मैटिंग प्रॉपर्टी पढ़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides से निर्मित" title="टेक्स्ट और इमेज ऑनलाइन निकालें" description="मुफ़्त Aspose.Slides Parser ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Parser खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलें कैसे पढ़ता है।
- एक ODP फ़ाइल अपलोड करें और उसका टेक्स्ट और इमेज पाएँ।
- सब कुछ एक ZIP आर्काइव के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="पार्सिंग के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="Python से आप अन्य समर्थित प्रेज़ेंटेशन फ़ॉर्मैट से भी टेक्स्ट निकाल सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
