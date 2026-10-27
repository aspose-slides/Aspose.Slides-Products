---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: C++ का उपयोग करके PPT एनोटेशन हटाएँ
url: /hi/cpp/annotation/ppt/ 
description: PPT प्रेज़ेंटेशन से एनोटेशन हटाने के लिए C++ सोर्स कोड।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ में PPT से टिप्पणियाँ और टिप्पणी लेखक हटाएँ" h2="ऐसे C++ ऐप बनाएँ जो सर्वर-साइड API के ज़रिए प्रेज़ेंटेशन फ़ाइलों में टिप्पणियों और लेखकों को प्रबंधित करें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ के ज़रिए PPT से टिप्पणियाँ हटाएँ" variant="code" %}}

PPT प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए [Aspose.Slides for C++](/slides/hi/cpp/) का उपयोग करें। नीचे दिया गया उदाहरण `get_CommentAuthors` से मिले हर लेखक की टिप्पणियाँ हटाता है और फिर टिप्पणी लेखक संग्रह खाली करता है।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT से एनोटेशन हटाएँ – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ के ज़रिए PPT से टिप्पणियाँ कैसे हटाएँ" intro="PPT प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए इन चरणों का पालन करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for C++ इंस्टॉल करें। देखें [इंस्टॉलेशन](https://docs.aspose.com/slides/cpp/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT फ़ाइल को `Presentation` क्लास से लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_CommentAuthors` से मिले टिप्पणी लेखकों पर इटरेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर लेखक की टिप्पणियाँ `get_Comments()->Clear()` से हटाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}टिप्पणी लेखक संग्रह खाली करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपडेट किए गए प्रेज़ेंटेशन को `SaveFormat::Ppt` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides से निर्मित" title="PPT टिप्पणियाँ ऑनलाइन हटाएँ" description="मुफ़्त Aspose.Slides Annotation ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Annotation खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टिप्पणियाँ कैसे हटाता है।
- अपनी PPT फ़ाइल से सभी टिप्पणियाँ हटाएँ।
- साफ़ की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="एनोटेशन के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="C++ के साथ, आप अन्य फ़ॉर्मेट से भी एनोटेशन हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
