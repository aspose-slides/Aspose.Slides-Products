---
title: C#에서 PPTX를 Word로 변환
url: /ko/net/conversion/pptx-to-word/
keywords: PPTX를 Word로, PPTX를 Word로, PPTX를 DOC로, PowerPoint를 Word로, C# API, .NET 라이브러리로 변환
description: C#에서 PPTX를 Word로 변환합니다. .NET 라이브러리 API를 사용하여 PowerPoint를 Word로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C#에서 PPTX를 Word로 변환" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 C# 코드를 사용하여 PowerPoint를 Word로 변환하기 위한 강력한 크로스 플랫폼 .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides 및 Aspose.Words를 사용하여 PowerPoint를 Word로 변환" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/) 및 [**Aspose.Words for .NET**](https://products.aspose. com/words/net/)은 PowerPoint 프레젠테이션, Word 문서 및 기타 파일을 조작하고 변환하는 데 사용되는 강력한 .NET 라이브러리입니다. PowerPoint를 Word로 변환하면 기본적으로 프레젠테이션 슬라이드의 내용이 Word 문서의 페이지로 이동됩니다.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C#에서 PowerPoint를 Word로 변환" %}}
몇 줄의 코드만으로 빠르게 PPTX를 Word로 변환할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="PowerPoint를 Word로 변환하기 위한 C# 코드" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPTX를 Word로 변환하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** 및 **Aspose.Words for .NET** 설치 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프로젝트에서 두 개의 라이브러리를 참조로 추가하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스와 Doc 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word로 변환하려는 PPTX 프레젠테이션을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
슬라이드의 내용을 기반으로 이미지와 텍스트를 생성합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 Word 문서를 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="PowerPoint를 다른 형식의 파일로 변환할 수도 있습니다." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}