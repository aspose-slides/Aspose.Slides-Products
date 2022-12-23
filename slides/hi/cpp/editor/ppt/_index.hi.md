---
title: पीपीटी को सी ++ में संपादित करें
url: /hi/cpp/editor/ppt/
keywords: पीपीटी संपादित करें, पावरपॉइंट, पीपीटी, पावरपॉइंट, सी ++ एपीआई, सी ++ लाइब्रेरी संपादित करें
description: पीपीटी को सी ++ में संपादित करें। PowerPoint प्रस्तुति को संपादित करने के लिए C++ लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पीपीटी को सी ++ में संपादित करें" h2="C++ कोड का उपयोग करके PPT संपादित करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके पीपीटी संपादित करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) एक शक्तिशाली C++ लाइब्रेरी है जिसका उपयोग प्रस्तुतियों में हेरफेर करने और संपादित करने के लिए किया जाता है। आप पीपीटी प्रस्तुति में पाठ की एक नई पंक्ति जोड़कर इसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="पीपीटी को सी ++ में संपादित करें" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PPT दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{% blocks/products/pf/agp/code-block title="पीपीटी संपादित करने के लिए सी++ कोड" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C++ में PPT को कैसे संपादित करें" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
C++** के लिए **Aspose.Slides इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/cpp/installation/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पीपीटी प्रस्तुति लोड करें जिसे आप संपादित करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ की एक नई पंक्ति जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिवर्तित PowerPoint फ़ाइल सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}