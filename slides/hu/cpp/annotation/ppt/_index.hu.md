---
title: Távolítsa el a PPT megjegyzést a C++ használatával
weight: 4380
url: /hu/cpp/annotation/ppt/ 
description: C++ forráskód a megjegyzések törléséhez a PPT-ből
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Távolítsa el a megjegyzéseket és a megjegyzés szerzőket a PPT-ből C++ nyelven" h2="Készítse el saját C++ alkalmazásait, hogy manipulálja a megjegyzéseket és a szerzőket a dokumentumfájlokban szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a megjegyzéseket a PPT-ből a C++ segítségével" %}}
A megjegyzések PPT-fájlból való eltávolításához az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) API-t használjuk, amely funkciókban gazdag, hatékony és könnyen használható. dokumentummanipulációs API C++ platformhoz.
{{% blocks/products/pf/agp/code-block title="Annotációk törlése a PPT - C++ programból" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Hogyan távolítsunk el megjegyzéseket a PPT-ről C++-on keresztül" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for C++** alkalmazást. Lásd: [**Telepítés**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a PPT-t a Presentation osztály egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ismételje meg a betöltött PPT összes szerzőjét
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Távolítsa el a szerző összes megjegyzését
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A végén távolítsa el az összes szerzőt
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott megjegyzésformátumok" subTitle="A C++ használatával könnyen megjegyzéseket fűzhet más formátumokhoz, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}