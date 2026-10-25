---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET से PPT फ़ाइल मेटाडेटा देखें या संपादित करें
url: /hi/net/metadata/ppt/
description: PPT मेटाडेटा देखने या संपादित करने के लिए C# सोर्स कोड।
keywords: PPT मेटाडेटा संपादित करें, PPT मेटाडेटा देखें, PPT प्रॉपर्टी संपादित करें, PPT प्रॉपर्टी देखें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# से PPT प्रॉपर्टी संपादित करें" h2="ऐसे .NET ऐप्लिकेशन बनाएँ जो सर्वर-साइड API से प्रेज़ेंटेशन की बिल्ट-इन और कस्टम प्रॉपर्टी पढ़ें और बदलें।" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# से PPT प्रॉपर्टी बदलें" variant="code" %}}

[Aspose.Slides for .NET](/slides/hi/net/) से डेवलपर प्रेज़ेंटेशन की बिल्ट-इन और कस्टम प्रॉपर्टी तक पहुँच सकते हैं और उन्हें बदल सकते हैं। PPT मेटाडेटा पढ़ने और अपडेट करने के लिए `Presentation` ऑब्जेक्ट की [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) प्रॉपर्टी का उपयोग करें।

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT की बिल्ट-इन प्रॉपर्टी बदलें – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT में कस्टम प्रॉपर्टी जोड़ें – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# में PPT मेटाडेटा कैसे देखें या संपादित करें" intro="PPT मेटाडेटा देखने या संपादित करने के लिए ये चरण अपनाएँ।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से PPT फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रेज़ेंटेशन से `DocumentProperties` ऑब्जेक्ट प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author`, `Title` और `Subject` जैसी बिल्ट-इन प्रॉपर्टी पढ़ें या अपडेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`DocumentProperties` से कस्टम प्रॉपर्टी तक पहुँचें और उन्हें बदलें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides से निर्मित" title="PPT मेटाडेटा ऑनलाइन देखें और संपादित करें" description="मुफ़्त Aspose.Slides Metadata ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Metadata खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides प्रॉपर्टी कैसे पढ़ता और लिखता है।
- अपनी PPT फ़ाइल की बिल्ट-इन और कस्टम प्रॉपर्टी देखें और संपादित करें।
- अपडेट की गई फ़ाइल सहेजें और डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित मेटाडेटा फ़ॉर्मैट" subTitle="C# से आप निम्नलिखित फ़ॉर्मैट का मेटाडेटा भी प्रबंधित कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
