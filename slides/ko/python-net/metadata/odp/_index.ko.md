---
title: Python을(를) 사용하여 ODP 파일 메타데이터 보기 또는 편집
url: /ko/python-net/metadata/odp/
keywords: ODP 메타데이터 수정, ODP 메타데이터 보기, ODP 속성 수정, ODP 속성 보기
description: ODP 형식 메타데이터를 편집하거나 보기 위한 Python 소스 코드.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python을(를) 사용하여 ODP 속성 편집" h2="서버 측 API를 사용하여 프리젠테이션 파일의 기본 제공 속성과 사용자 정의 속성을 수정하려면 자신만의 Python 앱을 빌드하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python을 통해 ODP 속성 수정" %}}
개발자는 Aspose.Slides for Python via .NET을(를) 사용하여 기본 제공 속성 및 사용자 지정 속성의 값에 액세스하고 수정할 수 있습니다. 개발자는 프레젠테이션 파일의 문서 속성에 액세스하기 위해 Presentation 개체에 의해 노출된 [DocumentProperties](https://reference.aspose.com/slides/python-net/aspose.slides/documentproperties/) 속성을 사용할 수 있습니다.
{{% blocks/products/pf/agp/code-block title="ODP 내장 속성 수정 - Python" offSpacer="true" %}}

```py

import aspose.slides as slides

# Instantiate the Presentation class that represents the Presentation
with slides.Presentation(path + "ModifyBuiltinProperties.odp") as presentation:
    # Create a reference to object associated with Presentation
    documentProperties = presentation.document_properties

    # Set the builtin properties
    documentProperties.author = "Aspose.Slides for Python"
    documentProperties.title = "Modifying Presentation Properties"
    documentProperties.subject = "Aspose Subject"
    documentProperties.comments = "Aspose Description"
    documentProperties.manager = "Aspose Manager"

    # save your presentation to a file
    presentation.save("DocumentProperties_out.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="ODP에 맞춤 속성 추가 - Python" offSpacer="true" %}}

```py

import aspose.slides as slides

# Instantiate the Presentation class
with slides.Presentation() as presentation:
    # Getting Document Properties
    documentProperties = presentation.document_properties

    # Adding Custom properties
    documentProperties.set_custom_property_value("New Custom", 12)
    documentProperties.set_custom_property_value("My Nam", "Aspose Metadata Editor")
    documentProperties.set_custom_property_value("Custom", 124)

    # Getting property name at particular index
    getPropertyName = documentProperties.get_custom_property_name(2)

    # Removing selected property
    documentProperties.remove_custom_property(getPropertyName)

    # Saving presentation
    presentation.save("CustomDocumentProperties_out.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python을 통해 ODP의 메타데이터를 추출하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 ODP 파일에서 메타데이터를 추출하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP 파일에 대한 경로를 사용하여 프레젠테이션 클래스를 인스턴스화합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션과 연결된 DocumentProperties 개체 가져오기
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
DocumentProperties 개체의 항목을 반복합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
사용자 지정 속성 액세스 및 수정
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 메타데이터 형식" subTitle="Python을(를) 사용하여 다음을 비롯한 다양한 형식의 메타데이터를 조작할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/python-net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}