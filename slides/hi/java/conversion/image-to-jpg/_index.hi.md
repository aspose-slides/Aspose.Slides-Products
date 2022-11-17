---
title: जावा में Image को JPG में कनवर्ट करें
url: /hi/java/conversion/image-to-jpg/
keywords: Image से JPG, Image को JPG में बदलें, Java API, Java लाइब्रेरी, Image, JPG
description: जावा में Image को JPG में कनवर्ट करें। Image फ़ाइलों को JPGs में कनवर्ट करने के लिए Java लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जावा में Image को JPG में कनवर्ट करें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म जावा लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="जावा में Image को JPG में कनवर्ट करें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) प्रेजेंटेशन फाइल बनाने और मैनिपुलेट करने के लिए एक शक्तिशाली जावा लाइब्रेरी है। इसके अलावा, यह Image को JPG में बदलने के लचीले तरीके प्रदान करता है। **Aspose.Slides for Java** का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन Image को JPG फ़ाइलों में केवल जावा कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, Aspose.Slides for Java Image फ़ाइलों को JPG फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको Image को JPG और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा का उपयोग करके Image को JPG में बदलें" %}}
Image को JPG में बदलने के लिए, आपको Image फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे JPG के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="Image को JPG में बदलने के लिए जावा कोड" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
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

{{< blocks/products/pf/feature-page-section  h2="जावा एपीआई के लिए Aspose.Slides का उपयोग करके Image को JPG में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये जावा में Image को JPG में बदलने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने जावा प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
जावा में स्रोत Image फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को JPG फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Image को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप Image को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}