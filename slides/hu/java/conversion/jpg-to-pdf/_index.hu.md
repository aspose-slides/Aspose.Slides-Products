---
title: Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven
url: /hu/java/conversion/jpg-to-pdf/
keywords: JPG to PDF, JPG konvertálása PDF formátumba, Java API, Java Library, JPG, PDF
description: Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven. Használja a Java könyvtár API-t a JPG fájlok konvertálásához PDF formátumúvá
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven" h2="Nagy sebességű és többplatformos Java Library, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) egy hatékony Java-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a JPG PDF formátumra való konvertálására. Az **Aspose.Slides for Java** használatával bármely fejlesztő vagy alkalmazás képes a JPG fájlokat PDF fájlokra konvertálni, mindössze néhány soros Java kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Java gyorsan exportál JPG fájlokat PDF fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) JPG fájl konvertálását PDF-re és sok más fájlformátumra

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a(z) JPG fájlt PDF formátumra Java használatával" %}}
A JPG formátum PDF formátumra konvertálásához létre kell hoznia egy prezentációt a JPG fájlból, és el kell mentenie PDF néven.

{{% blocks/products/pf/agp/code-block title="Java kód a JPG PDF formátumba való konvertálásához" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A JPG konvertálása PDF formátumba az Aspose.Slides for Java API segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a JPG PDF formátumra konvertálásához Java nyelven." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Telepítse az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) programot.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Java projekthez.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nyissa meg a forrás JPG fájljait Java nyelven.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése PDF fájlként.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="A(z) JPG konvertálása más támogatott formátumokká" subTitle="A JPG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}