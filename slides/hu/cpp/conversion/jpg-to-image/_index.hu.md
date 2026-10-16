---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A JPG konvertálása Image formátumra C++ nyelven
url: /hu/cpp/conversion/jpg-to-image/
keywords: JPG to Image, JPG konvertálása Image formátumba, C++ API, C++ Library, JPG, Image
description: A JPG konvertálása Image formátumra C++ nyelven. Használja a C++ könyvtár API-t a JPG fájlok konvertálásához Image formátumúvá
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A JPG konvertálása Image formátumra C++ nyelven" h2="Nagy sebességű és többplatformos C++ könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására olyan szoftverek használata nélkül, mint a Microsoft vagy az Open Office, az Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A JPG konvertálása Image formátumra C++ használatával" variant="code" %}}

A JPG formátum Image formátumra konvertálásához létre kell hoznia egy prezentációt a JPG fájlból, és el kell mentenie Image néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ kód a JPG Image formátumba való konvertálásához" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
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
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A JPG konvertálása Image formátumra C++ nyelven" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) egy hatékony C++ könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a JPG Image formátumra való konvertálására. Az **Aspose.Slides for C++** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a JPG fájlokat Image fájlokra, mindössze néhány sornyi C++ kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for C++ gyorsan exportál JPG fájlokat Image fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) JPG fájl konvertálását Image-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A JPG konvertálása Image formátumba az Aspose.Slides for C++ API használatával" intro="Ezek a lépések a JPG konvertálásához Image-re C++ nyelven." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for C++**](https://products.aspose.com/slides/hu/cpp/) programot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a C++ projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a forrás JPG fájljait C++ nyelven.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése Image fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes online konverter"
  description="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) JPG konvertálása más támogatott formátumokká" subTitle="A JPG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
