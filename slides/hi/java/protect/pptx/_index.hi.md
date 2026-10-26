---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java का उपयोग करके PPTX प्रेजेंटेशन फ़ाइलें सुरक्षित करें
url: /hi/java/protect/pptx/
description: Java में PPTX प्रेजेंटेशन सुरक्षित करें। प्रेजेंटेशन फ़ाइलें एन्क्रिप्ट करने और राइट प्रोटेक्शन सेट करने के लिए Aspose.Slides for Java का उपयोग करें।
keywords: PPTX राइट प्रोटेक्शन, PPTX फ़ाइल एन्क्रिप्ट करें, PPTX प्रेजेंटेशन लॉक करें, PPTX सुरक्षित करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java का उपयोग करके PPTX लॉक करें या पासवर्ड से सुरक्षित करें" h2="ऐसे Java एप्लिकेशन बनाएं जो सर्वर-साइड API से प्रेजेंटेशन फ़ाइलें सुरक्षित करें।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के ज़रिए PPTX प्रेजेंटेशन सुरक्षित करना" variant="code" %}}

[Aspose.Slides for Java](/slides/hi/java/) के साथ आप पासवर्ड सेट करके PPTX प्रेजेंटेशन को खुलने या बदले जाने से सुरक्षित कर सकते हैं। `encrypt` और `setWriteProtection` जैसी मेथड कॉल करने के लिए `Presentation` क्लास के `ProtectionManager` ऑब्जेक्ट का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java का उपयोग करके PPTX प्रेजेंटेशन एन्क्रिप्ट करें" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java का उपयोग करके PPTX प्रेजेंटेशन के लिए राइट प्रोटेक्शन सेट करें" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java के ज़रिए PPTX को पासवर्ड से कैसे सुरक्षित करें" intro="PPTX प्रेजेंटेशन सुरक्षित करने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` ऑब्जेक्ट की `encrypt` मेथड या `setWriteProtection` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सुरक्षित फ़ाइल को `SaveFormat.Pptx` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलों को ऑनलाइन पासवर्ड से सुरक्षित करें" description="मुफ़्त Aspose.Slides Lock ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Lock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रेजेंटेशन को कैसे सुरक्षित करता है।
- अपनी PPTX फ़ाइल खोलने या संपादित करने के लिए पासवर्ड सेट करें।
- सुरक्षित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="सुरक्षा के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="Java का उपयोग करके आप निम्न फ़ॉर्मेट भी सुरक्षित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
