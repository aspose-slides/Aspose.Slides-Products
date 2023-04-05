---
title: C#에서 이미지 병합
url: /ko/net/merger/image-to-image/
keywords: 이미지 병합, 이미지를 이미지로, 이미지 결합, 이미지 결합, C# API, .NET 라이브러리
description: C#에서 이미지를 이미지에 병합합니다. .NET 라이브러리 API를 사용하여 이미지 결합
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C#에서 이미지 병합" h2="NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 C# 코드를 사용하여 이미지를 병합하기 위한 강력한 크로스 플랫폼 .NET API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 이미지를 이미지에 병합" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)은 프레젠테이션, 이미지 및 기타 파일을 병합하고 조작하는 데 사용되는 강력한 .NET 라이브러리입니다. 이미지를 이미지로 병합하면 두 개의 이미지를 효과적으로 결합하여 하나의 사진을 얻을 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C#에서 이미지를 이미지로 병합" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/ko/net/)을 사용하면 단 몇 줄의 코드만으로 이미지 파일을 빠르게 병합할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="이미지를 이미지에 병합하기 위한 C# 코드" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("imagepath1"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("imagepath2"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("merged-image.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C#에서 이미지를 병합하는 방법" >}}


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
사진 프레임으로 병합하려는 이미지를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 이미지를 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="온라인으로 PDF 파일 병합" sectionDescription="[Python에서 PDF를 병합하는 방법](https://products.aspose.com/slides/ko/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 파일 병합" subTitle="다른 형식의 파일을 결합하여 단일 파일을 얻을 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/net/merger/html-to-image/" name="HTML TO IMAGE" >}}    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}