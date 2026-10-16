---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: पायथन में HTML को JPG में कनवर्ट करें
url: /hi/python-net/conversion/html-to-jpg/
keywords: HTML से JPG, HTML को JPG में बदलें, Python API, Python लाइब्रेरी, HTML, JPG
description: पायथन में HTML को JPG में कनवर्ट करें। HTML फ़ाइलों को JPGs में कनवर्ट करने के लिए Python लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="पायथन में HTML को JPG में कनवर्ट करें" h2="हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="पायथन का उपयोग करके HTML को JPG में बदलें" variant="code" %}}

HTML को JPG में बदलने के लिए, आपको HTML फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे JPG के रूप में सहेजना होगा।

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML को JPG में बदलने के लिए पायथन कोड" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("file.html", "rt", encoding="utf-8") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for sld in pres.slides:
        bmp = sld.get_image(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), slides.ImageFormat.JPEG)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="पायथन में HTML को JPG में कनवर्ट करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह HTML को JPG में बदलने के लचीले तरीके प्रदान करता है। **Aspose.Slides for Python via .NET** का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन HTML को JPG फ़ाइलों में केवल Python कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, पायथन के लिए Aspose.Slides HTML फ़ाइलों को JPG फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको HTML को JPG और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="पायथन एपीआई के लिए Aspose.Slides का उपयोग करके HTML को JPG में कैसे परिवर्तित करें" intro="ये पायथन में HTML को JPG में बदलने के चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) इंस्टॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपने पायथन प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}पायथन में स्रोत HTML फ़ाइलें खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}परिणाम को JPG फ़ाइल के रूप में सहेजें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="मुफ्त ऑनलाइन कनवर्टर"
  description="[पायथन में पीपीटी को एचटीएमएल में कैसे बदलें](https://products.aspose.com/slides/hi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="HTML को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप HTML को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/python-net/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
