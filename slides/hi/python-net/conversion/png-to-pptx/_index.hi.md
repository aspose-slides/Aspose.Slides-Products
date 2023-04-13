---
title: पायथन में पीएनजी को पीपीटीएक्स में कनवर्ट करें
url: /hi/python-net/conversion/png-to-pptx/
keywords: PNG को PPTX, PNG को PPTX, PowerPoint, PNG, PPTX, Python API, Python लाइब्रेरी में कन्वर्ट करें
description: पायथन में पीएनजी को पीपीटीएक्स में कनवर्ट करें। PNG छवियों को PowerPoint में कनवर्ट करने के लिए Python लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पायथन में पीएनजी को पीपीटीएक्स में कनवर्ट करें" h2="पायथन कोड का उपयोग करके पीएनजी को पीपीटीएक्स में परिवर्तित करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म पायथन एपीआई" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PNG को PPTX में बदलें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) एक शक्तिशाली Python लाइब्रेरी है जिसका उपयोग PowerPoint प्रस्तुतियों, PDF, को बनाने, रूपांतरित करने और हेरफेर करने के लिए किया जाता है। एचटीएमएल डॉक्स, और अन्य फाइलें। जब आप PNG को PPTX में बदलते हैं, तो आप अनिवार्य रूप से एक PowerPoint प्रस्तुति बना रहे होते हैं जिसमें PNG छवियों पर आधारित स्लाइड होती हैं।

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="पायथन में पीएनजी को पीपीटीएक्स में कनवर्ट करें" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PNG छवि को PowerPoint प्रस्तुति में बदल सकते हैं:

{{% blocks/products/pf/agp/code-block title="पीएनजी को पीपीटीएक्स में परिवर्तित करने के लिए पायथन कोड" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पायथन में PNG को PPTX में कैसे बदलें" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
उस PNG छवि को लोड करें जिसे आप PPTX में बदलना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी फ़ाइल को PPTX प्रस्तुति के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित PowerPoint रूपांतरण" subTitle="आप फ़ाइलों को अन्य स्वरूपों में PowerPoint में भी रूपांतरित कर सकते हैं" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}