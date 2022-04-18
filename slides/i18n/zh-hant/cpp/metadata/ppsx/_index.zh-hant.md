---
title: 通過 C++ 編輯或查看 PPSX 文檔元數據
weight: 5520
url: /zh-hant/cpp/metadata/ppsx/ 
description: 在 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境中編輯或查看 PPSX 文件元數據的 C++ 示例代碼。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C++ 提取 PPSX 元數據" h2="構建您自己的 C++ 應用程序，以使用服務器端 API 從 PPSX 文件中添加、編輯、刪除或提取元數據。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 獲取 PPSX 元數據" %}}

 為了提取 PPSX 元數據，我們將使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp)
 API 是一個功能豐富、功能強大且易於使用的 C++ 平台文檔元數據提取 API。可以直接下載最新版本，直接打開
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 包管理器，搜索
 **Aspose.Slides.Cpp**
 並安裝。您還可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="通過 C++ 提取 PPSX 元數據的步驟" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="IDocumentProperties 類表示與演示文件關聯的文檔屬性。開發人員可以使用此屬性訪問元數據，如下所述。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載 PPSX 文件
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 get\_DocumentProperties() 獲取文檔屬性
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用循環迭代所有屬性
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
每次迭代打印屬性。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C++ 支持所有主要平台和操作系統。請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有適用於 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境的兼容操作系統。
- 項目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="提取 PPSX 的元數據 - C++" offSpacer="" %}}

```cs

const String templatePath = u"../templates/AccessModifyingProperties.ppsx";

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(templatePath);

// Create a reference to DocumentProperties object associated with Prsentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

for (int32_t i = 0; i get_CountOfCustomProperties(); i++){
	System::Console::WriteLine(u"Custom Property Name : {0}", documentProperties->GetCustomPropertyName(i));
	System::Console::WriteLine(u"Custom Property Vlaue : {0}", documentProperties->idx_get(documentProperties->GetCustomPropertyName(i)));
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Slides for C++ API" %}}

 Aspose.Slides API 可用於讀取、寫入、操作 Microsoft PowerPoint 文檔並將其轉換為 PDF、XPS、HTML、TIFF、ODP 和各種其他格式。可以從頭開始創建新文件並將其保存為相關支持的格式。 Aspose.Slides 是一個獨立的 API，用於創建、解析或操作演示文稿、幻燈片和元素，它不依賴於 Microsoft 或 OpenOffice 等任何軟件。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of PPSX via Online App" sectionDescription="View & edit Metadata to PPSX documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPSX file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" >}}
PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的元數據格式" subTitle="使用 C++，人們還可以操作許多其他格式的元數據，包括" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/odp/" name="ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/otp/" name="OTP" description="OpenDocument 標準格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pot/" name="POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/potm/" name="POTM" description="微軟 PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/potx/" name="POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pps/" name="PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppsm/" name="PPSM" description="啟用宏的幻燈片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/ppt/" name="PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pptm/" name="PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/metadata/pptx/" name="PPTX" description="打開 XML 表示格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}