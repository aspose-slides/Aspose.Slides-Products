---
title: C++ में SVG को PNG में बदलें
url: /hi/cpp/conversion/svg-to-png/
keywords: SVG से PNG, SVG को PNG में बदलें, C++ API, C++ लाइब्रेरी, SVG, PNG
description: C++ में SVG को PNG में बदलें। SVG फ़ाइलों को PNGs में कनवर्ट करने के लिए C++ लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ में SVG को PNG में बदलें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म C++ लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, विलय करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="C++ में SVG को PNG में बदलें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली C++ लाइब्रेरी है। इसके अलावा, यह SVG को PNG में बदलने के लचीले तरीके प्रदान करता है। C++** के लिए **Aspose.Slides का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन SVG को PNG फ़ाइलों में C++ कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for C++ SVG फ़ाइलों को PNG फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको SVG को PNG और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ का उपयोग करके SVG को PNG में बदलें" %}}
SVG को PNG में बदलने के लिए, आपको SVG फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे PNG के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="SVG को PNG में बदलने के लिए C++ कोड" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ API के लिए Aspose.Slides का उपयोग करके SVG को PNG में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="C++ में SVG को PNG में बदलने के लिए ये कदम हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने सी ++ प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
स्रोत SVG फ़ाइलें C++ में खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को PNG फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="SVG को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप SVG को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}