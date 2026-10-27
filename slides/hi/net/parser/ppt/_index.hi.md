---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: .NET से PPT फ़ाइलों से टेक्स्ट निकालें
url: /hi/net/parser/ppt/ 
description: .NET से PPT फ़ाइलों से टेक्स्ट निकालने के लिए C# सोर्स कोड।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# से PPT फ़ाइलें पार्स करें" h2="सर्वर-साइड .NET API से PPT फ़ाइलों से टेक्स्ट निकालें और टेक्स्ट फ़ॉर्मैटिंग की जाँच करें।"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# से PPT फ़ाइल पार्स करें" %}}

PPT प्रेज़ेंटेशन से टेक्स्ट निकालने के लिए [Aspose.Slides for .NET](/slides/hi/net/) का उपयोग करें। पैकेज को [NuGet](https://www.nuget.org/packages/aspose.slides.net) से इंस्टॉल करें या Package Manager Console में निम्न कमांड चलाएँ।

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कमांड" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT फ़ाइलें पार्स करें – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# में PPT फ़ाइलें कैसे पार्स करें" intro="[Aspose.Slides for .NET](/slides/hi/net/) API से बुनियादी दस्तावेज़ पार्सिंग के लिए कोड की बस कुछ पंक्तियाँ चाहिए।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` से PPT फ़ाइल लोड करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.GetAllTextFrames` से टेक्स्ट फ़्रेम प्राप्त करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}टेक्स्ट फ़्रेम, पैराग्राफ़ और टेक्स्ट हिस्सों पर लूप चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आवश्यकता अनुसार `Text`, `FontHeight` और `LatinFont.FontName` प्रॉपर्टी पढ़ें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="सिस्टम आवश्यकताएँ" intro="एक समर्थित .NET रनटाइम और Aspose.Slides for .NET पैकेज का संदर्भ आवश्यक है। आप Visual Studio या कोई अन्य संगत C# डेवलपमेंट एनवायरनमेंट उपयोग कर सकते हैं।" %}}

- .NET Framework, .NET, Mono या Xamarin के साथ संगत एनवायरनमेंट
- Visual Studio जैसा C# डेवलपमेंट एनवायरनमेंट
- NuGet से इंस्टॉल किया गया Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides से निर्मित" title="टेक्स्ट और इमेज ऑनलाइन निकालें" description="मुफ़्त Aspose.Slides Parser ऐप [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net/) से बना है, वही API जो ऊपर दिए गए कोड में है। इसे खोलें और देखें कि API आपकी अपनी PPT फ़ाइलों के साथ क्या कर सकता है।" button="Aspose.Slides Parser खोलें" note="[सभी मुफ़्त ऐप्स](https://products.aspose.app/slides/family)" >}}
- आपके ब्राउज़र में चलता है, कुछ भी इंस्टॉल करने की ज़रूरत नहीं।
- कोड लिखने से पहले देखें कि Aspose.Slides आपकी फ़ाइलें कैसे पढ़ता है।
- एक PPT फ़ाइल अपलोड करें और उसका टेक्स्ट और इमेज पाएँ।
- सब कुछ एक ZIP आर्काइव के रूप में डाउनलोड करें।
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

PPT फ़ाइल बाइनरी फ़ाइल फ़ॉर्मैट में एक Microsoft PowerPoint 97-2003 प्रेज़ेंटेशन है। इसमें टेक्स्ट, बुलेट सूचियों, इमेज, मल्टीमीडिया और एम्बेड किए गए OLE ऑब्जेक्ट वाली स्लाइड्स होती हैं। नए PowerPoint संस्करण Office Open XML पर आधारित PPTX फ़ॉर्मैट का उपयोग करते हैं। OpenOffice Impress और Apple Keynote जैसे ऐप्लिकेशन भी PPT फ़ाइलें बना सकते हैं।

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="पार्सिंग के लिए अन्य समर्थित फ़ॉर्मैट" subTitle="C# से आप निम्नलिखित फ़ॉर्मैट भी पार्स कर सकते हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/parser/odp/" name="ODP" description="OpenDocument प्रेज़ेंटेशन" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hi/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML प्रेज़ेंटेशन" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
