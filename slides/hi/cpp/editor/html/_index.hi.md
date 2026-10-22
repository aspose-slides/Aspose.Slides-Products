---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: HTML को C++ में संपादित करें
url: /hi/cpp/editor/html/
keywords: HTML, HTML, C++ API, C++ लाइब्रेरी संपादित करें
description: HTML को C++ में संपादित करें। HTML फ़ाइल संपादित करने के लिए C++ लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="HTML को C++ में संपादित करें" h2="C++ कोड का उपयोग करके HTML के संपादन के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML को C++ में संपादित करें" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ HTML दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML संपादित करने के लिए C++ कोड" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"page.html", SaveFormat::Html5);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके HTML संपादित करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) एक शक्तिशाली C++ लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, HTML दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर और संपादित करने के लिए किया जाता है। आप किसी HTML दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="HTML को C++ में कैसे संपादित करें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++** के लिए **Aspose.Slides इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/cpp/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वह HTML दस्तावेज़ लोड करें जिसे आप संपादित करना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पाठ की एक नई पंक्ति जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिवर्तित HTML फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
