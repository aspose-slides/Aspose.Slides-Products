---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावा में एचटीएमएल को पीपीटी में कनवर्ट करें
url: /hi/java/conversion/html-to-ppt/
keywords: HTML को PPT, HTML को PPT, PowerPoint, HTML, PPT, Java API, Java लाइब्रेरी में बदलें
description: जावा में एचटीएमएल को पीपीटी में कनवर्ट करें। HTML को PowerPoint में बदलने के लिए Java लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावा में एचटीएमएल को पीपीटी में कनवर्ट करें" h2="जावा कोड का उपयोग करके HTML को PPT में बदलने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म Java API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा में एचटीएमएल को पीपीटी में कनवर्ट करें" variant="code" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ HTML दस्तावेज़ को PowerPoint प्रस्तुति में बदल सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/code title="एचटीएमएल को पीपीटी में बदलने के लिए जावा कोड" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.ppt", SaveFormat.Ppt);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके HTML को PPT में बदलें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) एक शक्तिशाली जावा लाइब्रेरी है जिसका उपयोग PowerPoint प्रस्तुतियों, PDF, HTML डॉक्स और अन्य को बनाने, बदलने और हेरफेर करने के लिए किया जाता है फ़ाइलें। जब आप HTML को पीपीटी में कनवर्ट करते हैं, तो आप अनिवार्य रूप से सामग्री को HTML दस्तावेज़ में PowerPoint प्रस्तुति में स्लाइड में ले जा रहे हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="जावा में HTML को PPT में कैसे बदलें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java** इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/java/installation/)।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वह HTML दस्तावेज़ लोड करें जिसे आप PPT में बदलना चाहते हैं।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणामी फ़ाइल को PPT प्रस्तुति के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऑनलाइन कनवर्टर"
  description="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित PowerPoint रूपांतरण" subTitle="आप फ़ाइलों को अन्य स्वरूपों में PowerPoint में भी रूपांतरित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-ppt/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/jpg-to-pptx/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
