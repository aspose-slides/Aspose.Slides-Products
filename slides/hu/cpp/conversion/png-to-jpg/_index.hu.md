---
title: A PNG konvertálása JPG formátumra C++ nyelven
url: /hu/cpp/conversion/png-to-jpg/
keywords: PNG to JPG, PNG konvertálása JPG formátumba, C++ API, C++ Library, PNG, JPG
description: A PNG konvertálása JPG formátumra C++ nyelven. Használja a C++ könyvtár API-t a PNG fájlok konvertálásához JPG formátumúvá
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="A PNG konvertálása JPG formátumra C++ nyelven" h2="Nagy sebességű és többplatformos C++ könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="A PNG konvertálása JPG formátumra C++ nyelven" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) egy hatékony C++ könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a PNG JPG formátumra való konvertálására. Az **Aspose.Slides for C++** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a PNG fájlokat JPG fájlokra, mindössze néhány sornyi C++ kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for C++ gyorsan exportál PNG fájlokat JPG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) PNG fájl konvertálását JPG-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A PNG konvertálása JPG formátumra C++ használatával" %}}
A PNG formátum JPG formátumra konvertálásához létre kell hoznia egy prezentációt a PNG fájlból, és el kell mentenie JPG néven.

{{% blocks/products/pf/agp/code-block title="C++ kód a PNG JPG formátumba való konvertálásához" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".jpg");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Jpeg());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PNG konvertálása JPG formátumba az Aspose.Slides for C++ API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PNG konvertálásához JPG-re C++ nyelven." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) programot.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a C++ projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás PNG fájljait C++ nyelven.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése JPG fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) PNG konvertálása más támogatott formátumokká" subTitle="A PNG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}