---
title: C++ aracılığıyla PPTX belge grafiği
weight: 5370
url: /tr/cpp/chart/pptx/ 
description: Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment üzerinde PPTX dosyasında çizelge veya diyagram çizmek ve dönüştürmek için C++ örnek kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPTX Biçimleri Grafikleri C++'da" h2="Microsoft veya Adobe PDF gibi herhangi bir yazılım kullanmadan C++ API'leri için sunucu tarafı Aspose.Slides kullanan yerel ve yüksek performanslı PPTX belge çizelgeleri." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides.cpp" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak PPTX Dosya Grafikleri Nasıl Oluşturulur" %}}

 PPTX dosyasını aramak için kullanacağız
 [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/)
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay belge arama API'si olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 paket yöneticisi, ara
 **Aspose.Slides.Cpp**
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="C++'da PPTX Dosya Grafikleri Oluşturma Adımları" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="[Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) API'leri ile basit bir belge grafiği sadece birkaç satır kodla yapılabilir." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Anlık Sunum sınıfı.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
İlk slayta erişin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Varsayılan verilerle grafik ekleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Grafik veri sayfasının dizinini ayarlayın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Grafik verileri çalışma kitabını alın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Grafik Başlığı ayarlayın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Varsayılan oluşturulan serileri ve kategorileri silin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Seriler ve kategoriler ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
İlk grafik serisini alın ve verileri doldurun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Seriler için dolgu rengini ayarlayın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyasını kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C++ tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.
- Projenizde referans verilen C++ DLL için Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPTX Dosyaları Tablosu Oluştur - C++" offSpacer="" %}}

```cs
// Output File Path.
const String outputFilePath = u"OutputDirectory\\column_chart.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> pres = MakeObject<Presentation>();

// Access first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add chart with default data
SharedPtrv<IChart> chart = slide->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::ClusteredColumn, 0, 0, 500, 500);

// Setting the index of chart data sheet
int defaultWorksheetIndex = 0;

// Getting the chart data workbook
SharedPtr<IChartDataWorkbook> fact = chart->get_ChartData()->get_ChartDataWorkbook();

// Setting chart Title
chart->get_ChartTitle()->AddTextFrameForOverriding(u"Sample Title");
chart->get_ChartTitle()->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chart->get_ChartTitle()->set_Height(20);
chart->set_HasTitle(true);

// Delete default generated series and categories
chart->get_ChartData()->get_Series()->Clear();
chart->get_ChartData()->get_Categories()->Clear();
int s = chart->get_ChartData()->get_Series()->get_Count();
s = chart->get_ChartData()->get_Categories()->get_Count();

// Add series
chart->get_ChartData()->get_Series()->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, ObjectExt::Box<System::String>(u"Series 1")), chart->get_Type());
chart->get_ChartData()->get_Series()->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, ObjectExt::Box<System::String>(u"Series 2")), chart->get_Type());

// Add categories
chart->get_ChartData()->get_Categories()->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, ObjectExt::Box<System::String>(u"Category 1")));
chart->get_ChartData()->get_Categories()->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, ObjectExt::Box<System::String>(u"Category 2")));
chart->get_ChartData()->get_Categories()->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, ObjectExt::Box<System::String>(u"Category 3")));

// Take first chart series
SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);

// Populate series data
series->get_DataPoints()->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, ObjectExt::Box(20)));
series->get_DataPoints()->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, ObjectExt::Box(50)));
series->get_DataPoints()->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, ObjectExt::Box(30)));

// Setting fill color for series
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());

// Take second chart series
series = chart->get_ChartData()->get_Series()->idx_get(1);

// Populate series data
series->get_DataPoints()->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, ObjectExt::Box(30)));
series->get_DataPoints()->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, ObjectExt::Box(10)));
series->get_DataPoints()->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, ObjectExt::Box(60)));

// Setting fill color for series
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Orange());

// First label will be show Category name
SharedPtr<IDataLabel> lbl = series->get_DataPoints()->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);

lbl = series->get_DataPoints()->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);

// Show value for third label
lbl = series->get_DataPoints()->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");

// Save PPTX file
pres->Save(outputFilePath, Aspose::Slides::Export::SaveFormat::Pptx);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides for C++ API Hakkında" %}}

 Sayfamızı ziyaret ederek hemen şimdi PPTX belge çizelgeleri oluşturun.
 [Canlı Demolar web sitesi](https://products.aspose.app/slides/chart)
 . Canlı demo aşağıdaki avantajlara sahiptir



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Chart Creation Live Demos" sectionDescription="Generate PPTX documents charts right now by visiting our [Live Demos website](https://products.aspose.app/slides/chart). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Chart will be created instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Grafik Formatları" subTitle="C++ kullanarak, aşağıdakiler de dahil olmak üzere farklı formatlarla kolayca başa çıkabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/chart/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}