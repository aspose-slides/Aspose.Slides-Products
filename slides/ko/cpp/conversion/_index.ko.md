---
title: C++를 사용하여 다양한 형식으로 Microsoft PowerPoint 프레젠테이션 변환
url: /ko/cpp/conversion/
description: Microsoft PowerPoint Slides를 C++ 기반 응용 프로그램 내에서 HTML, PDF 및 이미지 형식을 포함한 여러 파일로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++를 통한 Microsoft<sup>®</sup> PowerPoint 프레젠테이션 변환" h2="슬라이드를 이미지, HTML, PDF 및 기타 형식으로 변환하기 위한 다양한 변환 시나리오에 대한 C++ 예제 코드." >}}

{{% blocks/products/pf/feature-page-summary %}}

Microsoft<sup>®</sup> PowerPoint 형식의 변환 프로세스는 C++ PowerPoint 라이브러리를 사용하여 프로세스를 간단하고 자동화하기 쉽습니다. 개발자는 관련 소스 코드를 개선하고 애플리케이션에 통합할 수 있습니다. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 형식의 상호 변환" %}}
프로그래밍 방식으로 PPT, PPTX를 포함한 Microsoft<sup>®</sup> PowerPoint 문서의 상호 변환은 단 두 줄의 코드입니다. [Presentation class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation)를 사용하여 파일을 로드하고 [Save method](https://apireference.aspose.com/slides)를 호출합니다. /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 출력 파일 및 SaveFormat.OutputFormats를 매개변수로 포함합니다.

{{% blocks/products/pf/feature-page-code h3="C++ 변환 코드" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint 파일을 PDF로 변환" %}}

Microsoft<sup>®</sup> PowerPoint를 PDF로 변환하는 것은 PDF 문서의 엄청난 공유로 인해 일반적인 시나리오입니다. 프로그래머는 [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options)를 사용하여 이를 자동화하고 관련 PDF 변환 설정을 지정할 수 있습니다. 텍스트 압축 수준, JPEG 품질 [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), PDF 준수 수준과 같은 몇 가지 특정 설정 [준수](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), 숨겨진 슬라이드 변환 [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), 선택한 슬라이드 및 잠긴 [비밀번호] 생성 .

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint에서 PDF로 변환 코드" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 슬라이드를 이미지로 저장" %}}
웹에 프레젠테이션 콘텐츠를 표시하는 경우가 있을 때마다 파일을 HTML 또는 이미지 JPG, TIFF, PNG 등으로 렌더링해야 합니다. 슬라이드를 이미지로 변환하는 프로세스는 간단합니다. [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c)를 사용하여 모든 슬라이드를 가져오고 각 슬라이드를 하나씩 반복합니다. 각 반복 중에 슬라이드 이미지에 대해 [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783)을 사용한 다음 필요한 이미지 형식으로 저장합니다. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint에서 이미지로 변환" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}