---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: पायथन में PNG को SVG में कनवर्ट करें
url: /hi/python-net/conversion/png-to-svg/
keywords: PNG से SVG, PNG को SVG में बदलें, Python API, Python लाइब्रेरी, PNG, SVG
description: पायथन में PNG को SVG में कनवर्ट करें। PNG फ़ाइलों को SVGs में कनवर्ट करने के लिए Python लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="पायथन में PNG को SVG में कनवर्ट करें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="पायथन का उपयोग करके PNG को SVG में बदलें" variant="code" %}}

PNG को SVG में बदलने के लिए, आपको PNG फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे SVG के रूप में सहेजना होगा।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PNG को SVG में बदलने के लिए पायथन कोड" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for index in range(pres.slides.length):
        slide = pres.slides[index]

        with open("slide-{index}.svg".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="पायथन में PNG को SVG में कनवर्ट करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह PNG को SVG में बदलने के लचीले तरीके प्रदान करता है। **Aspose.Slides for Python via .NET** का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन PNG को SVG फ़ाइलों में केवल Python कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, पायथन के लिए Aspose.Slides PNG फ़ाइलों को SVG फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको PNG को SVG और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="पायथन एपीआई के लिए Aspose.Slides का उपयोग करके PNG को SVG में कैसे परिवर्तित करें" intro="ये पायथन में PNG को SVG में बदलने के चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) इंस्टॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपने पायथन प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पायथन में स्रोत PNG फ़ाइलें खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणाम को SVG फ़ाइल के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides से निर्मित" title="PNG को SVG में ऑनलाइन बदलें" description="मुफ़्त Aspose.Slides Conversion ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PNG फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Conversion खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" upload="अपनी फ़ाइल छोड़ें या अपलोड करें" saveAs="इस रूप में सहेजें" convert="बदलें" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides फ़ाइलों को कैसे बदलता है।
- PNG फ़ाइलें अपलोड करें और उन्हें SVG के रूप में सहेजें।
- परिणाम डाउनलोड करें या और फ़ाइलें बदलें।
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="PNG को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप PNG को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
