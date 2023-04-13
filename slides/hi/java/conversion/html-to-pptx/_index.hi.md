---
title: जावा में HTML को PPTX में बदलें
url: /hi/java/conversion/html-to-pptx/
keywords: HTML को PPTX, HTML को PPTX, PowerPoint, HTML, PPTX, Java API, Java लाइब्रेरी में बदलें
description: जावा में HTML को PPTX में बदलें। HTML को PowerPoint में बदलने के लिए Java लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जावा में HTML को PPTX में बदलें" h2="जावा कोड का उपयोग करके HTML को PPTX में परिवर्तित करने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म Java API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके HTML को PPTX में कनवर्ट करें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) एक शक्तिशाली जावा लाइब्रेरी है जिसका उपयोग PowerPoint प्रस्तुतियों, PDF, HTML डॉक्स और अन्य को बनाने, बदलने और हेरफेर करने के लिए किया जाता है फ़ाइलें। जब आप HTML को PPTX में कनवर्ट करते हैं, तो आप अनिवार्य रूप से सामग्री को HTML दस्तावेज़ में PowerPoint प्रस्तुति में स्लाइड पर ले जा रहे होते हैं।

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="जावा में HTML को PPTX में बदलें" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ HTML दस्तावेज़ को PowerPoint प्रस्तुति में बदल सकते हैं:

{{% blocks/products/pf/agp/code-block title="HTML को PPTX में बदलने के लिए जावा कोड" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.pptx", SaveFormat.Pptx);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="जावा में HTML को PPTX में कैसे बदलें" >}}


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
वह HTML दस्तावेज़ लोड करें जिसे आप PPTX में बदलना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी फ़ाइल को PPTX प्रस्तुति के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित PowerPoint रूपांतरण" subTitle="आप फ़ाइलों को अन्य स्वरूपों में PowerPoint में भी रूपांतरित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}