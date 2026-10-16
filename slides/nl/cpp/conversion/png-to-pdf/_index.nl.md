---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PNG naar PDF in C++
url: /nl/cpp/conversion/png-to-pdf/
keywords: PNG naar PDF, Converteer PNG naar PDF, C++ API, C++ Library, PNG, PDF
description: Converteer PNG naar PDF in C++. Gebruik de C++-bibliotheek-API om PNG-bestanden naar PDF-bestanden te converteren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PNG naar PDF in C++" h2="Snelle en platformonafhankelijke C++-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PNG naar PDF met behulp van C++" variant="code" %}}

Om de PNG naar PDF te converteren, moet u een presentatie maken van het PNG-bestand en deze opslaan als PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-code voor het converteren van PNG naar PDF" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PNG naar PDF in C++" %}}

[**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/) is een krachtige C++-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om PNG naar PDF te converteren. Met **Aspose.Slides voor C++** kan elke ontwikkelaar of toepassing PNG naar PDF bestanden converteren met slechts een paar regels C++-code.

Aspose.Slides voor C++ is een moderne documentverwerkings-API en exporteert snel PNG-bestanden naar PDF-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u PNG naar PDFs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PNG naar PDF te converteren met Aspose.Slides voor C++ API" intro="Dit zijn de stappen om PNG naar PDF in C++ te converteren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer [**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw C++-project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open de bronbestanden PNG in C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla resultaat op als PDF bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis online converter"
  description="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converteer PNG naar andere ondersteunde formaten" subTitle="U kunt PNG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
