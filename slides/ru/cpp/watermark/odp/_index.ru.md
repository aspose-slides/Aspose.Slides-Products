---
title: Добавьте водяной знак в файлы презентаций ODP с помощью C++
url: /ru/cpp/watermark/odp/
keywords: Добавить водяной знак ODP, Добавить текстовый водяной знак ODP, Добавить водяной знак изображения ODP
description: Исходный код C++ для добавления водяного знака в презентацию ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Добавьте водяной знак в презентацию ODP, используя C++" h2="Создавайте собственные приложения C++, чтобы вставлять текстовые или графические водяные знаки в презентации PPT, PPTX или ODP с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Добавить водяной знак в презентацию ODP через C++" %}}
Используя Aspose.Slides for C++, вы можете добавить водяной знак в презентацию ODP. Водяные знаки являются неотъемлемой частью любой презентации. Они используются для защиты содержимого презентации от копирования или использования без разрешения. Водяной знак — это видимое или невидимое изображение или текст, которые размещаются поверх презентации. Его можно использовать для идентификации владельца презентации и предотвращения несанкционированного использования. Водяные знаки также можно использовать, чтобы придать презентации профессиональный вид и сделать ее более изысканной. 
{{% blocks/products/pf/agp/code-block title="Добавьте текстовый водяной знак в ODP, используя C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Добавьте водяной знак изображения в презентацию ODP, используя C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как добавить водяной знак в ODP через C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для добавления текстового водяного знака в файлы ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите ODP с экземпляром Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Выберите основную презентацию
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте тип фигуры с помощью метода AddAutoShape.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте текст водяного знака, используя метод AddTextFrame.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы" subTitle="Используя C++, вы также можете добавить водяной знак в следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}