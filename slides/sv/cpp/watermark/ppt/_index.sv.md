---
title: Lägg till vattenstämpel i PPT presentationsfiler med C++
url: /sv/cpp/watermark/ppt/
keywords: Lägg till vattenstämpel PPT, Lägg till textvattenstämpel PPT, Lägg till bildvattenstämpel PPT
description: Källkod för C++ för att lägga till vattenstämpel i presentationen PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lägg till vattenstämpel i presentationen PPT med C++" h2="Bygg dina egna C++-appar för att infoga text- eller bildvattenstämplar i PPT-, PPTX- eller ODP-presentationer med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till vattenstämpel i presentationen PPT via C++" %}}
Med Aspose.Slides for C++ kan du lägga till vattenstämpel i presentationen av PPT. Vattenstämplar är en viktig del av alla presentationer. De används för att skydda innehållet i presentationen från att kopieras eller användas utan tillstånd. En vattenstämpel är en synlig eller osynlig bild eller text som placeras ovanpå presentationen. Den kan användas för att identifiera ägaren till presentationen och för att förhindra obehörig användning. Vattenstämplar kan också användas för att sätta en professionell touch till presentationen och få den att se mer polerad ut. 
{{% blocks/products/pf/agp/code-block title="Lägg till textvattenstämpel i PPT med C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lägg till bildvattenstämpel i PPT presentation med C++" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Så här lägger du till vattenstämpel i PPT via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att lägga till textvattenstämpel i PPT-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT med en instans av Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Välj huvudpresentationen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till formtyp med metoden AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till vattenstämpeltext med AddTextFrame-metoden
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra format som stöds" subTitle="Med C++ kan du också lägga till vattenstämpel i följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}