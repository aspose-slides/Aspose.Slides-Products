---
title: पायथन में HTML संपादित करें
url: /hi/python-net/editor/html/
keywords: एचटीएमएल, एचटीएमएल, पायथन एपीआई, पायथन लाइब्रेरी संपादित करें
description: पायथन में HTML संपादित करें। HTML फ़ाइल को संपादित करने के लिए Python लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पायथन में HTML संपादित करें" h2="पायथन कोड का उपयोग करके HTML के संपादन के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके HTML संपादित करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) एक शक्तिशाली Python लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, HTML दस्तावेज़ों और अन्य फ़ाइलों में हेरफेर और संपादित करने के लिए किया जाता है . आप किसी HTML दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="पायथन में HTML संपादित करें" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) का उपयोग करके, आप केवल कुछ के साथ HTML दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं कोड की पंक्तियाँ।

{{% blocks/products/pf/agp/code-block title="HTML संपादित करने के लिए पायथन कोड" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पायथन में HTML को कैसे संपादित करें" >}}


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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}