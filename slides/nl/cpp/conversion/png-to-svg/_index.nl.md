---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PNG naar SVG in C++
url: /nl/cpp/conversion/png-to-svg/
keywords: PNG naar SVG, Converteer PNG naar SVG, C++ API, C++ Library, PNG, SVG
description: Converteer PNG naar SVG in C++. Gebruik de C++-bibliotheek-API om PNG-bestanden naar SVG-bestanden te converteren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PNG naar SVG in C++" h2="Snelle en platformonafhankelijke C++-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PNG naar SVG met behulp van C++" variant="code" %}}

Om de PNG naar SVG te converteren, moet u een presentatie maken van het PNG-bestand en deze opslaan als SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-code voor het converteren van PNG naar SVG" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = pres->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PNG naar SVG in C++" %}}

[**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/) is een krachtige C++-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om PNG naar SVG te converteren. Met **Aspose.Slides voor C++** kan elke ontwikkelaar of toepassing PNG naar SVG bestanden converteren met slechts een paar regels C++-code.

Aspose.Slides voor C++ is een moderne documentverwerkings-API en exporteert snel PNG-bestanden naar SVG-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u PNG naar SVGs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PNG naar SVG te converteren met Aspose.Slides voor C++ API" intro="Dit zijn de stappen om PNG naar SVG in C++ te converteren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer [**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw C++-project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open de bronbestanden PNG in C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla resultaat op als SVG bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Gebouwd met Aspose.Slides" title="PNG online converteren naar SVG" description="De gratis app Aspose.Slides Conversion is gebouwd met [Aspose.Slides for C++](https://products.aspose.com/slides/nl/cpp/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PNG-bestanden." button="Aspose.Slides Conversion openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" upload="Sleep of upload uw bestand" saveAs="Opslaan als" convert="Converteren" >}}
- Werkt in uw browser, niets te installeren.
- Bekijk hoe Aspose.Slides bestanden converteert voordat u code schrijft.
- Upload PNG-bestanden en sla ze op als SVG.
- Download het resultaat of converteer meer bestanden.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converteer PNG naar andere ondersteunde formaten" subTitle="U kunt PNG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
