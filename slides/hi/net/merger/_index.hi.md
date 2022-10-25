---
title: C# का उपयोग करके PDF, PPT, PPTX और कई अन्य फ़ाइल स्वरूपों को मर्ज करें
url: /hi/net/merger/
keywords: मर्ज, जॉइन, पॉवरपॉइंट, प्रेजेंटेशन, C#, .NET, Aspose
description: सी # पीपीटी, पीपीटीएक्स, ओडीपी, पीडीएफ, पीएनजी, जेपीजी और कई अन्य फाइलों में कई फाइलों को मर्ज करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# में पावरपॉइंट, पीडीएफ, पीपीटी या अन्य दस्तावेजों को एक साथ मिलाएं" h2="पीपीटी, पीपीटीएक्स, पीडीएफ, पीएनजी, जेपीईजी और अन्य प्रारूपों को मर्ज करने के लिए हाई-स्पीड सी # लाइब्रेरी।" >}}

{{% blocks/products/pf/feature-page-section h2="C# का उपयोग करके PPT, PPTX, PDF को मर्ज करें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) प्रेजेंटेशन फाइल बनाने और उसमें हेरफेर करने के लिए एक शक्तिशाली C# लाइब्रेरी है। इसके अलावा, यह कई पीपीटी / पीपीटीएक्स प्रस्तुतियों को संयोजित करने के लचीले तरीके प्रदान करता है। जब आप एक प्रस्तुति को दूसरे में मर्ज करते हैं, तो आप एक फ़ाइल प्राप्त करने के लिए उनकी स्लाइड्स को एक प्रस्तुति में प्रभावी रूप से संयोजित कर रहे हैं। Aspose.Slides आपको दो प्रस्तुतियों को अलग-अलग तरीकों से मर्ज करने की अनुमति देता है। आप गुणवत्ता या डेटा के नुकसान के बारे में चिंता किए बिना प्रस्तुतियों को उनके सभी आकारों, शैलियों, ग्रंथों, स्वरूपण, टिप्पणियों, एनिमेशन आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # में पावरपॉइंट प्रेजेंटेशन मर्ज करें" %}}
PowerPoint प्रस्तुतियों को मर्ज करने के लिए, आपको स्लाइडों को एक प्रस्तुति से दूसरी प्रस्तुति में क्लोन करना होगा।

{{% blocks/products/pf/agp/code-block title="सी # का उपयोग कर पीपीटीएक्स फाइलों को मर्ज करें" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # का उपयोग करके स्लाइड मास्टर के साथ प्रस्तुतिकरण मर्ज करें" %}}
यह सी # कोड दर्शाता है कि कैसे कई प्रस्तुतियों को एक में मर्ज करें और स्लाइड मास्टर प्रस्तुति टेम्पलेट से शैलियों को लागू करें। तो, परिणाम प्रस्तुति एक ही स्रोत स्वरूपण रखेगी और इसमें किसी अन्य प्रस्तुति की मास्टर स्लाइड से स्वरूपण होगा।

{{% blocks/products/pf/agp/code-block title="सी # में एकाधिक पीपीटी को सिंगल में मर्ज करें" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API के लिए Aspose.Slides का उपयोग करके प्रस्तुतियों को कैसे मर्ज करें?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये दो पीपीटीएक्स फाइलों को मर्ज करने और परिणाम को पीडीएफ के रूप में .NET में सहेजने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for .NET**](https://docs.aspose.com/slides/net/installation/) इंस्टॉल करें। 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने सी # प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
सी # में स्रोत पीपीटीएक्स फाइलें खोलें।
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}