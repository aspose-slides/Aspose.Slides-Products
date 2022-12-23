---
title: Szerkessze a PPT-t C++-ban
url: /hu/cpp/editor/ppt/
keywords: PPT szerkesztése, PowerPoint szerkesztése, PPT, PowerPoint, C++ API, C++ Library
description: Szerkessze a PPT-t C++-ban. Használja a C++ könyvtár API-t a PowerPoint prezentáció szerkesztéséhez
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Szerkessze a PPT-t C++-ban" h2="Nagy sebességű és többplatformos C++ könyvtár a PPT szerkesztéséhez C++ kóddal" >}}

{{% blocks/products/pf/feature-page-section h2="Szerkessze a PPT-t az Aspose.Slides segítségével" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) egy hatékony C++-könyvtár, amelyet prezentációk kezelésére és szerkesztésére használnak. A PPT prezentációt úgy szerkesztheti, hogy új szövegsort ad hozzá. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Szerkessze a PPT-t C++-ban" %}}
Az [**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) használatával mindössze néhány sornyi kóddal új szövegsort adhat hozzá egy PPT-dokumentumhoz.

{{% blocks/products/pf/agp/code-block title="C++ kód a PPT szerkesztéséhez" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet PPT-t szerkeszteni C++-ban" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az **Aspose.Slides for C++** alkalmazást. Lásd: [**Telepítés**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adja hozzá a könyvtárat referenciaként a projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Prezentáció osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a szerkeszteni kívánt PPT-prezentációt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy új szövegsort.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a módosított PowerPoint fájlt.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Más fájlok szerkesztése" subTitle="Más formátumú fájlokat is szerkeszthet" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}