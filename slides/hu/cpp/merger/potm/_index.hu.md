---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Egyesítse a POTM fájlokat a C++ segítségével
weight: 7950
url: /hu/cpp/merger/potm/ 
description: C++ példakód a POTM dokumentumok kombinálásához C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Egyesítse a POTM fájlokat a C++ használatával" h2="POTM dokumentum-egyesítés szerveroldali C++ API-kkal."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="POTM-fájl egyesítése C++ használatával" %}}

A POTM-fájl egyesítéséhez használjuk
 [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentum-egyesítési API C++ platformhoz. A legújabb verziót közvetlenül letöltheti, csak nyissa meg
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 csomagkezelő, keressen
 **Aspose.Slides.Cpp**
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM fájlok egyesítése - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.potm";
const String sourceFilePath2 = u"SourceFile3.potm";
const String outputFilePath = u"mergedOutput.potm";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Potm);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="A POTM-fájlok egyesítésének lépései C++-ban" intro="Az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) API-kkal való egyesítése és összefűzése néhány sornyi kóddal elvégezhető." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mindkét POTM fájl betöltése.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Használja a get\_Slides() metódust az egyes diák áthaladásához.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az AddClone funkcióval egyesítheti a kívánt fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Használja a Save() metódust a megadott elérési úton történő mentéshez{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="Az Aspose.Slides for C++ támogatja az összes főbb platformon és operációs rendszeren. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ futási környezettel Windows 32 bites, Windows 64 bites és Linux 64 bites rendszerhez.
- Aspose.Slides for C++ DLL, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="PDF fájlok online egyesítése"
  description="[Hogyan lehet PDF-et egyesíteni Pythonban](https://products.aspose.com/slides/hu/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

A `.POTM` kiterjesztésű fájlok makrókat támogató Microsoft PowerPoint-sablonok, amelyeket a PowerPoint 2007 vezetett be. Újrafelhasználható bemutatóbeállításokat tárolhatnak, például elrendezéseket, stílusokat, háttereket, színpalettákat, betűtípusokat, alapértelmezett formázást és VBA-makrókat. A PowerPoint 2007 és újabb verziói meg tudják nyitni és szerkeszteni a POTM-fájlokat.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott egyesítő formátumok" subTitle="A C++ használatával sok más fájlformátum is egyesíthető, beleértve." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/odp/" name="ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/otp/" name="OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pps/" name="PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/ppsm/" name="PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/ppsx/" name="PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pptm/" name="PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pptx/" name="PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
