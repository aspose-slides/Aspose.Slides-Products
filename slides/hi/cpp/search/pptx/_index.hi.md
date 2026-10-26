---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ का उपयोग करके PPTX प्रेज़ेंटेशन में टेक्स्ट खोजें
url: /hi/cpp/search/pptx/
description: C++ में PPTX प्रेज़ेंटेशन में टेक्स्ट खोजें। प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट ढूँढने के लिए Aspose.Slides for C++ का उपयोग करें।
keywords: PPTX में शब्द खोजें, PPTX में टेक्स्ट ढूँढें, PPTX प्रेज़ेंटेशन का टेक्स्ट खोजें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ का उपयोग करके PPTX में टेक्स्ट खोजें" h2="Microsoft PowerPoint के बिना प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट ढूँढने के लिए Aspose.Slides for C++ का उपयोग करें।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ के माध्यम से PPTX प्रेज़ेंटेशन में टेक्स्ट खोजें" variant="code" %}}

Aspose.Slides for C++ आपको PPTX प्रेज़ेंटेशन में टेक्स्ट खोजने देता है। किसी स्लाइड के टेक्स्ट फ़्रेम इकट्ठा करने के लिए `SlideUtil::GetAllTextBoxes` का उपयोग करें, फिर जाँचें कि उनके टेक्स्ट में आवश्यक वाक्यांश है या नहीं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ के साथ PPTX प्रेज़ेंटेशन में टेक्स्ट खोजें" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ के माध्यम से PPTX में टेक्स्ट कैसे खोजें" intro="PPTX प्रेज़ेंटेशन में टेक्स्ट खोजने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास के साथ PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Slides` से आवश्यक स्लाइड प्राप्त करें और [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/) से उसके टेक्स्ट फ़्रेम प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}जाँचें कि हर फ़्रेम के टेक्स्ट में आवश्यक वाक्यांश है या नहीं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलों में ऑनलाइन टेक्स्ट खोजें" description="मुफ़्त Aspose.Slides Search ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Search खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides टेक्स्ट कैसे ढूँढता है।
- अपनी PPTX फ़ाइल में सादा टेक्स्ट या रेगुलर एक्सप्रेशन खोजें।
- मिले परिणामों को टेक्स्ट फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="खोज के लिए समर्थित अन्य फ़ॉर्मेट" subTitle="C++ का उपयोग करके, आप निम्न फ़ॉर्मेट में भी टेक्स्ट खोज सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
