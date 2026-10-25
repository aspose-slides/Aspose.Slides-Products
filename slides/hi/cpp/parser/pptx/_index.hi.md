---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2290
title: C++ से PPTX प्रेज़ेंटेशन से टेक्स्ट निकालें
url: /hi/cpp/parser/pptx/ 
description: C++ में PPTX प्रेज़ेंटेशन से टेक्स्ट निकालें। स्लाइड, टेक्स्ट फ़्रेम, पैराग्राफ़ और टेक्स्ट हिस्सों को पार्स करने के लिए Aspose.Slides for C++ का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ में PPTX प्रेज़ेंटेशन पार्स करें" h2="Microsoft PowerPoint के बिना प्रेज़ेंटेशन स्लाइड से टेक्स्ट निकालने के लिए Aspose.Slides for C++ का उपयोग करें।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ से PPTX फ़ाइल पार्स करें" %}}

PPTX प्रेज़ेंटेशन फ़ाइलें पार्स करने और स्लाइड से टेक्स्ट निकालने के लिए Aspose.Slides for C++ का उपयोग करें। API स्लाइड का टेक्स्ट `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` और `IPortion` के ज़रिए उपलब्ध कराता है, इसलिए आप Microsoft PowerPoint को ऑटोमेट किए बिना टेक्स्ट पढ़ सकते हैं। NuGet से [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) पैकेज इंस्टॉल करें या Package Manager Console में नीचे दिया गया कमांड चलाएँ।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कमांड" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX फ़ाइलें पार्स करें – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ में PPTX फ़ाइलें कैसे पार्स करें" intro="Aspose.Slides for C++ से PPTX फ़ाइलों से टेक्स्ट निकालें।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` क्लास से PPTX फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil::GetAllTextBoxes` से पहली स्लाइड के `ITextFrame` ऑब्जेक्ट प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ITextFrame` ऑब्जेक्ट पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर `ITextFrame` में `IParagraph` ऑब्जेक्ट पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}हर `IParagraph` में `IPortion` ऑब्जेक्ट पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_Text` से टेक्स्ट पढ़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएँ" intro="Aspose.Slides for C++ प्रमुख डेस्कटॉप और सर्वर प्लेटफ़ॉर्म का समर्थन करता है। सुनिश्चित करें कि आपके प्रोजेक्ट में निम्नलिखित पूर्वापेक्षाएँ हैं।" %}}

-  समर्थित C++ रनटाइम वाला Microsoft Windows, Linux, macOS या कोई अन्य संगत ऑपरेटिंग सिस्टम।
-  आपके प्रोजेक्ट में संदर्भित Aspose.Slides for C++ लाइब्रेरी।

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides से निर्मित" title="टेक्स्ट और इमेज ऑनलाइन निकालें" description="मुफ़्त Aspose.Slides Parser ऐप [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPTX फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Parser खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलें कैसे पढ़ता है।
- एक PPTX फ़ाइल अपलोड करें और उसका टेक्स्ट और इमेज पाएँ।
- सब कुछ एक ZIP आर्काइव के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

A PPTX file is a Microsoft PowerPoint Open XML presentation file. It stores slides, text, images, formatting, animations, and other presentation content in a zipped XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="पार्सिंग के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="C++ से आप अन्य प्रेज़ेंटेशन फ़ॉर्मैट भी पार्स कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/parser/odp/" name="ODP" description="OpenDocument प्रेज़ेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/cpp/parser/ppt/" name="PPT" description="PowerPoint 97-2003 प्रेज़ेंटेशन" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
