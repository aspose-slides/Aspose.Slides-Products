---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Python में ODP से टिप्पणियाँ हटाएँ
url: /hi/python-net/annotation/odp/ 
description: Aspose.Slides for Python via .NET के साथ Python में ODP प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाएँ।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python में ODP से टिप्पणियाँ और टिप्पणी लेखक हटाएँ" h2="प्रेज़ेंटेशन की टिप्पणियाँ और उनसे जुड़े लेखक हटाने के लिए Aspose.Slides for Python via .NET का उपयोग करें।" related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python के ज़रिए ODP से टिप्पणियाँ हटाएँ" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/hi/python-net/) ODP प्रेज़ेंटेशन में संग्रहीत टिप्पणियों और टिप्पणी लेखकों तक पहुँच देता है। `Presentation` से फ़ाइल लोड करें, हर लेखक का `comments` संग्रह खाली करें, `comment_authors` खाली करें और परिणाम को ODP फ़ॉर्मेट में सहेजें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python में ODP से टिप्पणियाँ हटाएँ" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python के ज़रिए ODP से टिप्पणियाँ कैसे हटाएँ" intro="ODP प्रेज़ेंटेशन से सभी टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए इन चरणों का पालन करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/) इंस्टॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP फ़ाइल को `Presentation` से खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` पर इटरेट करें और हर लेखक का `comments` संग्रह खाली करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`comment_authors` संग्रह खाली करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपडेट किए गए ODP प्रेज़ेंटेशन को लिखने के लिए `SaveFormat.ODP` के साथ `save` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides से निर्मित" title="ODP टिप्पणियाँ ऑनलाइन हटाएँ" description="मुफ़्त Aspose.Slides Annotation ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Annotation खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टिप्पणियाँ कैसे हटाता है।
- अपनी ODP फ़ाइल से सभी टिप्पणियाँ हटाएँ।
- साफ़ की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="एनोटेशन के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="Python के साथ, आप अन्य फ़ॉर्मेट से भी एनोटेशन हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
