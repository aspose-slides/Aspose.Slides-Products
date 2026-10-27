---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जेपीजी छवियों को सी ++ में मर्ज करें
url: /hi/cpp/merger/jpg-to-jpg/
keywords: जेपीजी, जेपीईजी को जेपीजी में मर्ज करें, जेपीजी से जुड़ें, जेपीजी, सी++ एपीआई, सी++ लाइब्रेरी को मिलाएं
description: जेपीजी को जेपीजी में सी ++ में मर्ज करें। जेपीजी फाइलों को गठबंधन करने के लिए सी ++ लाइब्रेरी एपीआई का प्रयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JPG को C++ में मर्ज करें" h2="C++ कोड का उपयोग करके JPG छवियों को मर्ज करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी" related="PNG,HTML,IMAGE,JPG,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जेपीजी को सी ++ में जेपीईजी में मर्ज करें" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ JPG फ़ाइलों को जल्दी से मर्ज कर सकते हैं

{{< blocks/products/pf/slides-design-update-10-2026/code title="जेपीजी को जेपीजी में विलय करने के लिए सी ++ कोड" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.jpg"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.jpg"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.jpg", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Jpeg());
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके JPG को JPG में मर्ज करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) एक शक्तिशाली C++ लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, छवियों और अन्य फ़ाइलों को मर्ज और हेरफेर करने के लिए किया जाता है। जब आप जेपीजी को जेपीजी में मर्ज करते हैं, तो आप प्रभावी रूप से एक तस्वीर प्राप्त करने के लिए दो छवियों को जोड़ रहे हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="JPG को C++ में कैसे मर्ज करें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++** के लिए **Aspose.Slides इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/cpp/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}उन जेपीजी फाइलों को लोड करें जिन्हें आप पिक्चर फ्रेम के रूप में मर्ज करना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणामी JPG छवि को सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides से निर्मित" title="JPG फ़ाइलों को ऑनलाइन मर्ज करें" description="मुफ़्त Aspose.Slides Merger ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी JPG फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Merger खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides फ़ाइलों को कैसे मर्ज करता है।
- कई JPG फ़ाइलें अपलोड करें और उन्हें एक में मिलाएँ।
- मर्ज किया गया परिणाम एक फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
