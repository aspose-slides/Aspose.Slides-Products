---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: छवि को जावा में पीपीटीएक्स में कनवर्ट करें
url: /hi/java/conversion/image-to-pptx/
keywords: छवि को PPTX, छवि को PPTX, PowerPoint, छवि, PPTX, Java API, Java लाइब्रेरी में बदलें
description: छवि को जावा में पीपीटीएक्स में कनवर्ट करें। छवि को PowerPoint में कनवर्ट करने के लिए Java लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="छवि को जावा में पीपीटीएक्स में कनवर्ट करें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म जावा लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="छवि को जावा में पीपीटीएक्स में कनवर्ट करें" variant="code" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ छवि को PowerPoint प्रस्तुति में बदल सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/code title="छवि को पीपीटीएक्स में कनवर्ट करने के लिए जावा कोड" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.save("presentation.pptx", SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा का उपयोग करके छवि को PPTX में बदलें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) एक शक्तिशाली जावा लाइब्रेरी है जिसका उपयोग PowerPoint प्रस्तुतियों, PDF, HTML डॉक्स और अन्य को बनाने, बदलने और हेरफेर करने के लिए किया जाता है फ़ाइलें। जब आप छवि को PPTX में बदलते हैं, तो आप अनिवार्य रूप से एक PowerPoint प्रस्तुति बना रहे होते हैं जिसमें उन छवियों पर आधारित स्लाइड होती हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="जावा एपीआई के लिए Aspose.Slides का उपयोग करके छवि को पीपीटीएक्स में कैसे परिवर्तित करें" intro="जावा में इमेज को पीपीटीएक्स में बदलने के ये चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) इंस्टॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपने जावा प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}उस छवि को लोड करें जिसे आप PPTX में बदलना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणामी फ़ाइल को PPTX प्रस्तुति के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऑनलाइन कनवर्टर"
  description="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित PowerPoint रूपांतरण" subTitle="आप फ़ाइलों को अन्य स्वरूपों में PowerPoint में भी रूपांतरित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
