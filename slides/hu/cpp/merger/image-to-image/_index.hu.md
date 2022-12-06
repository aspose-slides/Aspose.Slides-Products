---
title: Képek egyesítése C++-ban
url: /hu/cpp/merger/image-to-image/
keywords: Kép egyesítése, kép képhez, képek összekapcsolása, képek kombinálása, C++ API, C++ könyvtár
description: Kép egyesítése képpel C++-ban. Használja a C++ könyvtár API-t a képek kombinálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Kép egyesítése C++-ban" h2="Nagy sebességű és többplatformos C++ könyvtár képek egyesítéséhez C++ kóddal" >}}

{{% blocks/products/pf/feature-page-section h2="Kép egyesítése képpel az Aspose.Slides segítségével" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) egy hatékony C++ könyvtár, amellyel prezentációkat, képeket és egyéb fájlokat egyesíthet és kezelhet. Ha képet egyesít képpel, akkor hatékonyan kombinál két képet, hogy egy képet kapjon.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Kép egyesítése képpel C++-ban" %}}
Az [**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) használatával gyorsan egyesíthet képfájlokat, mindössze néhány sornyi kóddal.

{{% blocks/products/pf/agp/code-block title="C++ kód a kép képhez egyesítéséhez" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet képeket egyesíteni C++-ban" >}}


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
Töltse be az egyesíteni kívánt képeket képkeretként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a kapott képet.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Más fájlok egyesítése" subTitle="Más formátumú fájlokat is kombinálhat egyetlen fájl létrehozásához" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}