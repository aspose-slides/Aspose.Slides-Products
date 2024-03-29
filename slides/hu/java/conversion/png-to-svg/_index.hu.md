---
title: Konvertálja a(z) PNG fájlt SVG formátumra Java nyelven
url: /hu/java/conversion/png-to-svg/
keywords: PNG to SVG, PNG konvertálása SVG formátumba, Java API, Java Library, PNG, SVG
description: Konvertálja a(z) PNG fájlt SVG formátumra Java nyelven. Használja a Java könyvtár API-t a PNG fájlok konvertálásához SVG formátumúvá
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a(z) PNG fájlt SVG formátumra Java nyelven" h2="Nagy sebességű és többplatformos Java Library, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a(z) PNG fájlt SVG formátumra Java nyelven" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) egy hatékony Java-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a PNG SVG formátumra való konvertálására. Az **Aspose.Slides for Java** használatával bármely fejlesztő vagy alkalmazás képes a PNG fájlokat SVG fájlokra konvertálni, mindössze néhány soros Java kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Java gyorsan exportál PNG fájlokat SVG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) PNG fájl konvertálását SVG-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a(z) PNG fájlt SVG formátumra Java használatával" %}}
A PNG formátum SVG formátumra konvertálásához létre kell hoznia egy prezentációt a PNG fájlból, és el kell mentenie SVG néven.

{{% blocks/products/pf/agp/code-block title="Java kód a PNG SVG formátumba való konvertálásához" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A PNG konvertálása SVG formátumba az Aspose.Slides for Java API segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a PNG SVG formátumra konvertálásához Java nyelven." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) programot.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Java projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás PNG fájljait Java nyelven.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése SVG fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) PNG konvertálása más támogatott formátumokká" subTitle="A PNG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}