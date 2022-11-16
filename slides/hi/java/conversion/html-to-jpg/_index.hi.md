---
title: जावा में HTML को JPG में कनवर्ट करें
url: /hi/java/conversion/html-to-jpg/
keywords: HTML से JPG, HTML को JPG में बदलें, Java API, Java लाइब्रेरी, HTML, JPG
description: जावा में HTML को JPG में कनवर्ट करें। HTML फ़ाइलों को JPGs में कनवर्ट करने के लिए Java लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जावा में HTML को JPG में कनवर्ट करें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म जावा लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="जावा में HTML को JPG में कनवर्ट करें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) प्रेजेंटेशन फाइल बनाने और मैनिपुलेट करने के लिए एक शक्तिशाली जावा लाइब्रेरी है। इसके अलावा, यह HTML को JPG में बदलने के लचीले तरीके प्रदान करता है। **Aspose.Slides for Java** का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन HTML को JPG फ़ाइलों में केवल जावा कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, Aspose.Slides for Java HTML फ़ाइलों को JPG फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको HTML को JPG और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा का उपयोग करके HTML को JPG में बदलें" %}}
HTML को JPG में बदलने के लिए, आपको HTML फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे JPG के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="HTML को JPG में बदलने के लिए जावा कोड" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="जावा एपीआई के लिए Aspose.Slides का उपयोग करके HTML को JPG में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये जावा में HTML को JPG में बदलने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source HTML files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as JPG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="HTML को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप HTML को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}