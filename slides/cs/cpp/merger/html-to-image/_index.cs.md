---
title: Sloučit HTML do obrázku v C++
url: /cs/cpp/merger/html-to-image/
keywords: Sloučit HTML s obrázkem, HTML s obrázkem, Připojit HTML, Kombinovat HTML, Obrázek, C++ API, C++ knihovna
description: Sloučit HTML do obrázku v C++. Pomocí API knihovny C++ zkombinujte HTML s obrázkem
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Sloučit obrázek v C++" h2="Vysokorychlostní a multiplatformní knihovna C++ pro sloučení HTML s obrázkem pomocí kódu C++" >}}

{{% blocks/products/pf/feature-page-section h2="Sloučit HTML do obrázku pomocí Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/) je výkonná knihovna C++ používaná ke slučování a manipulaci s prezentacemi, dokumenty HTML a dalšími soubory. Když sloučíte HTML do obrázku, efektivně kombinujete obsah v HTML dokumentech, abyste získali jeden obrázek. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Sloučit HTML do obrázku v C++" %}}
Pomocí [**Aspose.Slides for C++**](https://products.aspose.com/slides/cs/cpp/) můžete rychle sloučit soubory obrázků pomocí několika řádků kódu

{{% blocks/products/pf/agp/code-block title="C++ kód pro sloučení HTML do obrázku" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);
pres->get_Slides()->AddFromHtml(htmlText2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Jak sloučit HTML do obrázku v C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides pro C++**. Viz [**Instalace**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte dokumenty HTML, které chcete sloučit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný obrázek.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Sloučit další soubory" subTitle="Můžete také kombinovat soubory v jiných formátech a získat tak jeden soubor" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}