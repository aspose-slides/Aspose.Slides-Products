---
title: पायथन में पीपीटी संपादित करें
url: /hi/python-net/editor/ppt/
keywords: पीपीटी संपादित करें, पावरपॉइंट संपादित करें, पीपीटी, पावरपॉइंट, पायथन एपीआई, पायथन लाइब्रेरी संपादित करें
description: पायथन में पीपीटी संपादित करें। PowerPoint प्रस्तुति को संपादित करने के लिए Python लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पायथन में पीपीटी संपादित करें" h2="पायथन कोड का उपयोग करके पीपीटी संपादित करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके पीपीटी संपादित करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) एक शक्तिशाली Python लाइब्रेरी है जिसका उपयोग प्रस्तुतियों में हेरफेर करने और संपादित करने के लिए किया जाता है। आप पीपीटी प्रस्तुति में पाठ की एक नई पंक्ति जोड़कर इसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="पायथन में पीपीटी संपादित करें" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) का उपयोग करके, आप पीपीटी दस्तावेज़ में टेक्स्ट की एक नई पंक्ति जोड़ सकते हैं। कोड की पंक्तियाँ।

{{% blocks/products/pf/agp/code-block title="पीपीटी संपादित करने के लिए पायथन कोड" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पायथन में पीपीटी को कैसे संपादित करें" >}}


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
पीपीटी प्रस्तुति लोड करें जिसे आप संपादित करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ की एक नई पंक्ति जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिवर्तित PowerPoint फ़ाइल सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}