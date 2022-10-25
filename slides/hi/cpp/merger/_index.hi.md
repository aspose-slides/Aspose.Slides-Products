---
title: C++ का उपयोग करके PDF, PPT, PPTX और कई अन्य फ़ाइल स्वरूपों को मर्ज करें
url: /hi/cpp/merger/
keywords: मर्ज, जॉइन, पॉवरपॉइंट, प्रेजेंटेशन, C++, Aspose
description: C++ PPT, PPTX, ODP, PDF, PNG, JPG और कई अन्य फाइलों को मर्ज करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ में Powerpoint, PDF, PPT या अन्य दस्तावेज़ों को एक साथ मर्ज करें" h2="पीपीटी, पीपीटीएक्स, पीडीएफ, पीएनजी, जेपीईजी और अन्य प्रारूपों को मर्ज करने के लिए हाई-स्पीड सी ++ लाइब्रेरी।" >}}

{{% blocks/products/pf/feature-page-section h2="C++ का उपयोग करके PPT, PPTX, PDF को मर्ज करें" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hi/cpp/) प्रेजेंटेशन फाइल बनाने और उसमें हेरफेर करने के लिए एक शक्तिशाली C++ लाइब्रेरी है। इसके अलावा, यह कई पीपीटी / पीपीटीएक्स प्रस्तुतियों को संयोजित करने के लचीले तरीके प्रदान करता है। जब आप एक प्रस्तुति को दूसरे में मर्ज करते हैं, तो आप एक फ़ाइल प्राप्त करने के लिए उनकी स्लाइड्स को एक प्रस्तुति में प्रभावी रूप से संयोजित कर रहे हैं। Aspose.Slides आपको दो प्रस्तुतियों को अलग-अलग तरीकों से मर्ज करने की अनुमति देता है। आप गुणवत्ता या डेटा के नुकसान के बारे में चिंता किए बिना प्रस्तुतियों को उनके सभी आकारों, शैलियों, ग्रंथों, स्वरूपण, टिप्पणियों, एनिमेशन आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="पावरपॉइंट प्रेजेंटेशन को C++ में मर्ज करें" %}}
PowerPoint प्रस्तुतियों को मर्ज करने के लिए, आपको स्लाइडों को एक प्रस्तुति से दूसरी प्रस्तुति में क्लोन करना होगा।

{{% blocks/products/pf/agp/code-block title="C++ का उपयोग करके PPTX फाइलों को मर्ज करें" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ . का उपयोग करके स्लाइड मास्टर के साथ प्रस्तुतियों को मर्ज करें" %}}
यह C++ कोड दर्शाता है कि कैसे कई प्रस्तुतियों को एक में मिला दिया जाता है और स्लाइड मास्टर प्रस्तुति टेम्पलेट से शैलियों को लागू किया जाता है। तो, परिणाम प्रस्तुति एक ही स्रोत स्वरूपण रखेगी और इसमें किसी अन्य प्रस्तुति की मास्टर स्लाइड से स्वरूपण होगा।

{{% blocks/products/pf/agp/code-block title="सी++ में एकाधिक पीपीटी को सिंगल में मर्ज करें" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for C++ API का उपयोग करके प्रस्तुतियों को कैसे मर्ज करें?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये दो पीपीटीएक्स फाइलों को मर्ज करने और सी ++ में पीडीएफ के रूप में परिणाम सहेजने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://docs.aspose.com/slides/cpp/installation/) इंस्टॉल करें। 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने सी ++ प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
स्रोत PPTX फ़ाइलें C++ में खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**AddClone** विधि का उपयोग करके PPTX फाइलों को मिलाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति सहेजें और एकल पीडीएफ फाइल के रूप में परिणाम प्राप्त करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="मर्ज करने के लिए अन्य समर्थित प्रारूप" subTitle="आप अन्य फ़ाइल स्वरूपों को भी जोड़ सकते हैं। नीचे अन्य समर्थित प्रारूप देखें।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}