---
title: 通過 Java 編輯或查看 POTM 文件元數據
weight: 4240
url: /zh-hant/java/metadata/potm/ 
description: 用於在 JSP/JSF 應用程序和桌面應用程序的 Java 運行時環境中編輯或查看 POTM 格式元數據的 Java 示例代碼。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 提取 POTM 元數據" h2="構建您自己的 Java 應用程序，以使用服務器端 API 從 POTM 文件中添加、編輯、刪除或提取元數據。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTM" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 提取 POTM 元數據" %}}

 為了獲取 POTM 文件元數據，我們將使用
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API 是一個功能豐富、功能強大且易於使用的 Java 平台元數據 API。您可以直接從
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{% blocks/products/pf/agp/code-block title="存儲庫" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依賴" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="通過 Java 提取 POTM 元數據的步驟" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="IDocumentProperties 類表示與演示文件關聯的文檔屬性。開發人員可以使用此屬性訪問元數據，如下所述。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 getPresentationInfo() 獲取 POTM 信息
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
讀取所有屬性
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
設置新屬性
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用新屬性更新和寫入 POTM 信息
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java 支持所有主要平台和操作系統。請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或與 JSP/JSF 應用程序和桌面應用程序的 Java 運行時環境兼容的操作系統。
- 直接從 Java 獲取最新版本的 Aspose.Slides
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="提取 POTM 的元數據 - Java" offSpacer="" %}}

```cs

// read the info of presentation
IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("presentation.potm");

// obtain the current properties
IDocumentProperties props = info.readDocumentProperties();

// set the new values of Author and Title fields
props.setAuthor("New Author");
props.setTitle("New Title");

// update the presentation with a new values
info.updateDocumentProperties(props);
info.writeBindedPresentation("presentation.potm");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Slides for Java API" %}}

 Aspose.Slides API 可用於讀取、寫入、操作 Microsoft PowerPoint 文檔並將其轉換為 PDF、XPS、HTML、TIFF、ODP 和各種其他格式。可以從頭開始創建新文件並將其保存為相關支持的格式。 Aspose.Slides 是一個獨立的 API，用於創建、解析或操作演示文稿、幻燈片和元素，它不依賴於 Microsoft 或 OpenOffice 等任何軟件。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of POTM via Online App" sectionDescription="View & edit Metadata to POTM documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your POTM file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" >}}
Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. These settings can include styles, backgrounds, colour palette, fonts and defaults along with macros that consist of custom functions for doing particular task. They may also be opened by a previous version of PowerPoint with Open XML document support installed. POTM files can be opened in Microsoft PowerPoint for editing like any other PowerPoint file.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的元數據格式" subTitle="使用 Java，One 還可以操作許多其他格式的元數據，包括" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/odp/" name="ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/otp/" name="OTP" description="OpenDocument 標準格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pot/" name="POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/potx/" name="POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pps/" name="PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/ppsm/" name="PPSM" description="啟用宏的幻燈片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/ppsx/" name="PPSX" description="幻燈片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/ppt/" name="PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pptm/" name="PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pptx/" name="PPTX" description="打開 XML 表示格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}