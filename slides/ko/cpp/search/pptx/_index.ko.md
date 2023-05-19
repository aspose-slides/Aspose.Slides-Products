---
title: C++을(를) 사용하여 PPTX 프레젠테이션 파일에서 텍스트 검색
url: /ko/cpp/search/pptx/
keywords: PPTX에서 단어 검색, PPTX에서 텍스트 검색 및 바꾸기, PPTX에서 텍스트 검색 프레젠테이션
description: PPTX 프레젠테이션에서 텍스트를 검색하기 위한 C++ 소스 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++을 사용하여 PPTX 텍스트 검색" h2="서버 측 API를 사용하여 프리젠테이션 파일에서 텍스트를 검색하고 교체하는 나만의 C++ 앱을 빌드하세요. 프레젠테이션 문서에서 특정 단어나 구의 모든 입구를 찾는 방법을 알아봅니다. 정확한 데이터 일치 및 정규식 일치로 텍스트를 검색합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++을 통한 텍스트 PPTX 프레젠테이션 검색 및 바꾸기" %}}
Aspose.Slides for C++ API를 사용하여 콘텐츠, 댓글, 슬라이드 노트 또는 메타데이터의 기본 문서 검색 및 텍스트 바꾸기를 단 몇 줄의 코드로 수행할 수 있습니다. 정규식 일치를 사용하고 대소문자를 일치시켜 프레젠테이션의 텍스트를 검색합니다. 제목, 콘텐츠, 바닥글 또는 머리글에서 텍스트를 검색합니다.
{{% blocks/products/pf/agp/code-block title="텍스트 검색 PPTX C++을 사용한 프레젠테이션" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++을 통해 PPTX에서 텍스트를 검색하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="텍스트 PPTX 파일을 검색하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 PPTX를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) 메서드를 사용하여 텍스트를 찾고 바꿉니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPTX 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="온라인 PPTX 검색 라이브 데모" sectionDescription="지금 바로 PPTX 문서의 콘텐츠, 댓글 또는 메타데이터에서 텍스트를 검색하고 교체하세요." >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 검색 형식" subTitle="C++을(를) 사용하여 다음 형식의 텍스트를 검색할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}