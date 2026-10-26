---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java का उपयोग करके PPTX प्रेजेंटेशन फ़ाइलें अनलॉक करें
url: /hi/java/unlock/pptx/
description: Aspose.Slides for Java का उपयोग करके Java में PPTX प्रेजेंटेशन से पासवर्ड और राइट प्रोटेक्शन हटाएं।
keywords: PPTX राइट प्रोटेक्शन हटाएं, PPTX डिक्रिप्ट करें, PPTX प्रेजेंटेशन अनलॉक करें, PPTX की सुरक्षा हटाएं
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java का उपयोग करके PPTX अनलॉक करें" h2="ऐसे Java एप्लिकेशन बनाएं जो सर्वर-साइड API से प्रेजेंटेशन फ़ाइलों के पासवर्ड और राइट प्रोटेक्शन हटाएं।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java के ज़रिए PPTX प्रेजेंटेशन से सुरक्षा हटाना" variant="code" %}}

[Aspose.Slides for Java](/slides/hi/java/) के साथ आप PPTX प्रेजेंटेशन से एन्क्रिप्शन या राइट प्रोटेक्शन हटा सकते हैं। एन्क्रिप्टेड प्रेजेंटेशन खोलने के लिए `LoadOptions.setPassword` और सुरक्षा सेटिंग्स हटाने के लिए `ProtectionManager` की `removeEncryption` और `removeWriteProtection` मेथड का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java का उपयोग करके PPTX से पासवर्ड सुरक्षा हटाएं" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java का उपयोग करके PPTX प्रेजेंटेशन से राइट प्रोटेक्शन हटाएं" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java के ज़रिए PPTX से पासवर्ड कैसे हटाएं" intro="PPTX प्रेजेंटेशन से सुरक्षा हटाने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन एन्क्रिप्टेड होने पर `LoadOptions.setPassword` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` ऑब्जेक्ट की `removeEncryption` या `removeWriteProtection` मेथड कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अनलॉक किए गए प्रेजेंटेशन को `SaveFormat.Pptx` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलें ऑनलाइन अनलॉक करें" description="मुफ़्त Aspose.Slides Unlock ऐप [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Unlock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides सुरक्षा कैसे हटाता है।
- अपनी PPTX फ़ाइल से पासवर्ड या राइट प्रोटेक्शन हटाएं।
- अनलॉक की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अनलॉक करने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="Java का उपयोग करके आप निम्न फ़ॉर्मेट से भी सुरक्षा हटा सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
