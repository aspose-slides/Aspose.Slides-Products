---
title: जेपीजी को जावा में पीपीटी में कनवर्ट करें
url: /hi/java/conversion/jpg-to-ppt/
keywords: जेपीजी को पीपीटी, जेपीजी को पीपीटी, पावरपॉइंट, जेपीजी, पीपीटी, जावा एपीआई, जावा लाइब्रेरी में कनवर्ट करें
description: जेपीजी को जावा में पीपीटी में कनवर्ट करें। JPG छवियों को PowerPoint में कनवर्ट करने के लिए Java लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जेपीजी को जावा में पीपीटी में कनवर्ट करें" h2="जेपीजी को पीपीटी में कनवर्ट करने के लिए जावा कोड का उपयोग करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म जावा एपीआई" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके JPG को PPT में बदलें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) एक शक्तिशाली जावा लाइब्रेरी है जिसका उपयोग PowerPoint प्रस्तुतियों, PDF, HTML डॉक्स और अन्य को बनाने, बदलने और हेरफेर करने के लिए किया जाता है फ़ाइलें। जब आप JPG को PPT में कनवर्ट करते हैं, तो आप अनिवार्य रूप से एक PowerPoint प्रस्तुति बना रहे होते हैं जिसमें JPG छवियों पर आधारित स्लाइड होती हैं।

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="जेपीजी को जावा में पीपीटी में कनवर्ट करें" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ JPG छवि को PowerPoint प्रस्तुति में बदल सकते हैं:

{{% blocks/products/pf/agp/code-block title="जेपीजी को पीपीटी में बदलने के लिए जावा कोड" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="जावा में जेपीजी को पीपीटी में कैसे बदलें" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java** इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/java/installation/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
उस जेपीजी छवि को लोड करें जिसे आप पीपीटी में बदलना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी फ़ाइल को PPT प्रस्तुति के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित PowerPoint रूपांतरण" subTitle="आप फ़ाइलों को अन्य स्वरूपों में PowerPoint में भी रूपांतरित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}