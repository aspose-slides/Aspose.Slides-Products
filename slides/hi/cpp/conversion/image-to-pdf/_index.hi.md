---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ में Image को PDF में बदलें
url: /hi/cpp/conversion/image-to-pdf/
keywords: Image से PDF, Image को PDF में बदलें, C++ API, C++ लाइब्रेरी, Image, PDF
description: C++ में Image को PDF में बदलें। Image फ़ाइलों को PDFs में कनवर्ट करने के लिए C++ लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ में Image को PDF में बदलें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, विलय करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ का उपयोग करके Image को PDF में बदलें" variant="code" %}}

Image को PDF में बदलने के लिए, आपको Image फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे PDF के रूप में सहेजना होगा।

{{< blocks/products/pf/slides-design-update-10-2026/code title="Image को PDF में बदलने के लिए C++ कोड" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ में Image को PDF में बदलें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली C++ लाइब्रेरी है। इसके अलावा, यह Image को PDF में बदलने के लचीले तरीके प्रदान करता है। C++** के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन Image को PDF फ़ाइलों में C++ कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for C++ Image फ़ाइलों को PDF फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको Image को PDF और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ API के लिए Aspose.Slides का उपयोग करके Image को PDF में कैसे बदलें" intro="C++ में Image को PDF में बदलने के लिए ये कदम हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) इंस्टॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपने सी ++ प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}स्रोत Image फ़ाइलें C++ में खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणाम को PDF फ़ाइल के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऑनलाइन कनवर्टर"
  description="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Image को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप Image को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/cpp/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
