---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JPG को PDF में C# में मर्ज करें
url: /hi/net/merger/jpg-to-pdf/
keywords: जेपीजी से पीडीएफ, जेपीजी को पीडीएफ में मर्ज करें, जेपीजी को पीडीएफ, पीडीएफ, जेपीजी, सी#एपीआई, .नेट लाइब्रेरी से जोड़ें
description: सी # में जेपीजी को पीडीएफ में मर्ज करें। JPG और PDF को संयोजित करने के लिए .NET लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JPG को PDF में C# में मर्ज करें" h2="NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर C# कोड का उपयोग करके JPG को PDF फ़ाइलों में मर्ज करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API" related="JPG,PNG,HTML,IMAGE,PDF,SVG,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JPG को PDF में C# में मर्ज करें" variant="code" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ JPG को PDF में शीघ्रता से मर्ज कर सकते हैं

{{< blocks/products/pf/slides-design-update-10-2026/code title="जेपीजी को पीडीएफ में विलय करने के लिए सी # कोड" >}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके JPG को PDF में मर्ज करें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) एक शक्तिशाली .NET लाइब्रेरी है, जिसका इस्तेमाल प्रेजेंटेशन, PDF, इमेज बनाने, बदलने, मर्ज करने और हेरफेर करने के लिए किया जाता है। और अन्य फ़ाइलें। जब आप जेपीजी को पीडीएफ में मर्ज करते हैं, तो आप एक पीडीएफ फाइल प्राप्त करने के लिए जेपीजी छवियों को प्रभावी ढंग से जोड़ रहे हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="सी # में जेपीजी को पीडीएफ में कैसे विलय करें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** इंस्टॉल करें। [**इंस्टॉलेशन**](https://docs.aspose.com/slides/net/installation/) देखें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}उन JPG छवियों को लोड करें जिन्हें आप चित्र फ़्रेम के रूप में मर्ज करना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणामी पीडीएफ फाइल को सेव करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides से निर्मित" title="JPG को PDF में ऑनलाइन मर्ज करें" description="मुफ़्त Aspose.Slides Merger ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी JPG फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Merger खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides फ़ाइलों को कैसे मर्ज करता है।
- कई JPG फ़ाइलें अपलोड करें और उन्हें एक PDF फ़ाइल में मिलाएँ।
- मर्ज किया गया परिणाम एक फ़ाइल के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/png-to-pdf/" name="PNG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
