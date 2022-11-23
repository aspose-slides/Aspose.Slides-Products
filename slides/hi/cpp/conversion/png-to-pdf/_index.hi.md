---
title: C++ में PNG को PDF में बदलें
url: /hi/cpp/conversion/png-to-pdf/
keywords: PNG से PDF, PNG को PDF में बदलें, C++ API, C++ लाइब्रेरी, PNG, PDF
description: C++ में PNG को PDF में बदलें। PNG फ़ाइलों को PDFs में कनवर्ट करने के लिए C++ लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ में PNG को PDF में बदलें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, विलय करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="C++ में PNG को PDF में बदलें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली C++ लाइब्रेरी है। इसके अलावा, यह PNG को PDF में बदलने के लचीले तरीके प्रदान करता है। C++** के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन PNG को PDF फ़ाइलों में C++ कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for C++ PNG फ़ाइलों को PDF फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको PNG को PDF और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ का उपयोग करके PNG को PDF में बदलें" %}}
PNG को PDF में बदलने के लिए, आपको PNG फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे PDF के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="PNG को PDF में बदलने के लिए C++ कोड" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ API के लिए Aspose.Slides का उपयोग करके PNG को PDF में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="C++ में PNG को PDF में बदलने के लिए ये कदम हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने सी ++ प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
स्रोत PNG फ़ाइलें C++ में खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को PDF फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PNG को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप PNG को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}