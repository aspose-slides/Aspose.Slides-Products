---
title: C++를 사용하여 PPT 주석 제거
weight: 4380
url: /ko/cpp/annotation/ppt/ 
description: PPT에서 주석을 삭제하는 C++ 소스 코드
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++의 PPT에서 주석 및 주석 작성자 제거" h2="서버 측 API를 사용하여 문서 파일에서 댓글과 작성자를 조작하는 고유한 C++ 앱을 빌드합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 PPT에서 주석 제거" %}}
PPT 파일에서 주석을 제거하기 위해 기능이 풍부하고 강력하며 사용하기 쉬운 [Aspose.Slides for C++](https://products.aspose.com/slides/ko/cpp/) API를 사용합니다. C++ 플랫폼용 문서 조작 API.
{{% blocks/products/pf/agp/code-block title="PPT에서 주석 삭제 - C++" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="C++를 통해 PPT에서 주석을 제거하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++**를 설치합니다. [**설치**](https://docs.aspose.com/slides/cpp/installation/)를 참조하세요.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 클래스의 인스턴스로 PPT 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
로드된 PPT의 모든 작성자에 대해 반복
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
작성자의 모든 주석 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
마지막에 모든 작성자 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 주석 형식" subTitle="C++를 사용하면 다음을 포함한 다른 형식에 쉽게 주석을 달 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}