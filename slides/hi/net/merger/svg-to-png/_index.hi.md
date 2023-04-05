---
title: सी # में एसवीजी को पीएनजी में मर्ज करें
url: /hi/net/merger/svg-to-png/
keywords: SVG को PNG में मर्ज करें, SVG को PNG में, SVG को PNG में मिलाएँ, SVG को PNG में मिलाएँ, C# API, .NET लाइब्रेरी
description: सी # में एसवीजी को पीएनजी में मर्ज करें। SVG और PNG फ़ाइलों को संयोजित करने के लिए .NET लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="सी # में एसवीजी को पीएनजी में मर्ज करें" h2="NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर C# कोड का उपयोग करके SVG को PNG छवियों में मर्ज करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके SVG को PNG में मर्ज करें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) एक शक्तिशाली .NET लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, छवियों और अन्य फ़ाइलों को मर्ज करने और उनमें हेरफेर करने के लिए किया जाता है। जब आप एसवीजी को पीएनजी में विलय करते हैं, तो आप पीएनजी चित्र प्राप्त करने के लिए एसवीजी छवियों को प्रभावी ढंग से जोड़ रहे हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="सी # में एसवीजी को पीएनजी में मर्ज करें" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ SVG को PNG फ़ाइलों में शीघ्रता से मर्ज कर सकते हैं

{{% blocks/products/pf/agp/code-block title="एसवीजी को पीएनजी में विलय के लिए सी # कोड" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    ISvgImage svgImage = new SvgImage("doc.svg");
    IPPImage image = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    ISvgImage svgImage2 = new SvgImage("doc.svg");
    IPPImage image2 = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="सी # में एसवीजी को पीएनजी में विलय कैसे करें" >}}


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
उन एसवीजी फाइलों को लोड करें जिन्हें आप मर्ज करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी PNG छवि सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="पीडीएफ फाइलों को ऑनलाइन मर्ज करें" sectionDescription="[पायथन में पीडीएफ को कैसे मर्ज करें](https://products.aspose.com/slides/hi/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}