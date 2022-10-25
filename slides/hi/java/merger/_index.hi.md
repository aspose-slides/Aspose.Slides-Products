---
title: जावा का उपयोग करके पीडीएफ, पीपीटी, पीपीटीएक्स और कई अन्य फ़ाइल स्वरूपों को मर्ज करें
url: /hi/java/merger/
keywords: मर्ज करें, जुड़ें, पावरपॉइंट, प्रेजेंटेशन, जावा, एस्पोज करें
description: जावा पीपीटी, पीपीटीएक्स, ओडीपी, पीडीएफ, पीएनजी, जेपीजी और कई अन्य में कई फाइलों को मर्ज करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा में पावरपॉइंट, पीडीएफ, पीपीटी या अन्य दस्तावेजों को एक साथ मिलाएं" h2="पीपीटी, पीपीटीएक्स, पीडीएफ, पीएनजी, जेपीईजी और अन्य प्रारूपों को मर्ज करने के लिए हाई-स्पीड जावा लाइब्रेरी।" >}}

{{% blocks/products/pf/feature-page-section h2="Java का उपयोग करके PPT, PPTX, PDF को मर्ज करें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) प्रेजेंटेशन फाइल बनाने और उसमें हेरफेर करने के लिए एक शक्तिशाली जावा लाइब्रेरी है। इसके अलावा, यह कई पीपीटी / पीपीटीएक्स प्रस्तुतियों को संयोजित करने के लचीले तरीके प्रदान करता है। जब आप एक प्रस्तुति को दूसरे में मर्ज करते हैं, तो आप एक फ़ाइल प्राप्त करने के लिए उनकी स्लाइड्स को एक प्रस्तुति में प्रभावी रूप से संयोजित कर रहे हैं। Aspose.Slides आपको दो प्रस्तुतियों को अलग-अलग तरीकों से मर्ज करने की अनुमति देता है। आप गुणवत्ता या डेटा के नुकसान के बारे में चिंता किए बिना प्रस्तुतियों को उनके सभी आकारों, शैलियों, ग्रंथों, स्वरूपण, टिप्पणियों, एनिमेशन आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा में PowerPoint प्रस्तुतियों को मर्ज करें" %}}
PowerPoint प्रस्तुतियों को मर्ज करने के लिए, आपको स्लाइडों को एक प्रस्तुति से दूसरी प्रस्तुति में क्लोन करना होगा।

{{% blocks/products/pf/agp/code-block title="Java का उपयोग करके PPTX फ़ाइलें मर्ज करें" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा का उपयोग करके स्लाइड मास्टर के साथ प्रस्तुतियों को मिलाएं" %}}
यह जावा कोड दर्शाता है कि कैसे कई प्रस्तुतियों को एक में मिलाएं और स्लाइड मास्टर प्रस्तुति टेम्पलेट से शैलियों को लागू करें। तो, परिणाम प्रस्तुति एक ही स्रोत स्वरूपण रखेगी और इसमें किसी अन्य प्रस्तुति की मास्टर स्लाइड से स्वरूपण होगा।

{{% blocks/products/pf/agp/code-block title="जावा में एकाधिक पीपीटी को सिंगल में मर्ज करें" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="जावा एपीआई के लिए Aspose.Slides का उपयोग करके प्रस्तुतियों को कैसे मर्ज करें?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये दो पीपीटीएक्स फाइलों को मर्ज करने और जावा में पीडीएफ के रूप में परिणाम सहेजने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/) इंस्टॉल करें। 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने जावा प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
जावा में स्रोत PPTX फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**AddClone** विधि का उपयोग करके PPTX फाइलों को मिलाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति सहेजें और एकल पीडीएफ फाइल के रूप में परिणाम प्राप्त करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="मर्ज करने के लिए अन्य समर्थित प्रारूप" subTitle="आप अन्य फ़ाइल स्वरूपों को भी जोड़ सकते हैं। नीचे अन्य समर्थित प्रारूप देखें।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}