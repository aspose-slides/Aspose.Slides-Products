---
title: Protect and lock PPT document via C++ 
weight: 2570
url: /cpp/protect/ppt/ 
description: C++ example code to lock PPT file using password on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Encrypt PPT Files via C++" h2="Password-protect PowerPoint presentations including PPT format using .NET Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Secure PPT File Using C++" %}}

 In order to protect PPT file, we’ll use
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp) 
 API which is a feature-rich, powerful and easy to use document encryption API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.slides) 
 package manager, search for
 **Aspose.Slides.Cpp** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Slides" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Steps to Protect PPT Files via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Document protection using Aspose.Slides APIs can be done with just few lines of code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPT File
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Set Password using get\_ProtectionManager()->Encrypt(.) method
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save protected PPT presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Slides for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.ppt";
const String outputFilePath = u"OutputPath\OutPutFile.ppt";

// Load the PPT file
SharedPtr<Presentation> pptFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
pptFile->get_ProtectionManager()->Encrypt(u"password");

// Save the PPT
pptFile->Save(outputFilePath, SaveFormat::Ppt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.Slides for C++ API" %}}

 Aspose.Slides API can be used to read, write, manipulate and convert Microsoft PowerPoint documents to PDF, XPS, HTML, TIFF, ODP and various other formats. One can create new files from scratch and save those in the relevant supported formats. Aspose.Slides is a standalone API for creating, parsing or manipulating presentations, slides and elements and it does not depend on any software like Microsoft or OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect PPT" sectionDescription="Check our live demos to [encrypt PPT files](https://products.aspose.app/slides/protect/ppt) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPT file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PPT file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protection Documents" subTitle="Using C++, one can protect other files including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/protect/odp/" name="ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/protect/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}