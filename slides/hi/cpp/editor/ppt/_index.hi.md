---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: पीपीटी को सी ++ में संपादित करें
url: /hi/cpp/editor/ppt/
keywords: पीपीटी संपादित करें, पावरपॉइंट, पीपीटी, पावरपॉइंट, सी ++ एपीआई, सी ++ लाइब्रेरी संपादित करें
description: पीपीटी को सी ++ में संपादित करें। PowerPoint प्रस्तुति को संपादित करने के लिए C++ लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="पीपीटी को सी ++ में संपादित करें" h2="C++ कोड का उपयोग करके PPT संपादित करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="पीपीटी को सी ++ में संपादित करें" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PPT दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="पीपीटी संपादित करने के लिए सी++ कोड" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके पीपीटी संपादित करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) एक शक्तिशाली C++ लाइब्रेरी है जिसका उपयोग प्रस्तुतियों में हेरफेर करने और संपादित करने के लिए किया जाता है। आप पीपीटी प्रस्तुति में पाठ की एक नई पंक्ति जोड़कर इसे संपादित कर सकते हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ में PPT को कैसे संपादित करें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++** के लिए **Aspose.Slides इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/cpp/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पीपीटी प्रस्तुति लोड करें जिसे आप संपादित करना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पाठ की एक नई पंक्ति जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिवर्तित PowerPoint फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलें ऑनलाइन संपादित करें" description="मुफ़्त Aspose.Slides Editor ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Editor खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलों को कैसे संभालता है।
- अपनी PPTX फ़ाइलें अपलोड करें और तुरंत संपादित करें।
- संपादित फ़ाइल को सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
