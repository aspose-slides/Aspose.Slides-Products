---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ से PPTX प्रेज़ेंटेशन में वॉटरमार्क जोड़ें
url: /hi/cpp/watermark/pptx/
description: C++ में PPTX प्रेज़ेंटेशन में टेक्स्ट या इमेज वॉटरमार्क जोड़ें। प्रेज़ेंटेशन स्लाइड पर वॉटरमार्क लगाने के लिए Aspose.Slides for C++ का उपयोग करें।
keywords: PPTX में वॉटरमार्क जोड़ें, PPTX में टेक्स्ट वॉटरमार्क जोड़ें, PPTX में इमेज वॉटरमार्क जोड़ें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ से PPTX प्रेज़ेंटेशन में वॉटरमार्क जोड़ें – उदाहरण" h2="Microsoft PowerPoint के बिना प्रेज़ेंटेशन फ़ाइलों में टेक्स्ट या इमेज वॉटरमार्क जोड़ने के लिए Aspose.Slides for C++ का उपयोग करें।" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ के ज़रिए PPTX प्रेज़ेंटेशन में वॉटरमार्क जोड़ें" variant="code" %}}

Aspose.Slides for C++ से आप PPTX प्रेज़ेंटेशन में टेक्स्ट या इमेज वॉटरमार्क जोड़ सकते हैं। `AddAutoShape` से मास्टर स्लाइड पर वॉटरमार्क शेप जोड़ें, `AddTextFrame` से टेक्स्ट जोड़ें या `File::ReadAllBytes` और `AddImage` से लोड की गई इमेज से शेप भरें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ से PPTX में टेक्स्ट वॉटरमार्क जोड़ें" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ से PPTX प्रेज़ेंटेशन में इमेज वॉटरमार्क जोड़ें" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ से PPTX में वॉटरमार्क कैसे जोड़ें" intro="PPTX फ़ाइलों में टेक्स्ट या इमेज वॉटरमार्क जोड़ने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Masters` कलेक्शन से मास्टर स्लाइड चुनें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddAutoShape` मेथड से वॉटरमार्क शेप जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddTextFrame` मेथड से वॉटरमार्क टेक्स्ट जोड़ें या `AddImage` से पिक्चर फ़िल सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Pptx` से वॉटरमार्क वाली फ़ाइल सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides से निर्मित" title="PPTX फ़ाइलों में ऑनलाइन वॉटरमार्क जोड़ें" description="मुफ़्त Aspose.Slides Watermark ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Watermark खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides वॉटरमार्क कैसे जोड़ता है।
- अपनी PPTX फ़ाइल में टेक्स्ट या इमेज वॉटरमार्क जोड़ें।
- वॉटरमार्क वाली फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="वॉटरमार्क के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="C++ से आप निम्नलिखित फ़ॉर्मैट में भी वॉटरमार्क जोड़ सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
