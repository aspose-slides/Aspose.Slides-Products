---
title: माइक्रोसॉफ्ट पावरपॉइंट प्रेजेंटेशन सी ++ का उपयोग करके विभिन्न प्रारूपों में रूपांतरण
url: /hi/cpp/conversion/
description: माइक्रोसॉफ्ट पावरपॉइंट स्लाइड्स को एचटीएमएल, पीडीएफ और सी ++ आधारित अनुप्रयोगों के भीतर छवि प्रारूपों सहित कई फाइलों में कनवर्ट करें।
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> C++ के माध्यम से PowerPoint प्रस्तुति रूपांतरण" h2="स्लाइड्स को इमेज, एचटीएमएल, पीडीएफ और अन्य फॉर्मेट में बदलने के लिए विभिन्न रूपांतरण परिदृश्यों के लिए सी ++ उदाहरण कोड।" >}}

{{% blocks/products/pf/feature-page-summary %}}

Microsoft<sup>®</sup> PowerPoint प्रारूपों की रूपांतरण प्रक्रिया C++ PowerPoint लाइब्रेरी का उपयोग करके प्रक्रियाओं को स्वचालित करने के लिए सरल और आसान है। डेवलपर्स प्रासंगिक स्रोत कोड को बढ़ा सकते हैं और इसे अपने अनुप्रयोगों में एकीकृत कर सकते हैं। 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint स्वरूपों का अंतर रूपांतरण" %}}
PPT, PPTX सहित Microsoft<sup>®</sup> PowerPoint दस्तावेज़ों का अंतर्रूपांतरण प्रोग्रामेटिक रूप से केवल दो पंक्तियों का कोड है। [प्रस्तुति वर्ग](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) का उपयोग करके फ़ाइल लोड करें और [सहेजें विधि](https://apireference.aspose.com/slides) पर कॉल करें /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) आउटपुट फ़ाइल और SaveFormat.OutputFormats को पैरामीटर के रूप में रखते हैं।

{{% blocks/products/pf/feature-page-code h3="सी ++ रूपांतरण कोड" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="पावरपॉइंट फाइलों को पीडीएफ में बदलें" %}}

Microsoft<sup>®</sup> PowerPoint को PDF में कनवर्ट करना PDF दस्तावेज़ों के विशाल साझाकरण के कारण एक सामान्य परिदृश्य है। प्रोग्रामर इसे स्वचालित कर सकते हैं और [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) का उपयोग करके प्रासंगिक PDF रूपांतरण सेटिंग्स सेट कर सकते हैं। कुछ विशिष्ट सेटिंग्स जैसे टेक्स्ट कम्प्रेशन स्तर, JPEG गुणवत्ता [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), PDF अनुपालन स्तर [अनुपालन](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), हिडन स्लाइड्स को कनवर्ट करना [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), चयनित स्लाइड और जनरेटिंग लॉक [पासवर्ड](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983 PDF files) संरक्षित PDF फ़ाइलें .

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint से PDF रूपांतरण कोड" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint स्लाइड को छवियों के रूप में सहेजें" %}}
जब कभी वेब पर प्रस्तुति सामग्री प्रदर्शित करने की बात आती है, तो HTML या छवियों JPG, TIFF, PNG, आदि के रूप में फ़ाइलों को प्रस्तुत करने की आवश्यकता होती है। स्लाइड को छवियों के रूप में परिवर्तित करने की प्रक्रिया सरल है। [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) का उपयोग करके सभी स्लाइड प्राप्त करें और प्रत्येक स्लाइड के माध्यम से एक-एक करके पुनरावृति करें। प्रत्येक पुनरावृत्ति के दौरान स्लाइड छवि के लिए [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) का उपयोग करें और फिर आवश्यक छवि प्रारूप में सहेजें। 

{{% blocks/products/pf/feature-page-code h3="छवि रूपांतरण के लिए C++ PowerPoint" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}