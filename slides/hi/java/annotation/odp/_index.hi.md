---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Java का उपयोग करके ODP एनोटेशन हटाएँ
url: /hi/java/annotation/odp/ 
description: Aspose.Slides for Java के साथ Java में ODP प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाएँ।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java में ODP से टिप्पणियाँ और टिप्पणी लेखक हटाएँ" h2="प्रेज़ेंटेशन फ़ाइलों से टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए Aspose.Slides for Java का उपयोग करें।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के ज़रिए ODP से टिप्पणियाँ हटाएँ" variant="code" %}}

Aspose.Slides for Java आपको ODP प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाने देता है। `Presentation` क्लास से फ़ाइल लोड करें, `getCommentAuthors` से मिले `ICommentAuthor` ऑब्जेक्ट पर इटरेट करें, उनकी टिप्पणियाँ हटाएँ और अपडेट किया गया प्रेज़ेंटेशन सहेजें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP से एनोटेशन हटाएँ – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java के ज़रिए ODP से टिप्पणियाँ कैसे हटाएँ" intro="ODP प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए इन चरणों का पालन करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for Java इंस्टॉल करें। देखें [इंस्टॉलेशन](https://docs.aspose.com/slides/java/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP फ़ाइल को `Presentation` क्लास से लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getCommentAuthors` से मिले `ICommentAuthor` ऑब्जेक्ट पर इटरेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर लेखक की टिप्पणियाँ `getComments().clear()` से हटाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}टिप्पणी लेखक संग्रह खाली करें और अपडेट की गई ODP फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides से निर्मित" title="ODP टिप्पणियाँ ऑनलाइन हटाएँ" description="मुफ़्त Aspose.Slides Annotation ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Annotation खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टिप्पणियाँ कैसे हटाता है।
- अपनी ODP फ़ाइल से सभी टिप्पणियाँ हटाएँ।
- साफ़ की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="एनोटेशन के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="Java के साथ, आप अन्य फ़ॉर्मेट से भी एनोटेशन हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
