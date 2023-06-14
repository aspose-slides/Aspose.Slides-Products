---
title: Vízjel hozzáadása a PPT prezentációs fájlokhoz a C++ használatával
url: /hu/cpp/watermark/ppt/
keywords: Vízjel hozzáadása PPT, Szöveg vízjel hozzáadása PPT, Kép vízjel hozzáadása PPT
description: C++ forráskód vízjel hozzáadásához a PPT prezentációhoz.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Vízjel hozzáadása a PPT prezentációhoz a C++ használatával" h2="Készítse el saját C++ alkalmazásait, amellyel szöveget vagy képet illeszthet be PPT-, PPTX- vagy ODP-prezentációba szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Vízjel hozzáadása a PPT prezentációhoz a C++ segítségével" %}}
A Aspose.Slides for C++ használatával vízjelet adhat a PPT prezentációhoz. A vízjelek minden prezentáció elengedhetetlen részét képezik. Arra szolgálnak, hogy megvédjék a prezentáció tartalmát az engedély nélküli másolástól vagy felhasználástól. A vízjel egy látható vagy láthatatlan kép vagy szöveg, amely a prezentáció tetejére kerül. Segítségével azonosítható a prezentáció tulajdonosa, és megakadályozható a jogosulatlan használat. A vízjelek arra is használhatók, hogy professzionális hatást keltsenek a prezentációban, és még csiszoltabbnak tűnjenek. 
{{% blocks/products/pf/agp/code-block title="Szöveges vízjel hozzáadása a PPT fájlhoz a C++ használatával" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kép vízjel hozzáadása a PPT prezentációhoz a C++ használatával" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Vízjel hozzáadása a PPT fájlhoz a C++ segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a szöveges vízjel hozzáadásához a PPT fájlokhoz." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A PPT betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Válassza ki a fő bemutatót
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá alaktípust az AddAutoShape módszerrel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá vízjelszöveget az AddTextFrame módszerrel
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PPT formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott formátumok" subTitle="A C++ használatával a következő formátumokhoz is hozzáadhat vízjelet:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}