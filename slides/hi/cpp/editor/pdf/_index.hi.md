---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: सी ++ में पीडीएफ संपादित करें
url: /hi/cpp/editor/pdf/
keywords: पीडीएफ, पीडीएफ, सी ++ एपीआई, सी ++ लाइब्रेरी संपादित करें
description: सी ++ में पीडीएफ संपादित करें। पीडीएफ दस्तावेज़ संपादित करने के लिए सी ++ लाइब्रेरी एपीआई का प्रयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="सी ++ में पीडीएफ संपादित करें" h2="C++ कोड का उपयोग करके PDF संपादित करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="सी ++ में पीडीएफ संपादित करें" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PDF दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="पीडीएफ संपादित करने के लिए सी ++ कोड" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके PDF संपादित करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) एक शक्तिशाली C++ लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, PDF दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर और संपादित करने के लिए किया जाता है। आप किसी PDF दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="सी ++ में पीडीएफ कैसे संपादित करें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++** के लिए **Aspose.Slides इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/cpp/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वह पीडीएफ दस्तावेज़ लोड करें जिसे आप संपादित करना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पाठ की एक नई पंक्ति जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिवर्तित पीडीएफ फाइल को सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलें ऑनलाइन संपादित करें" description="मुफ़्त Aspose.Slides Editor ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Editor खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलों को कैसे संभालता है।
- अपनी PPTX फ़ाइलें अपलोड करें और तुरंत संपादित करें।
- संपादित फ़ाइल को सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
