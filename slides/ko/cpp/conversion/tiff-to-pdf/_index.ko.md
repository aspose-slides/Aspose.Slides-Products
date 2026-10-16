---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ 응용 프로그램을 통해 TIFF를 PDF로 변환
weight: 5900
url: /ko/cpp/conversion/tiff-to-pdf/ 
description: TIFF 문서를 PDF 형식으로 변환하는 샘플 C++ 변환 코드. 모든 C++ 응용 프로그램 내에서 일괄 TIFF에서 PDF로 변환하는 예제 코드를 사용합니다.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++를 통해 TIFF를 PDF로 변환" h2="Microsoft PowerPoint를 설치할 필요 없이 C++ 라이브러리를 사용하여 고성능 TIFF를 PDF로 변환합니다."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++를 사용하여 TIFF를 PDF로 변환하는 방법" %}}

TIFF를 PDF로 변환하기 위해 다음을 사용합니다.
 [C++용 Aspose.Slides](https://products.aspose.com/slides/ko/cpp/)
 기능이 풍부하고 강력하며 사용하기 쉬운 C++ 플랫폼용 문서 조작 및 변환 API인 API입니다. 최신 버전을 직접 다운로드할 수 있습니다.
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 패키지 관리자, 검색
 Aspose.Slides.Cpp
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="명령" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="TIFF에서 PDF로 C++ 변환 소스 코드" >}}
```cs
// Load the TIFF.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.tiff");
// Save in PDF format.
prs->Save(u"convertedFile.pdf", Aspose::Slides::Export::SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++를 통해 TIFF를 PDF로 변환하는 단계" intro="C++ 개발자는 몇 줄의 코드로 TIFF 파일을 PDF로 쉽게 변환할 수 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for C++ Presentation Object로 TIFF 파일을 로드합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save() 메서드를 호출합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}파일 확장자가 (PDF)인 출력 파일 경로를 전달합니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF 파일은 지정된 경로에 저장됩니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}호환되는 프로그램에서 PDF 파일을 엽니다.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="시스템 요구 사항" intro="C++ 변환 예제 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오." %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
- 프로젝트에서 참조되는 C++ DLL용 Aspose.Slides.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="TIFF을 PDF로 변환하는 무료 앱"
  description="[무료 MP4 To MP3 앱을 사용해보십시오](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 TIFF를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="OpenDocument 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="OpenDocument 표준 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="마이크로소프트 파워포인트 템플릿 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="마이크로소프트 파워포인트 템플릿 프레젠테이션" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="매크로 사용 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="파워포인트 슬라이드 쇼" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="마이크로소프트 파워포인트 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="매크로 사용 프레젠테이션 파일" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Open XML 프레젠테이션 형식" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="확장 가능한 마크업 언어" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ko/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="XML 용지 사양" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
