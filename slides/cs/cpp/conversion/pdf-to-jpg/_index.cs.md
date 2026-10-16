---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převeďte PDF do JPG v C++
url: /cs/cpp/conversion/pdf-to-jpg/
keywords: PDF do JPG, Převést PDF do JPG, C++ API, C++ Library, PDF, JPG
description: Převeďte PDF do JPG v C++. Použijte API knihovny C++ k převodu souborů PDF na JPGs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převeďte PDF do JPG v C++" h2="Vysokorychlostní a multiplatformní knihovna C++, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF do JPG pomocí C++" variant="code" %}}

Chcete-li převést PDF do JPG, budete muset vytvořit prezentaci ze souboru PDF a uložit ji jako JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ kód pro převod PDF do JPG" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"InputPDF.pdf");
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
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".jpg");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Jpeg());
}

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převeďte PDF do JPG v C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/) je výkonná knihovna C++ pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu PDF do JPG. Pomocí **Aspose.Slides for C++** může každý vývojář nebo aplikace převést soubory PDF do JPG pomocí několika řádků kódu C++.

Aspose.Slides pro C++ jako moderní API pro zpracování dokumentů rychle exportuje soubory PDF do formátů souborů JPG. Knihovna Aspose PowerPoint vám umožňuje převést PDF do JPGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést PDF do JPG pomocí Aspose.Slides for C++ API" intro="Toto jsou kroky pro převod PDF do JPG v C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete zdrojové soubory PDF v C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložit výsledek jako soubor JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Zdarma online konvertor"
  description="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Převést PDF do jiných podporovaných formátů" subTitle="Můžete také převést PDF a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
