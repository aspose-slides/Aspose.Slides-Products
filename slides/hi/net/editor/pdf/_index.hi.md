---
title: पीडीएफ को सी # में संपादित करें
url: /hi/net/editor/pdf/
keywords: PDF, PDF, C# API, .NET लाइब्रेरी संपादित करें
description: पीडीएफ को सी # में संपादित करें। PDF दस्तावेज़ संपादित करने के लिए .NET लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पीडीएफ को सी # में संपादित करें" h2="NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर C# कोड का उपयोग करके PDF संपादित करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PDF संपादित करें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) एक शक्तिशाली .NET लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, PDF दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर और संपादित करने के लिए किया जाता है। आप किसी PDF दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="पीडीएफ को सी # में संपादित करें" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PDF दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{% blocks/products/pf/agp/code-block title="पीडीएफ संपादित करने के लिए सी # कोड" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पीडीएफ को सी # में कैसे संपादित करें" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** इंस्टॉल करें। [**इंस्टॉलेशन**](https://docs.aspose.com/slides/net/installation/) देखें।
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}