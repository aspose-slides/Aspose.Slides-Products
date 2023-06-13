---
title: C++ kullanarak PPT Sunum Dosyalarına Filigran ekleyin
url: /tr/cpp/watermark/ppt/
keywords: Filigran Ekle PPT, Metin Filigranı Ekle PPT, Görüntü Filigranı Ekle PPT
description: PPT Sunumuna Filigran eklemek için C++ kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ kullanarak PPT Sunumuna Filigran ekleyin" h2="Sunucu tarafı API'lerini kullanarak PPT, PPTX veya ODP sunumuna metin veya resim filigranı eklemek için kendi C++ uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPT Sunumuna Filigran Ekleyin" %}}
Aspose.Slides for C++ kullanarak, PPT sunumuna filigran ekleyebilirsiniz. Filigranlar, herhangi bir sunumun önemli bir parçasıdır. Sunum içeriğinin kopyalanmasını veya izinsiz kullanılmasını önlemek için kullanılırlar. Filigran, sunumun üstüne yerleştirilen görünür veya görünmez bir resim veya metindir. Sunum sahibinin kimliğini tespit etmek ve izinsiz kullanımı önlemek için kullanılabilir. Sunuma profesyonel bir dokunuş eklemek ve daha gösterişli görünmesini sağlamak için filigranlar da kullanılabilir. 
{{% blocks/products/pf/agp/code-block title="C++ kullanarak PPT için Metin Filigranı ekleyin" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ kullanarak PPT Sunumuna Resim Filigranı ekleyin" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPT İçin Filigran Nasıl Eklenir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPT dosyalarına metin filigranı ekleme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ana sunumu seçin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape yöntemini kullanarak şekil türü ekleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame yöntemini kullanarak filigran metni ekleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPT biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="C++ kullanarak, Filigranı aşağıdaki biçimlere de ekleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}