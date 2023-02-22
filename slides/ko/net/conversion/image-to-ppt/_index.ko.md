---
title: C#에서 이미지를 PPT로 변환
url: /ko/net/conversion/image-to-ppt/
keywords: 이미지를 PPT로, 이미지를 PPT로, PowerPoint, 이미지, PPT, C# API, .NET 라이브러리로 변환
description: C#에서 이미지를 PPT로 변환합니다. .NET 라이브러리 API를 사용하여 이미지를 PowerPoint로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C#에서 이미지를 PPT로 변환" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 C# 코드를 사용하여 이미지를 PPT로 변환하기 위한 강력한 크로스 플랫폼 .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 이미지를 PPT로 변환" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)은 PowerPoint 프레젠테이션, PDF, HTML 문서, 및 기타 파일. 이미지를 PPT로 변환하면 기본적으로 해당 이미지를 기반으로 슬라이드가 포함된 PowerPoint 프레젠테이션을 만드는 것입니다.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="C#에서 이미지를 PPT로 변환" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 몇 줄의 코드만으로 이미지를 PowerPoint 프레젠테이션으로 변환할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="이미지를 PPT로 변환하기 위한 C# 코드" offSpacer="true" %}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C#에서 이미지를 PPT로 변환하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET**을 설치합니다. [**설치**](https://docs.aspose.com/slides/net/installation/)를 참조하세요.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프로젝트에서 라이브러리를 참조로 추가하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT로 변환할 이미지를 불러옵니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 파일을 PPT 프레젠테이션으로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 PowerPoint 변환" subTitle="다른 형식의 파일을 PowerPoint로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}