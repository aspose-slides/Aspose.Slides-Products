---
title: पायथन में छवि को पीपीटी में बदलें
url: /hi/python-net/conversion/image-to-ppt/
keywords: छवि को पीपीटी में बदलें, छवि को पीपीटी में बदलें, पायथन एपीआई, पायथन लाइब्रेरी, छवि, पीपीटी
description: पायथन में छवि को पीपीटी में बदलें। छवि फ़ाइलों को PDF में कनवर्ट करने के लिए Python लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पायथन में छवि को पीपीटी में बदलें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="पायथन में छवि को पीपीटी में बदलें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह छवि को पीपीटी में बदलने के लिए लचीले तरीके प्रदान करता है। **Aspose.Slides for Python via .NET** का उपयोग करके, कोई भी डेवलपर या ऐप्लिकेशन, Python कोड की कुछ ही पंक्तियों के साथ इमेज को PPT फ़ाइलों में बदल सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, पायथन के लिए Aspose.Slides पीपीटी फ़ाइल स्वरूपों में छवि फ़ाइलों को जल्दी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको छवि को PDF और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="पायथन का उपयोग करके छवि को पीपीटी में बदलें" %}}
इमेज को पीपीटी में बदलने के लिए, आपको इमेज फाइल से प्रेजेंटेशन बनाना होगा और इसे पीपीटी के रूप में सेव करना होगा।

{{% blocks/products/pf/agp/code-block title="छवि को पीपीटी में बदलने के लिए पायथन कोड" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    pres.save("index.ppt", slides.export.SaveFormat.PPT)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="पायथन एपीआई के लिए Aspose.Slides का उपयोग करके छवि को पीपीटी में कैसे परिवर्तित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये पायथन में इमेज को पीपीटी में बदलने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने पायथन प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पायथन में स्रोत छवि फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पीपीटी फ़ाइल के रूप में परिणाम सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="मुफ्त ऑनलाइन कनवर्टर" sectionDescription="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="छवि को अन्य समर्थित स्वरूपों में बदलें" subTitle="आप छवि को रूपांतरित भी कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}