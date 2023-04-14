---
title: A JPG konvertálása PDF formátumra C++ nyelven
url: /hu/cpp/conversion/jpg-to-pdf/
keywords: JPG to PDF, JPG konvertálása PDF formátumba, C++ API, C++ Library, JPG, PDF
description: A JPG konvertálása PDF formátumra C++ nyelven. Használja a C++ könyvtár API-t a JPG fájlok konvertálásához PDF formátumúvá
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="A JPG konvertálása PDF formátumra C++ nyelven" h2="Nagy sebességű és többplatformos C++ könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="A JPG konvertálása PDF formátumra C++ nyelven" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) egy hatékony C++ könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a JPG PDF formátumra való konvertálására. Az **Aspose.Slides for C++** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a JPG fájlokat PDF fájlokra, mindössze néhány sornyi C++ kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for C++ gyorsan exportál JPG fájlokat PDF fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) JPG fájl konvertálását PDF-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A JPG konvertálása PDF formátumra C++ használatával" %}}
A JPG formátum PDF formátumra konvertálásához létre kell hoznia egy prezentációt a JPG fájlból, és el kell mentenie PDF néven.

{{% blocks/products/pf/agp/code-block title="C++ kód a JPG PDF formátumba való konvertálásához" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A JPG konvertálása PDF formátumba az Aspose.Slides for C++ API használatával" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a JPG konvertálásához PDF-re C++ nyelven." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) programot.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a C++ projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás JPG fájljait C++ nyelven.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PDF fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) JPG konvertálása más támogatott formátumokká" subTitle="A JPG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}