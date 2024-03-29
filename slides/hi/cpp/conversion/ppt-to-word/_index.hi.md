---
title: C++ में PPT को Word में बदलें
url: /hi/cpp/conversion/ppt-to-word/
keywords: PPT को Word में, PPT को Word में, PPT को DOC में, PowerPoint को Word में, C++ API, C++ लाइब्रेरी, CPP में बदलें
description: C++ में PPT को Word में बदलें। PowerPoint को Word में बदलने के लिए C++ लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ में PPT को Word में बदलें" h2="Microsoft PowerPoint या Office के बिना C++ कोड का उपयोग करके PowerPoint को Word में परिवर्तित करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म C++ API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides और Aspose.Words का उपयोग करके PowerPoint को Word में कनवर्ट करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) और [**Aspose.Words for C++**](https://products.aspose.com/ Words/cpp/) शक्तिशाली C++ लाइब्रेरी हैं जिनका उपयोग PowerPoint प्रस्तुतियों, Word दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर करने और उन्हें बदलने के लिए किया जाता है। जब आप PowerPoint को Word में कनवर्ट करते हैं, तो आप अनिवार्य रूप से किसी Word दस्तावेज़ में किसी प्रस्तुति की स्लाइड्स की सामग्री को पृष्ठों पर ले जा रहे होते हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C++ में PowerPoint को Word में बदलें" %}}
आप कोड की केवल कुछ पंक्तियों के साथ PPT को Word में शीघ्रता से रूपांतरित कर सकते हैं

{{% blocks/products/pf/agp/code-block title="PowerPoint को Word में बदलने के लिए C++ कोड" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पीपीटी को वर्ड में कैसे बदलें" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
C++** के लिए **Aspose.Slides और C++** के लिए **Aspose.Words इंस्टॉल करें 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास और डॉक क्लास का एक उदाहरण बनाएँ।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
उस PPT प्रस्तुति को लोड करें जिसे आप Word में बदलना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
स्लाइड्स की सामग्री के आधार पर चित्र और टेक्स्ट उत्पन्न करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी Word दस्तावेज़ को सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप PowerPoint को अन्य स्वरूपों में फ़ाइलों में भी रूपांतरित कर सकते हैं" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}