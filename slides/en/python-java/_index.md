---
title: Python PowerPoint API for PPT, PPTX, and ODP Presentations
weight: 5890
url: /python-java/
description: Aspose.Slides for Python via Java is a Python PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Python.
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Python PowerPoint API for Presentations" h2="Create, read, modify, and convert PowerPoint and OpenOffice presentations using Python without external software." logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-python-via-java-header.svg" pfName="Aspose.Slides" subTitlepfName="for Python via Java" downloadUrl="https://releases.aspose.com/slides/python-java/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via Java" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-python-via-java.svg" liveDemosLink="https://products.aspose.app/slides/family/" PricingLink="https://purchase.aspose.com/pricing/slides/python-java/" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/slides/python-java/" installationsDocsLink="https://docs.aspose.com/slides/python-java/installation/" nugetLink="" nugetPackageName="" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/slides/python-java/" >}}

{{% blocks/products/pf/feature-page-section %}}

<p><strong>Aspose.Slides for Python via Java</strong> is a Python library for creating, modifying, and converting PowerPoint presentations. It supports presentation elements such as slides, shapes, text, charts, tables, images, SmartArt, OLE objects, multimedia, and VBA macros. The API also supports merging, cloning, splitting, comparing, rendering, and printing presentations without Microsoft PowerPoint.</p>

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Why Choose Aspose.Slides for Python via Java?" %}}

Aspose.Slides for Python via Java offers several advantages for PowerPoint automation:

- **Cross-platform compatibility**: Use it on Windows, Linux, macOS, and other operating systems.
- **Easy integration and deployment**: Integrate it with existing applications and deploy it on servers or cloud environments without Microsoft Office.
- **Powerful features and functionality**: Create and modify slides, add and edit shapes, text, images, animations, transitions, charts, tables, and other elements, apply themes and layouts, insert audio and video, export and print presentations, export to video, and more.
- **High performance and quality**: Process presentations efficiently while preserving output fidelity and accuracy.
- **Free trial and licensing options**: Download the evaluation version and choose from licensing options such as developer, site, OEM, and cloud licenses.

{{% /blocks/products/pf/feature-page-section %}}

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray singleproduct">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">Advanced Python PowerPoint API Features</h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-copy ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Create or clone existing slides from templates</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-table ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Work with PowerPoint tables via API</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-shield ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Apply or remove shape protection</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-bar-chart ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Add Excel charts as OLE objects to slides</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-image ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Create shapes and add text to shapes on slides
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-align-left ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Handle text and shape formatting
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-database ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Generate presentations from a database</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-lock ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Protect presentations and generated PDFs</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-print ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Print presentations on a physical printer</p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">System Requirements</h2>
    Aspose.Slides for Python via Java is a platform-independent API. It can run on Windows, Linux, and macOS with the following software installed:
    <ul>
      <li>JDK 1.8 or above</li>
      <li>Python 3.7 or above</li>
      <li>JPype1 1.5.0 or above (JPype has been tested on Java versions from 1.8 to 11)</li>
    </ul>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">How to Install</h2>
    <p>Use PyPI to install the Aspose.Slides Python library for presentation processing from the <a href="https://pypi.org/project/aspose-slides-java/">PyPI repository</a>:</p>
    <pre>pip install aspose-slides-java</pre>
   </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Create New PowerPoint Presentation in Python</h2>
        <p>In the example given below, we have added a rectangle to the first slide of the presentation.</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat, ShapeType

presentation = Presentation()
slide = presentation.getSlides().get_Item(0)
slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 150, 300, 200)
presentation.save("presentation.pptx", SaveFormat.Pptx)
presentation.dispose()

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Merge Presentations in Python</h2>
        <p>This Python code shows you how to merge presentations:</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

dstPresentation = Presentation("presentation1.pptx")
srcPresentation = Presentation("presentation2.pptx")

for slideIndex in range(srcPresentation.getSlides().size()):
    slide = srcPresentation.getSlides().get_Item(slideIndex)
    dstPresentation.getSlides().addClone(slide)

dstPresentation.save("combined_presentation.pptx", SaveFormat.Pptx)
dstPresentation.dispose()
srcPresentation.dispose()

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Import a Presentation from PDF in Python</h2>
        <p>This Python code demonstrates the PDF to PowerPoint conversion process:</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

presentation = Presentation()

presentation.getSlides().removeAt(0)
presentation.getSlides().addFromPdf("welcome_to_powerpoint.pdf")

presentation.save("presentation.pptx", SaveFormat.Pptx)
presentation.dispose()

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to PDF in Python</h2>
        <p>This Python code shows how to convert a PowerPoint or OpenOffice presentation to PDF using the default options.</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

presentation = Presentation("presentation.pptx")

presentation.save("document.pdf", SaveFormat.Pdf)
presentation.dispose()

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to JPG in Python</h2>
        <p>The following example shows you how to convert a PowerPoint PPT, PPTX, and OpenOffice ODP document into a set of JPEG images.</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, ImageFormat

presentation = Presentation("presentation.pptx")

for slideIndex in range(presentation.getSlides().size()):
    slide = presentation.getSlides().get_Item(slideIndex)
    slideImage = slide.getImage(2, 2)
    slideImage.save("slide_" + str(slideIndex) + ".jpg", ImageFormat.Jpeg)
    slideImage.dispose()

presentation.dispose()

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/support-learning-resources >}}
    {{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
        {{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/slides/python-java/" >}}
        {{< blocks/products/pf/slr-element name="API References" href="https://docs.aspose.com/slides/python-java/api-reference/" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
        {{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/slides" >}}
        {{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
        {{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/slides/" >}}
        {{< blocks/products/pf/slr-element name="Release Notes" href="https://releases.aspose.com/slides/python-java/release-notes/" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Slides for Python via Java?" tabId="success-stories" >}}
        {{< blocks/products/pf/slr-element name="Customers List" href="https://about.aspose.com/customers/" >}}
        {{< blocks/products/pf/slr-element name="Success Stories" href="https://about.aspose.com/customers/success-stories/" >}}
    {{< /blocks/products/pf/slr-tab >}}
{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/slides/python-java/" pricingInformationLink="https://purchase.aspose.com/pricing/slides/python-java/" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Slides" description="Aspose.Slides is also available for other popular development environments, as listed below:" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sdkName=".NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sdkName="Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/cpp/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sdkName="C++" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/python-net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sdkName="Python via .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/android-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-android-java.svg" sdkName="Android via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/php-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sdkName="PHP via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-net/" imgSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-net.svg" sdkName="Node.js via .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-java/" imgSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-java.svg" sdkName="Node.js via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/sharepoint/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-sharepoint.svg" sdkName="SharePoint" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/reporting-services/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-reporting-services.svg" sdkName="Reporting Services" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/jasperreports/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-jasperreports.svg" sdkName="JasperReports" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
