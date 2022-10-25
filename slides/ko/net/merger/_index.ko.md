---
title: C#을 사용하여 PDF, PPT, PPTX 및 기타 여러 파일 형식 병합
url: /ko/net/merger/
keywords: 병합, 조인, PowerPoint, 프레젠테이션, C#, .NET, Aspose
description: C# PPT, PPTX, ODP, PDF, PNG, JPG 등의 여러 파일을 병합합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C#에서 PowerPoint, PDF, PPT 또는 기타 문서 병합" h2="PPT, PPTX, PDF, PNG, JPEG 및 기타 형식을 병합하는 고속 C# 라이브러리." >}}

{{% blocks/products/pf/feature-page-section h2="C#을 사용하여 PPT, PPTX, PDF 병합" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)은 프레젠테이션 파일을 만들고 조작하기 위한 강력한 C# 라이브러리입니다. 또한 여러 PPT/PPTX 프레젠테이션을 결합하는 유연한 방법을 제공합니다. 한 프리젠테이션을 다른 프리젠테이션에 병합하면 하나의 프리젠테이션에서 슬라이드를 효과적으로 결합하여 하나의 파일을 얻는 것입니다. Aspose.Slides를 사용하면 두 개의 프레젠테이션을 서로 다른 방식으로 병합할 수 있습니다. 품질이나 데이터 손실에 대해 걱정할 필요 없이 모든 모양, 스타일, 텍스트, 서식, 주석, 애니메이션 등으로 프레젠테이션을 병합할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#에서 PowerPoint 프레젠테이션 병합" %}}
PowerPoint 프레젠테이션을 병합하려면 한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복제해야 합니다.

{{% blocks/products/pf/agp/code-block title="C#을 사용하여 PPTX 파일 병합" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 사용하여 슬라이드 마스터와 프레젠테이션 병합" %}}
이 C# 코드는 여러 프레젠테이션을 하나로 병합하고 슬라이드 마스터 프레젠테이션 템플릿의 스타일을 적용하는 방법을 보여줍니다. 따라서 결과 프레젠테이션은 동일한 소스 서식을 유지하고 다른 프레젠테이션의 마스터 슬라이드에서 서식을 포함합니다.

{{% blocks/products/pf/agp/code-block title="C#에서 여러 PPT를 하나로 병합" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2=".NET API용 Aspose.Slides를 사용하여 프레젠테이션을 병합하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 두 개의 PPTX 파일을 병합하고 결과를 .NET에서 PDF로 저장하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for .NET**](https://docs.aspose.com/slides/net/installation/)을 설치합니다. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C# 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C#에서 소스 PPTX 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**AddClone** 방법을 사용하여 PPTX 파일을 결합합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션을 저장하고 단일 PDF 파일로 결과를 얻으십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="병합할 기타 지원 형식" subTitle="다른 파일 형식을 결합할 수도 있습니다. 아래에서 지원되는 다른 형식을 참조하세요." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}