---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7490
title: Vytváření grafů PPT pomocí C++
url: /cs/cpp/chart/ppt/ 
description: Ukázkový kód C++ pro vytváření grafů v prezentacích PPT ve Windows a Linuxu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Vytváření grafů v prezentacích PPT pomocí C++" h2="Vytvářejte grafy v prezentacích PPT pomocí serverových API Aspose.Slides for C++ bez Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Vytváření grafů PPT pomocí C++" %}}

Pomocí [Aspose.Slides for C++](/slides/cs/cpp/) vytvoříte grafy v prezentacích PPT. Nainstalujte balíček z [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) nebo použijte následující příkaz v konzole Správce balíčků.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Příkaz" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Vytvoření grafu v PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slide(0);

// Add a chart with default data.
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0, 0, 500, 500);

// Set the index of the chart data sheet.
int defaultWorksheetIndex = 0;

// Get the chart data workbook.
auto chartDataWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();

// Set the chart title.
chart->get_ChartTitle()->AddTextFrameForOverriding(u"Sample Title");
chart->get_ChartTitle()->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chart->get_ChartTitle()->set_Height(20);
chart->set_HasTitle(true);

// Delete the default generated series and categories.
chart->get_ChartData()->get_Series()->Clear();
chart->get_ChartData()->get_Categories()->Clear();

// Add series.
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 1, ObjectExt::Box(String(u"Series 1"))), chart->get_Type());
chart->get_ChartData()->get_Series()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 0, 2, ObjectExt::Box(String(u"Series 2"))), chart->get_Type());

// Add categories.
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 0, ObjectExt::Box(String(u"Category 1"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 0, ObjectExt::Box(String(u"Category 2"))));
chart->get_ChartData()->get_Categories()->Add(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 0, ObjectExt::Box(String(u"Category 3"))));

// Take the first chart series.
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 1, ObjectExt::Box(20)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 1, ObjectExt::Box(50)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 1, ObjectExt::Box(30)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Blue());

// Take the second chart series.
series = chart->get_ChartData()->get_Series()->idx_get(1);

// Populate series data.
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 1, 2, ObjectExt::Box(30)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 2, 2, ObjectExt::Box(10)));
series->get_DataPoints()->AddDataPointForBarSeries(chartDataWorkbook->GetCell(defaultWorksheetIndex, 3, 2, ObjectExt::Box(60)));

// Set the fill color for the series.
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Orange());

// Show the category name for the first label.
auto dataLabel = series->get_DataPoints()->idx_get(0)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowCategoryName(true);

dataLabel = series->get_DataPoints()->idx_get(1)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);

// Show the value for the third label.
dataLabel = series->get_DataPoints()->idx_get(2)->get_Label();
dataLabel->get_DataLabelFormat()->set_ShowValue(true);
dataLabel->get_DataLabelFormat()->set_ShowSeriesName(true);
dataLabel->get_DataLabelFormat()->set_Separator(u"/");

// Save the PPT file.
presentation->Save(u"column_chart.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak vytvářet grafy v souborech PPT pomocí C++" intro="Vytvořte graf v prezentaci PPT pomocí Aspose.Slides for C++ v několika řádcích kódu." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte objekt `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte přístup k prvnímu snímku.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte graf s výchozími daty.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nastavte index datového listu grafu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Získejte sešit s daty grafu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nastavte název grafu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odstraňte výchozí vygenerované řady a kategorie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte řady a kategorie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vezměte první řadu grafu a naplňte její data.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nastavte barvu výplně řady.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zobrazte v popiscích dat druhé řady název kategorie, název řady a hodnotu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte soubor PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Systémové požadavky" intro="Aspose.Slides for C++ podporuje hlavní platformy a operační systémy. Ujistěte se, že vaše prostředí splňuje následující předpoklady." %}}

-  Microsoft Windows, Linux, macOS nebo jiný kompatibilní operační systém s podporovaným běhovým prostředím C++.
-  Knihovna Aspose.Slides for C++ odkazovaná ve vašem projektu.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/chart-app label="Vytvořeno pomocí Aspose.Slides" title="Vytváření grafů PPT online" description="Bezplatná aplikace Aspose.Slides Chart je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Chart" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides vytváří grafy, ještě než napíšete kód.
- Vytvořte graf z dat v Excelu nebo z tabulky.
- Stáhněte jej jako soubor PPT nebo jako obrázek.
{{< /blocks/products/pf/slides-design-update-10-2026/chart-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Soubor PPT obsahuje sadu snímků pro prezentaci. Používá binární formát souboru aplikace Microsoft PowerPoint 97-2003. Soubor PPT může obsahovat text, odrážky, obrázky, multimédia a další vložené objekty OLE. Microsoft zavedl novější formát PPTX v aplikaci PowerPoint 2007. PPTX je založen na Office Open XML a liší se od staršího binárního formátu. Soubory PPT umí vytvářet i další aplikace, například OpenOffice Impress a Apple Keynote.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro grafy" subTitle="Pomocí C++ můžete vytvářet grafy i v dalších formátech." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/chart/pptx/" name="PPTX" description="Formát prezentací Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
