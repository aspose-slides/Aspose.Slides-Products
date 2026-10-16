---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A TIFF konvertálása XML-re C++ alkalmazással
weight: 2670
url: /hu/cpp/conversion/tiff-to-xml/ 
description: Minta C++ konverziós kód TIFF dokumentumhoz XML formátumba. Használjon példakódot a kötegelt TIFF-ből XML-be konvertálásához bármely C++ alkalmazáson belül.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja a TIFF-et XML-re C++ segítségével" h2="Nagy teljesítményű TIFF-XML konvertálás C++ könyvtár használatával Microsoft PowerPoint telepítése nélkül."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="TIFF konvertálása XML-re C++ használatával" %}}

A TIFF XML-re konvertálásához használjuk
 [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API C++ platformhoz. A legújabb verziót közvetlenül letöltheti, csak nyissa meg
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 csomagkezelő, keressen
 Aspose.Slides.Cpp
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Parancs" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="TIFF-ből XML-be C++ konvertáló forráskód" >}}
```cs
// Load the TIFF.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.tiff");
// Save in XML format.
for (int32_t index = 0; index < prs->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.xml", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = prs->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Lépések a TIFF XML-re konvertálásához C++ segítségével" intro="A C++ fejlesztők könnyedén konvertálhatják a TIFF fájlokat XML-re, mindössze néhány sornyi kóddal." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be az Aspose.Slides for C++ Presentation Object TIFF fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a Save() metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja meg a kimeneti fájl elérési útját (XML) fájlkiterjesztéssel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az XML fájl a megadott elérési útra kerül mentésre.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg az XML fájlt egy kompatibilis programban.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="A C++ konverziós példakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ futási környezettel Windows 32 bites, Windows 64 bites és Linux 64 bites rendszerhez.
- Aspose.Slides for C++ DLL, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes alkalmazás a TIFF konvertálásához XML -re"
  description="[Próbálja ki az ingyenes Collage alkalmazást](https://products.aspose.app/slides/collage/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A TIFF-et számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt ​​fájlformátumra." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="Továbbfejlesztett metafájl formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-ppsm/" name="TIFF TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
