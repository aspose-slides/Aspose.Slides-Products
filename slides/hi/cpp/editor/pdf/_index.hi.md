---
title: सी ++ में पीडीएफ संपादित करें
url: /hi/cpp/editor/pdf/
keywords: पीडीएफ, पीडीएफ, सी ++ एपीआई, सी ++ लाइब्रेरी संपादित करें
description: सी ++ में पीडीएफ संपादित करें। पीडीएफ दस्तावेज़ संपादित करने के लिए सी ++ लाइब्रेरी एपीआई का प्रयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="सी ++ में पीडीएफ संपादित करें" h2="C++ कोड का उपयोग करके PDF संपादित करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PDF संपादित करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) एक शक्तिशाली C++ लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, PDF दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर और संपादित करने के लिए किया जाता है। आप किसी PDF दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="सी ++ में पीडीएफ संपादित करें" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PDF दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{% blocks/products/pf/agp/code-block title="पीडीएफ संपादित करने के लिए सी ++ कोड" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="सी ++ में पीडीएफ कैसे संपादित करें" >}}


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
वह पीडीएफ दस्तावेज़ लोड करें जिसे आप संपादित करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ की एक नई पंक्ति जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिवर्तित पीडीएफ फाइल को सेव करें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}