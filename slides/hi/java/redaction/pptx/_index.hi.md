---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java का उपयोग करके PPTX प्रेज़ेंटेशन फ़ाइलों में गोपनीय जानकारी छिपाएँ
url: /hi/java/redaction/pptx/
description: Aspose.Slides for Java का उपयोग करके Java में PPTX प्रेज़ेंटेशन में टेक्स्ट खोजें और बदलें।
keywords: PPTX में गोपनीय जानकारी छिपाएँ, PPTX में टेक्स्ट खोजें और बदलें, PPTX प्रेज़ेंटेशन अपडेट करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java का उपयोग करके PPTX में गोपनीय जानकारी छिपाएँ" h2="सर्वर-साइड API का उपयोग करके प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट खोजने और बदलने वाले Java एप्लिकेशन बनाएँ।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के माध्यम से PPTX प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ" variant="code" %}}

[Aspose.Slides for Java](/slides/hi/java/) का उपयोग करके, आप PPTX प्रेज़ेंटेशन में टेक्स्ट खोज और बदल सकते हैं। प्रेज़ेंटेशन में खोजने और मेल खाने वाले टेक्स्ट को नए मान से बदलने के लिए `SlideUtil.findAndReplaceText` मेथड का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java का उपयोग करके PPTX प्रेज़ेंटेशन में गोपनीय जानकारी छिपाएँ" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java के माध्यम से PPTX में गोपनीय जानकारी कैसे छिपाएँ" intro="PPTX प्रेज़ेंटेशन में गोपनीय जानकारी छिपाने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास के साथ PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}टेक्स्ट खोजने और बदलने के लिए `SlideUtil.findAndReplaceText` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपडेट की गई प्रेज़ेंटेशन को `SaveFormat.Pptx` के साथ सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलों में ऑनलाइन गोपनीय जानकारी छिपाएँ" description="मुफ़्त Aspose.Slides Redaction ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Redaction खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट को कैसे खोजता और बदलता है।
- अपनी PPTX फ़ाइल में टेक्स्ट खोजें और बदलें, रेगुलर एक्सप्रेशन सहित।
- संसाधित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="गोपनीय जानकारी छिपाने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="Java का उपयोग करके, आप निम्न फ़ॉर्मेट में भी गोपनीय जानकारी छिपा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
