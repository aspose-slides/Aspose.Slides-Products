---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Egyesítse az OTP fájlokat C++ segítségével
weight: 4580
url: /hu/cpp/merger/otp/ 
description: C++ példakód az OTP dokumentumok kombinálásához C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Egyesítse az OTP fájlokat a C++ használatával" h2="OTP dokumentum-egyesítés szerveroldali C++ API-kkal."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hogyan egyesítsünk OTP fájlt C++ használatával" %}}

Az OTP-fájl egyesítéséhez használjuk
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP fájlok egyesítése - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.otp";
const String sourceFilePath2 = u"SourceFile3.otp";
const String outputFilePath = u"mergedOutput.otp";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Otp);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Az OTP fájlok egyesítésének lépései C++ nyelven" intro="Az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) API-kkal való egyesítése és összefűzése néhány sornyi kóddal elvégezhető." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be mindkét OTP-fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Használja a get\_Slides() metódust az egyes diák áthaladásához.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az AddClone funkcióval egyesítheti a kívánt fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Használja a Save() metódust a megadott elérési úton történő mentéshez{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="Az Aspose.Slides for C++ támogatja az összes főbb platformon és operációs rendszeren. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ futási környezettel Windows 32 bites, Windows 64 bites és Linux 64 bites rendszerhez.
- Aspose.Slides for C++ DLL, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Az Aspose.Slides segítségével készült" title="OTP fájlok egyesítése online" description="Az ingyenes Aspose.Slides Merger alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját OTP fájljaival." button="Aspose.Slides Merger megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan egyesíti a fájlokat az Aspose.Slides, mielőtt kódot írna.
- Töltsön fel több OTP fájlt, és egyesítse őket egyetlen fájlba.
- Töltse le az egyesített eredményt egyetlen fájlként.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

A `.OTP` kiterjesztésű fájlok OpenDocument-bemutatósablonok. Újrafelhasználható elrendezéseket, stílusokat, formázást, háttereket és egyéb tartalmat tárolnak, amelyekkel egységes megjelenésű új bemutatók készíthetők. Az OTP-fájlokat az OpenDocument Format (ODF) formátumot támogató alkalmazások hozhatják létre és nyithatják meg. A formátum a Microsoft PowerPoint POT és POTX sablonformátumaihoz hasonlítható.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott egyesítő formátumok" subTitle="A C++ használatával sok más fájlformátum is egyesíthető, beleértve." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/odp/" name="ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pps/" name="PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/ppsm/" name="PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/ppsx/" name="PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pptm/" name="PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/cpp/merger/pptx/" name="PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
