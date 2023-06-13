---
title: Java을(를) 사용하여 PPT 프레젠테이션 파일에 워터마크 추가
url: /ko/java/watermark/ppt/
keywords: 워터마크 추가 PPT, 텍스트 워터마크 추가 PPT, 이미지 워터마크 추가 PPT
description: PPT 프레젠테이션에 워터마크를 추가하기 위한 Java 소스 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java을(를) 사용하여 PPT 프레젠테이션에 워터마크 추가" h2="서버 측 API를 사용하여 텍스트 또는 이미지 워터마크를 PPT, PPTX 또는 ODP 프레젠테이션에 삽입하는 나만의 Java 앱을 구축하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java을(를) 통해 PPT 프레젠테이션에 워터마크 추가" %}}
Aspose.Slides for Java을(를) 사용하여 PPT 프레젠테이션에 워터마크를 추가할 수 있습니다. 워터마크는 프레젠테이션의 필수 요소입니다. 프리젠테이션 내용을 허가 없이 복사하거나 사용하지 못하도록 보호하는 데 사용됩니다. 워터마크는 프리젠테이션 위에 표시되는 보이거나 보이지 않는 이미지 또는 텍스트입니다. 프레젠테이션의 소유자를 식별하고 무단 사용을 방지하는 데 사용할 수 있습니다. 워터마크를 사용하여 프레젠테이션에 전문적인 느낌을 더하고 더욱 세련되게 보이게 할 수 있습니다. 
{{% blocks/products/pf/agp/code-block title="Java을 사용하여 PPT에 텍스트 워터마크 추가" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java을(를) 사용하여 PPT 프레젠테이션에 이미지 워터마크 추가" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java을(를) 통해 PPT에 워터마크를 추가하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="PPT 파일에 텍스트 워터마크를 추가하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 인스턴스로 PPT 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
마스터 프레젠테이션 선택
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape 메서드를 사용하여 도형 유형 추가
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame 메서드를 사용하여 워터마크 텍스트 추가
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PPT 형식으로 저장
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 형식" subTitle="Java을(를) 사용하여 다음 형식에 워터마크를 추가할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}