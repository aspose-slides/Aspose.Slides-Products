---
title: C++을(를) 사용하여 PPTX 프레젠테이션 파일 보호
url: /ko/cpp/protect/pptx/
keywords: 쓰기 방지 PPTX, PPTX 암호화, PPTX 프레젠테이션 잠금, PPTX 보호
description: PPTX 프레젠테이션을 보호하기 위한 C++ 소스 코드.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++을 사용하여 PPTX 잠금 또는 비밀번호 보호" h2="서버 측 API를 사용하여 프리젠테이션 파일을 보호하는 나만의 C++ 앱을 구축하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++을(를) 통해 PPTX 프레젠테이션 보호" %}}
Aspose.Slides for C++을(를) 사용하면 비밀번호를 설정하여 PPTX 프레젠테이션을 열거나 수정하지 못하도록 보호할 수 있습니다. 그런 다음 잠긴 프레젠테이션을 열거나 수정하려면 사용자가 암호를 입력해야 합니다.
{{% blocks/products/pf/agp/code-block title="C++을(를) 사용하여 PPTX 프레젠테이션 암호화" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++을(를) 사용하여 PPTX 프레젠테이션에 쓰기 방지 설정" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++을(를) 통해 PPTX을(를) 비밀번호로 보호하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 PPTX 파일을 보호하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 PPTX 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager 클래스를 사용하여 프레젠테이션 보호
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPTX 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 보호 형식" subTitle="C++을(를) 사용하여 다음 형식도 보호할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}