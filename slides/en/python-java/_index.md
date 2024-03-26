---
title: Python PowerPoint API by Aspose.Slides
weight: 5890
url: /python-java/ 
description: Aspose.Slides for Python via Java is a Python PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Python. 
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Python PowerPoint API for Presentations" h2="Create, Read, Modify and Convert PowerPoint and OpenOffice presentations using Python without any external software." logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-python-via-java-header.svg" pfName="Aspose.Slides" subTitlepfName="for Python via Java" downloadUrl="https://releases.aspose.com/slides/python-java/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via Java" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-python-via-java.svg" liveDemosLink="https://products.aspose.app/slides/family/" PricingLink="https://purchase.aspose.com/pricing/slides/python-java/" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/slides/python-java/" installationsDocsLink="https://docs.aspose.com/slides/python-java/installation/" nugetLink="" nugetPackageName="" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/slides/python-java/" >}}

{{% blocks/products/pf/feature-page-section %}}

<p><strong>Aspose.Slides for Python via Java</strong> is a Python library that lets you create, modify, and convert PowerPoint presentations in Python. It supports all presentation elements such as slides, shapes, text, charts, tables, images, and more. It also offers many advanced features such as merging, cloning, splitting, comparing, and printing presentations. It works without any dependencies and can process thousands of presentations in a short time.</p>

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Why Choose Aspose.Slides for Python via Java?" %}}

Aspose.Slides for Python via Java offers many advantages over other solutions for PowerPoint automation, such as:

- **Cross-platform compatibility**: Aspose.Slides for Python via Java supports multiple platforms. You can use Aspose.Slides for Python via Java on Windows, Linux, macOS, and other operating systems.
- **Easy integration and deployment**: Aspose.Slides for Python via Java is a standalone library that does not require Microsoft Office or any other software to be installed on your system. You can easily integrate Aspose.Slides for Python via Java with your existing applications and deploy it on any server or cloud environment.
- **Powerful features and functionality**: Aspose.Slides for Python via Java provides a rich set of features and functionality for working with PowerPoint presentations, such as creating and modifying slides, adding and editing shapes, text, images, animations, transitions, charts, tables, and other elements, applying themes and layouts, inserting audio and video, exporting and printing presentations, export to video, and much more.
- **High performance and quality**:  Aspose.Slides for Python via Java delivers high performance and quality results for processing PowerPoint presentations. You can process thousands of presentations in minutes, without compromising the fidelity and accuracy of the output.
- **Free trial and licensing options**: Aspose.Slides for Python via Java offers a free trial version that you can download and use for 30 days, without any limitations. You can also choose from various licensing options that suit your needs and budget, such as developer, site, OEM, and cloud licenses.

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
    <p class="col-lg-10">Apply or remove the protection on shapes</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-bar-chart ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Add Excel charts as OleObjects to slides</p>
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
     Handle text &amp; shape formatting
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-database ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Generate presentations from database</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-lock ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Protect presentations &amp; resultant PDF</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-print ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Print presentations on a physical printer</p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">System Requirements</h2>
    Aspose.Slides for Python via Java is platform-independent API. It can run on Windows, Unix/Linux & Mac platforms with the following software installed: 
    <ul>
      <li>JDK 1.8 or above</li>
      <li>Python 3.7 or above</li>
      <li>JPype1 1.5.0 or above (JPype has been tested on Java versions from 1.8 to 11)</li>
    </ul>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">How to Install</h2>
    <p>Use <strong>PyPI</strong> to install our Python library for Presentation processing from the <a href="https://pypi.org/project/aspose-slides-java/">PyPI repository:</a></p>
    <pre><code>pip install aspose-slides-java</code></pre>
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

pres = Presentation()
slide = pres.getSlides().get_Item(0)
slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 150, 300, 200)
pres.save("NewPresentation.pptx", SaveFormat.Pptx)

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

pres1 = Presentation("pres1.pptx");
pres2 = Presentation("pres2.pptx");

for i in range(pres2.getSlides().size()):
    pres1.getSlides().addClone(pres2.getSlides().get_Item(i));

pres1.save("combinedPresentation.pptx", SaveFormat.Pptx);

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Import Presentation From PDF in Python. Convert PDF to PPT, Convert PDF to PPTX, Convert PDF to ODP</h2>
        <p>This Python code demonstrates the PDF to PowerPoint conversion process:</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

pres.save("outputPresentation.pptx", SaveFormat.Pptx);

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to PDF in Python</h2>
        <p>This Python code shows you how to convert a PowerPoint PPT, PPTX, and OpenOffice ODP document to a PDF document using the default options. The resulting file is a PDF document at the maximum quality levels</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat

pres = Presentation("PowerPoint.pptx");

pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf);

jpype.shutdownJVM()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to JPG in Python. Convert PPT to JPG, Convert PPTX to JPG, Convert ODP to JPG</h2>
        <p>The following example shows you how to convert a PowerPoint PPT, PPTX, and OpenOffice ODP document into a set of JPEG images.</p>
        <pre>
            <code class="python">
import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("pres.pptx");

format_name = "PNG"

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, format_name, File("image_java" + str(i) + ".png"))

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
        {{< blocks/products/pf/slr-element name="Documentation" href="https://releases.aspose.com/slides/python-java/" >}}
        {{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-slides/" >}}
        {{< blocks/products/pf/slr-element name="API References" href="https://releases.aspose.com/slides/python-java/api-reference/" >}}
        {{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
        {{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/slides" >}}
        {{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
        {{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/slides/" >}}
        {{< blocks/products/pf/slr-element name="Release Notes" href="https://releases.aspose.com/slides/python-java/release-notes/" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Slides for Python via Java?" tabId="success-stories" >}}
        {{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
        {{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/aspose-slides" >}}
    {{< /blocks/products/pf/slr-tab >}}
{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/slides/python-java" pricingInformationLink="https://purchase.aspose.com/pricing/slides/python-java" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Slides" description="Aspose.Slides offers individual PowerPoint APIs for other popular development environments as listed below:" >}}
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

