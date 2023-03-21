---
title: Java에서 JPG을 Image로 변환
url: /ko/java/conversion/jpg-to-image/
keywords: JPG에서 Image으로, JPG에서 Image로 변환, Java API, Java 라이브러리, JPG, Image
description: Java에서 JPG을 Image로 변환합니다. Java 라이브러리 API를 사용하여 JPG 파일을 Image 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java에서 JPG을 Image로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 Java 라이브러리입니다." >}}

{{% blocks/products/pf/feature-page-section h2="Java에서 JPG을 Image로 변환" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Java 라이브러리입니다. 또한 JPG을 Image으로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for Java**를 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 Java 코드로 JPG을 Image 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Java는 JPG 파일을 Image 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 JPG을 Image 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 사용하여 JPG을 Image로 변환" %}}
JPG을 Image로 변환하려면 JPG 파일에서 프레젠테이션을 생성하고 Image로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="JPG을 Image로 변환하기 위한 Java 코드" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Java API를 사용하여 JPG을 Image로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java에서 JPG을 Image으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Java 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Java에서 소스 JPG 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 Image 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="JPG을 지원되는 다른 형식으로 변환" subTitle="JPG을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}