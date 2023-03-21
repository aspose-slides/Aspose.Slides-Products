---
title: पायथन में SVG को PNG में कनवर्ट करें
url: /hi/python-net/conversion/svg-to-png/
keywords: SVG से PNG, SVG को PNG में बदलें, Python API, Python लाइब्रेरी, SVG, PNG
description: पायथन में SVG को PNG में कनवर्ट करें। SVG फ़ाइलों को PNGs में कनवर्ट करने के लिए Python लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पायथन में SVG को PNG में कनवर्ट करें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="पायथन में SVG को PNG में कनवर्ट करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह SVG को PNG में बदलने के लचीले तरीके प्रदान करता है। **Aspose.Slides for Python via .NET** का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन SVG को PNG फ़ाइलों में केवल Python कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, पायथन के लिए Aspose.Slides SVG फ़ाइलों को PNG फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको SVG को PNG और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="पायथन का उपयोग करके SVG को PNG में बदलें" %}}
SVG को PNG में बदलने के लिए, आपको SVG फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे PNG के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="SVG को PNG में बदलने के लिए पायथन कोड" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    with open("image.svg", "rb") as file:
        svgContent = file.read()
    svgImage = slides.SvgImage(svgContent)
    ppImage = pres.images.add_image(svgImage)
    pres.slides[0].shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, ppImage.width, ppImage.height, ppImage)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="पायथन एपीआई के लिए Aspose.Slides का उपयोग करके SVG को PNG में कैसे परिवर्तित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये पायथन में SVG को PNG में बदलने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने पायथन प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पायथन में स्रोत SVG फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को PNG फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="SVG को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप SVG को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}