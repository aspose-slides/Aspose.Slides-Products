---
title: जावा में एचटीएमएल संपादित करें
url: /hi/java/editor/html/
keywords: एचटीएमएल, एचटीएमएल, जावा एपीआई, जावा लाइब्रेरी संपादित करें
description: जावा में एचटीएमएल संपादित करें। HTML फ़ाइल संपादित करने के लिए Java लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जावा में एचटीएमएल संपादित करें" h2="जावा कोड का उपयोग करके HTML के संपादन के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म जावा लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके HTML संपादित करें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) एक शक्तिशाली जावा लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, HTML दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर करने और संपादित करने के लिए किया जाता है। आप किसी HTML दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="जावा में एचटीएमएल संपादित करें" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ HTML दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं।

{{% blocks/products/pf/agp/code-block title="HTML संपादित करने के लिए जावा कोड" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="जावा में HTML को कैसे संपादित करें" >}}


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
वह HTML दस्तावेज़ लोड करें जिसे आप संपादित करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ की एक नई पंक्ति जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिवर्तित HTML फ़ाइल सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}