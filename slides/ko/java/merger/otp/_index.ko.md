---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java를 통해 OTP 파일 병합
weight: 920
url: /ko/java/merger/otp/ 
description: JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 Java Runtime Environment에서 OTP 문서를 결합하는 Java 샘플 코드입니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java에서 OTP 형식 병합" h2="서버 측 Java API를 사용한 기본 OTP 문서 병합."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java를 사용하여 OTP 파일을 병합하는 방법" %}}

OTP 파일을 병합하려면 다음을 사용합니다.
 [자바용 Aspose.Slides](https://products.aspose.com/slides/ko/java/)
 기능이 풍부하고 강력하며 사용하기 쉬운 Java 플랫폼용 병합 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="저장소" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="의존" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP 파일 병합 - 자바" >}}
```cs
// Load first OTP File
Presentation prest1 = new Presentation("prest1.otp");

// Load second OTP File
Presentation prest2 = new Presentation("prest2.otp");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.otp", SaveFormat.Otp);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java에서 OTP 파일을 병합하는 단계" intro="[Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/) API로 기본 문서 병합 및 연결을 몇 줄의 코드로 수행할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스가 있는 첫 번째 OTP 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation 클래스의 인스턴스로 두 번째 OTP 문서를 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}두 번째 OTP 파일의 각 슬라이드를 반복합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}각 반복에서 addClone()을 사용하여 첫 번째 파일이 있는 슬라이드를 추가합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}save() 메서드를 사용하여 지정된 경로에 저장{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="Java용 Aspose.Slides는 모든 주요 플랫폼 및 운영 체제에서 지원합니다. 다음 전제 조건이 있는지 확인하십시오." %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 Java Runtime Environment와 호환되는 OS.
- 최신 버전의 Aspose.Slides for Java를 다음에서 직접 가져옵니다. [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="온라인으로 PDF 파일 병합"
  description="[Python에서 PDF를 병합하는 방법](https://products.aspose.com/slides/ko/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

확장자가 `.OTP`인 파일은 OASIS OpenDocument 표준 형식으로 만든 프레젠테이션 템플릿 파일입니다. `OTP` 파일은 새 프레젠테이션을 만드는 데 사용되는 슬라이드 레이아웃, 스타일 및 기타 프레젠테이션 정보를 저장합니다.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 병합 형식" subTitle="Java를 사용하여 One은 ..를 포함한 다른 많은 파일 형식을 병합할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/odp/" name="ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/pot/" name="POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/potm/" name="POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/potx/" name="POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/pps/" name="PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/ppsm/" name="PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/ppsx/" name="PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/ppt/" name="PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/pptm/" name="PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/java/merger/pptx/" name="PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
