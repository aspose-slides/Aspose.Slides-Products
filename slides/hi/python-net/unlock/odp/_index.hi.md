---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python के साथ ODP प्रेजेंटेशन अनलॉक करें
url: /hi/python-net/unlock/odp/
description: Python के साथ ODP प्रेजेंटेशन से एन्क्रिप्शन और राइट प्रोटेक्शन हटाएं।
keywords: ODP अनलॉक करें, ODP से पासवर्ड हटाएं, ODP एन्क्रिप्शन हटाएं, ODP से राइट प्रोटेक्शन हटाएं
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python के साथ ODP प्रेजेंटेशन अनलॉक करें" h2="ऐसे Python एप्लिकेशन बनाएं जो Aspose.Slides के साथ ODP प्रेजेंटेशन से ओपनिंग पासवर्ड और राइट-प्रोटेक्शन सेटिंग्स हटाएं।" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python के साथ ODP से एन्क्रिप्शन और राइट प्रोटेक्शन हटाएं" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/hi/python-net/) के साथ आप वह एन्क्रिप्शन हटा सकते हैं जिसके कारण ODP प्रेजेंटेशन खोलने के लिए पासवर्ड चाहिए, या उसकी राइट-प्रोटेक्शन सेटिंग हटा सकते हैं। एन्क्रिप्टेड फ़ाइल खोलने के लिए `LoadOptions` के ज़रिए मौजूदा पासवर्ड दें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP प्रेजेंटेशन से एन्क्रिप्शन हटाएं – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP प्रेजेंटेशन से राइट प्रोटेक्शन हटाएं – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python के साथ ODP से सुरक्षा कैसे हटाएं" intro="ODP प्रेजेंटेशन से सुरक्षा हटाने के लिए ये चरण अपनाएं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}एन्क्रिप्टेड ODP फ़ाइल के लिए `LoadOptions` में मौजूदा पासवर्ड सेट करें, फिर `Presentation` से फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ओपनिंग पासवर्ड हटाने के लिए `ProtectionManager.remove_encryption` कॉल करें, या राइट प्रोटेक्शन हटाने के लिए `ProtectionManager.remove_write_protection` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणामी प्रेजेंटेशन को `SaveFormat.ODP` के साथ सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides से निर्मित" title="ODP फ़ाइलें ऑनलाइन अनलॉक करें" description="मुफ़्त Aspose.Slides Unlock ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी ODP फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Unlock खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides सुरक्षा कैसे हटाता है।
- अपनी ODP फ़ाइल से पासवर्ड या राइट प्रोटेक्शन हटाएं।
- अनलॉक की गई फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अनलॉक करने के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="अन्य समर्थित प्रेजेंटेशन फ़ॉर्मेट से सुरक्षा हटाने के लिए Python का उपयोग करें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
