---
title: C++에서 PPT를 Word로 변환
url: /ko/cpp/conversion/ppt-to-word/
keywords: PPT를 Word로, PPT를 Word로, PPT를 DOC로, PowerPoint를 Word로, C++ API, C++ 라이브러리, CPP로 변환
description: C++에서 PPT를 Word로 변환합니다. C++ 라이브러리 API를 사용하여 PowerPoint를 Word로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++에서 PPT를 Word로 변환" h2="Microsoft PowerPoint 또는 Office 없이 C++ 코드를 사용하여 PowerPoint를 Word로 변환하기 위한 강력한 크로스 플랫폼 C++ API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides 및 Aspose.Words를 사용하여 PowerPoint를 Word로 변환" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ko/cpp/) 및 [**Aspose.Words for C++**](https://products.aspose.com/ words/cpp/)는 PowerPoint 프레젠테이션, Word 문서 및 기타 파일을 조작하고 변환하는 데 사용되는 강력한 C++ 라이브러리입니다. PowerPoint를 Word로 변환하면 기본적으로 프레젠테이션 슬라이드의 내용이 Word 문서의 페이지로 이동됩니다.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C++에서 PowerPoint를 Word로 변환" %}}
몇 줄의 코드만으로 PPT를 Word로 빠르게 변환할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="PowerPoint를 Word로 변환하기 위한 C++ 코드" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPT를 Word로 변환하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**C++**용 Aspose.Slides 및 C++**용 **Aspose.Words 설치 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스와 Doc 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word로 변환하려는 PPT 프레젠테이션을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
슬라이드의 내용을 기반으로 이미지와 텍스트를 생성합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 Word 문서를 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="PowerPoint를 다른 형식의 파일로 변환할 수도 있습니다." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}