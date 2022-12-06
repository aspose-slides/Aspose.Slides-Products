---
title: TIFF को PDF में C# में मर्ज करें
url: /hi/net/merger/tiff-to-pdf/
keywords: TIFF से PDF, TIFF को PDF में मर्ज करें, TIFF से PDF, PDF, TIFF, C# API, .NET लाइब्रेरी में शामिल हों
description: सी # में टीआईएफएफ को पीडीएफ में मर्ज करें। TIFF और PDF को संयोजित करने के लिए .NET लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="TIFF को PDF में C# में मर्ज करें" h2="नेट फ्रेमवर्क, .NET कोर, विंडोज एज़्योर, मोनो या ज़ामरीन प्लेटफ़ॉर्म पर C# कोड का उपयोग करके TIFF को PDF फ़ाइलों में मर्ज करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके TIFF को PDF में मर्ज करें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) एक शक्तिशाली .NET लाइब्रेरी है, जिसका इस्तेमाल प्रेजेंटेशन, PDF, इमेज बनाने, बदलने, मर्ज करने और हेरफेर करने के लिए किया जाता है। और अन्य फ़ाइलें। जब आप टीआईएफएफ को पीडीएफ में मर्ज करते हैं, तो आप एक पीडीएफ फाइल प्राप्त करने के लिए छवियों को प्रभावी ढंग से जोड़ रहे हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="TIFF को PDF में C# में मर्ज करें" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ TIFF को PDF में शीघ्रता से मर्ज कर सकते हैं

{{% blocks/products/pf/agp/code-block title="टीआईएफएफ को पीडीएफ में विलय करने के लिए सी # कोड" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage tiff1 = pres.Images.AddImage(File.ReadAllBytes("image1.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, tiff1);

    IPPImage tiff2 = pres.Images.AddImage(File.ReadAllBytes("image2.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, tiff2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C# में TIFF को PDF में कैसे मर्ज करें" >}}


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
उन TIFF फ़ाइलों को लोड करें जिन्हें आप चित्र फ़्रेम के रूप में मर्ज करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी पीडीएफ को सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}