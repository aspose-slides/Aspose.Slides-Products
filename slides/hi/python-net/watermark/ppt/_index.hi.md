---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python से PPT प्रेज़ेंटेशन में वॉटरमार्क जोड़ें
url: /hi/python-net/watermark/ppt/
description: Python और Aspose.Slides से PPT प्रेज़ेंटेशन में टेक्स्ट और इमेज वॉटरमार्क जोड़ें।
keywords: PPT में वॉटरमार्क जोड़ें, PPT में टेक्स्ट वॉटरमार्क जोड़ें, PPT में इमेज वॉटरमार्क जोड़ें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python से PPT प्रेज़ेंटेशन में वॉटरमार्क जोड़ें" h2="ऐसे Python ऐप्लिकेशन बनाएँ जो Aspose.Slides से PPT प्रेज़ेंटेशन में टेक्स्ट या इमेज वॉटरमार्क जोड़ें।" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python से PPT प्रेज़ेंटेशन में वॉटरमार्क जोड़ने का उदाहरण" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/hi/python-net/) से आप Microsoft PowerPoint के बिना PPT प्रेज़ेंटेशन में टेक्स्ट या इमेज वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क स्वामित्व दिखा सकता है, प्रेज़ेंटेशन को गोपनीय या ड्राफ़्ट के रूप में चिह्नित कर सकता है, या एक जैसी ब्रांडिंग दे सकता है। नीचे दिए गए उदाहरण वॉटरमार्क को पहली मास्टर स्लाइड पर रखते हैं, ताकि वह उस मास्टर का उपयोग करने वाली स्लाइड पर दिखे।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT प्रेज़ेंटेशन में टेक्स्ट वॉटरमार्क जोड़ें – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT प्रेज़ेंटेशन में इमेज वॉटरमार्क जोड़ें – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python से PPT में वॉटरमार्क कैसे जोड़ें" intro="PPT प्रेज़ेंटेशन में टेक्स्ट वॉटरमार्क जोड़ने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से PPT फ़ाइल खोलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`masters` कलेक्शन से पहली मास्टर स्लाइड प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}मास्टर स्लाइड पर आयत जोड़ने के लिए `add_auto_shape` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क टेक्स्ट जोड़ने के लिए `add_text_frame` कॉल करें, फिर शेप को फ़ॉर्मैट और लॉक करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}वॉटरमार्क वाली प्रेज़ेंटेशन सहेजने के लिए `SaveFormat.PPT` के साथ `save` कॉल करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides से निर्मित" title="PPT फ़ाइलों में ऑनलाइन वॉटरमार्क जोड़ें" description="मुफ़्त Aspose.Slides Watermark ऐप [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Watermark खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides वॉटरमार्क कैसे जोड़ता है।
- अपनी PPT फ़ाइल में टेक्स्ट या इमेज वॉटरमार्क जोड़ें।
- वॉटरमार्क वाली फ़ाइल डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="वॉटरमार्क के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="Python से आप अन्य समर्थित प्रेज़ेंटेशन फ़ॉर्मैट में भी वॉटरमार्क जोड़ सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
