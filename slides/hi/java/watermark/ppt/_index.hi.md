---
title: Java का उपयोग करके PPT प्रस्तुतिकरण फ़ाइलों में वॉटरमार्क जोड़ें
url: /hi/java/watermark/ppt/
keywords: वॉटरमार्क जोड़ें PPT, टेक्स्ट वॉटरमार्क जोड़ें PPT, छवि वॉटरमार्क जोड़ें PPT
description: वॉटरमार्क को PPT प्रस्तुतिकरण में जोड़ने के लिए Java स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java का उपयोग करके PPT प्रस्तुतिकरण में वॉटरमार्क जोड़ें" h2="सर्वर-साइड API का उपयोग करके PPT, PPTX, या ODP प्रस्तुति में टेक्स्ट या इमेज वॉटरमार्क डालने के लिए अपना खुद का Java ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java द्वारा PPT प्रस्तुतिकरण में वॉटरमार्क जोड़ें" %}}
{Product_name} का उपयोग करके, आप वॉटरमार्क को PPT प्रस्तुतिकरण में जोड़ सकते हैं। वॉटरमार्क किसी भी प्रस्तुति का एक अनिवार्य हिस्सा हैं। इनका उपयोग प्रस्तुति की सामग्री को कॉपी किए जाने या अनुमति के बिना उपयोग किए जाने से बचाने के लिए किया जाता है। वॉटरमार्क एक दृश्य या अदृश्य छवि या पाठ है जिसे प्रस्तुति के शीर्ष पर रखा जाता है। इसका उपयोग प्रस्तुति के स्वामी की पहचान करने और अनधिकृत उपयोग को रोकने के लिए किया जा सकता है। वॉटरमार्क का उपयोग प्रस्तुति में एक पेशेवर स्पर्श जोड़ने और इसे और अधिक परिष्कृत दिखाने के लिए भी किया जा सकता है। 
{{% blocks/products/pf/agp/code-block title="Java का उपयोग करके PPT में टेक्स्ट वॉटरमार्क जोड़ें" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java का उपयोग करके PPT प्रस्तुतिकरण में इमेज वॉटरमार्क जोड़ें" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java के द्वारा PPT में वॉटरमार्क कैसे जोड़ें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PPT फ़ाइलों में टेक्स्ट वॉटरमार्क जोड़ने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ PPT लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
मास्टर प्रस्तुति का चयन करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape पद्धति का उपयोग करके आकृति प्रकार जोड़ें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame पद्धति का उपयोग करके वॉटरमार्क टेक्स्ट जोड़ें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPT प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित प्रारूप" subTitle="Java का उपयोग करके, आप निम्न स्वरूपों में वॉटरमार्क भी जोड़ सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}