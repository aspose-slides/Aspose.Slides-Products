---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Java का उपयोग करके PPT एनोटेशन हटाएँ
url: /hi/java/annotation/ppt/ 
description: Aspose.Slides for Java के साथ Java में PPT प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाएँ।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java में PPT से टिप्पणियाँ और टिप्पणी लेखक हटाएँ" h2="प्रेज़ेंटेशन फ़ाइलों से टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए Aspose.Slides for Java का उपयोग करें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के ज़रिए PPT से टिप्पणियाँ हटाएँ" variant="code" %}}

Aspose.Slides for Java आपको PPT प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाने देता है। `Presentation` क्लास से फ़ाइल लोड करें, `getCommentAuthors` से मिले `ICommentAuthor` ऑब्जेक्ट पर इटरेट करें, उनकी टिप्पणियाँ हटाएँ और अपडेट किया गया प्रेज़ेंटेशन सहेजें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT से एनोटेशन हटाएँ – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java के ज़रिए PPT से टिप्पणियाँ कैसे हटाएँ" intro="PPT प्रेज़ेंटेशन से टिप्पणियाँ और टिप्पणी लेखक हटाने के लिए इन चरणों का पालन करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for Java इंस्टॉल करें। देखें [इंस्टॉलेशन](https://docs.aspose.com/slides/java/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT फ़ाइल को `Presentation` क्लास से लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getCommentAuthors` से मिले `ICommentAuthor` ऑब्जेक्ट पर इटरेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर लेखक की टिप्पणियाँ `getComments().clear()` से हटाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}टिप्पणी लेखक संग्रह खाली करें और अपडेट की गई PPT फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides से निर्मित" title="PPT टिप्पणियाँ ऑनलाइन हटाएँ" description="मुफ़्त Aspose.Slides Annotation ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Annotation खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टिप्पणियाँ कैसे हटाता है।
- अपनी PPT फ़ाइल से सभी टिप्पणियाँ हटाएँ।
- साफ़ की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="एनोटेशन के लिए अन्य समर्थित फ़ॉर्मेट" subTitle="Java के साथ, आप अन्य फ़ॉर्मेट से भी एनोटेशन हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
