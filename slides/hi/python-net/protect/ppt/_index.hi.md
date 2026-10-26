---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python के साथ PPT प्रेजेंटेशन फ़ाइलें सुरक्षित करें
url: /hi/python-net/protect/ppt/
description: Python के साथ PPT प्रेजेंटेशन एन्क्रिप्ट करें या राइट प्रोटेक्शन सेट करें।
keywords: PPT राइट प्रोटेक्शन, Python से PPT एन्क्रिप्ट करें, PPT प्रेजेंटेशन लॉक करें, Python से PPT सुरक्षित करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python के साथ PPT प्रेजेंटेशन सुरक्षित करें" h2="ऐसे Python एप्लिकेशन बनाएं जो Aspose.Slides के साथ प्रेजेंटेशन एन्क्रिप्ट करें या राइट प्रोटेक्शन सेट करें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python के साथ PPT प्रेजेंटेशन सुरक्षित करें" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/hi/python-net/) दो अलग-अलग सुरक्षा तंत्र प्रदान करता है। PPT प्रेजेंटेशन को एन्क्रिप्ट करने और उसे खोलने के लिए पासवर्ड ज़रूरी बनाने हेतु `ProtectionManager.encrypt` कॉल करें। वैकल्पिक रूप से, फ़ाइल एन्क्रिप्ट किए बिना बदलाव से रोकने के लिए `ProtectionManager.set_write_protection` कॉल करें। उपयोगकर्ता फिर भी राइट-प्रोटेक्टेड प्रेजेंटेशन खोल सकता है और बदलाव किसी दूसरी फ़ाइल में सेव कर सकता है।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT प्रेजेंटेशन एन्क्रिप्ट करें – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT प्रेजेंटेशन पर राइट प्रोटेक्शन सेट करें – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python के साथ PPT कैसे सुरक्षित करें" intro="PPT फ़ाइल सुरक्षित करने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से PPT फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}खोलने के लिए पासवर्ड ज़रूरी बनाने हेतु `ProtectionManager.encrypt` का, या बदलाव से रोकने के लिए `ProtectionManager.set_write_protection` का उपयोग करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}सुरक्षित प्रेजेंटेशन को `SaveFormat.PPT` के साथ PPT के रूप में सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides से निर्मित" title="PPT फ़ाइलों को ऑनलाइन पासवर्ड से सुरक्षित करें" description="मुफ़्त Aspose.Slides Lock ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Lock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रेजेंटेशन को कैसे सुरक्षित करता है।
- अपनी PPT फ़ाइल खोलने या संपादित करने के लिए पासवर्ड सेट करें।
- सुरक्षित फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="सुरक्षा के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="अन्य समर्थित प्रेजेंटेशन फ़ॉर्मेट सुरक्षित करने के लिए Python का उपयोग करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
