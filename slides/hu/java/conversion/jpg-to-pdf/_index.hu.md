---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven
url: /hu/java/conversion/jpg-to-pdf/
keywords: JPG to PDF, JPG konvertálása PDF formátumba, Java API, Java Library, JPG, PDF
description: Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven. Használja a Java könyvtár API-t a JPG fájlok konvertálásához PDF formátumúvá
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven" h2="Nagy sebességű és többplatformos Java Library, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a(z) JPG fájlt PDF formátumra Java használatával" variant="code" %}}

A JPG formátum PDF formátumra konvertálásához létre kell hoznia egy prezentációt a JPG fájlból, és el kell mentenie PDF néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód a JPG PDF formátumba való konvertálásához" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a(z) JPG fájlt PDF formátumra Java nyelven" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) egy hatékony Java-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a JPG PDF formátumra való konvertálására. Az **Aspose.Slides for Java** használatával bármely fejlesztő vagy alkalmazás képes a JPG fájlokat PDF fájlokra konvertálni, mindössze néhány soros Java kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for Java gyorsan exportál JPG fájlokat PDF fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) JPG fájl konvertálását PDF-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A JPG konvertálása PDF formátumba az Aspose.Slides for Java API segítségével" intro="Ezek a lépések a JPG PDF formátumra konvertálásához Java nyelven." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) programot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a Java projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a forrás JPG fájljait Java nyelven.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése PDF fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Az Aspose.Slides segítségével készült" title="JPG konvertálása PDF formátumba online" description="Az ingyenes Aspose.Slides Conversion alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját JPG fájljaival." button="Aspose.Slides Conversion megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" upload="Húzza ide vagy töltse fel a fájlt" saveAs="Mentés másként" convert="Konvertálás" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan konvertálja a fájlokat az Aspose.Slides, mielőtt kódot írna.
- Töltsön fel JPG fájlokat, és mentse őket PDF formátumban.
- Töltse le az eredményt, vagy konvertáljon további fájlokat.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) JPG konvertálása más támogatott formátumokká" subTitle="A JPG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
