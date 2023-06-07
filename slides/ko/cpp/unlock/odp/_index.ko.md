---
title: C++을(를) 사용하여 ODP 프레젠테이션 파일 잠금 해제
url: /ko/cpp/unlock/odp/
keywords: 쓰기 방지 ODP 제거, ODP 해독, ODP 프레젠테이션 잠금 해제, ODP 보호 해제
description: ODP 프레젠테이션에서 보호를 제거하는 C++ 소스 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++을(를) 사용하여 ODP 잠금 해제" h2="나만의 C++ 앱을 구축하여 PowerPoint에서 비밀번호를 제거하고 서버 측 API를 사용하여 프레젠테이션 파일을 해독하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++을(를) 통해 ODP 프레젠테이션에서 암호화 제거" %}}
Aspose.Slides for C++을(를) 사용하여 ODP 프레젠테이션에서 암호화 또는 암호 보호를 제거할 수 있습니다. 이렇게 하면 사용자가 제한 없이 ODP 프레젠테이션에 액세스하거나 수정할 수 있습니다.
{{% blocks/products/pf/agp/code-block title="C++을(를) 사용하여 ODP에서 암호 보호 비활성화" offSpacer="true" %}}

```cpp

auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"123123");
    
auto presentation = System::MakeObject<Presentation>(u"pres.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"encryption-removed.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++을(를) 사용하여 ODP 프레젠테이션에서 쓰기 보호 제거" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++을(를) 통해 ODP에서 비밀번호를 제거하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 ODP 파일에서 보호를 제거하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 ODP 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager 클래스를 사용하여 쓰기 방지 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 ODP 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 형식" subTitle="C++을(를) 사용하여 다음 형식에서 보호를 제거할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}