---
lastmod: 2026-07-22
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python PowerPoint API for PPT, PPTX, and ODP Presentations
weight: 5890
url: /python-java/
description: Aspose.Slides for Python via Java is a Python PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Python.
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Python PowerPoint API for Presentations" h2="Create, read, modify, and convert PowerPoint and OpenDocument presentations in Python without Microsoft PowerPoint." logoImageSrc="/slides/images/aspose_slides-for-python-via-java-header.svg" pfName="Aspose.Slides" subTitlepfName="for Python via Java" downloadUrl="https://releases.aspose.com/slides/python-java/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via Java" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="/slides/images/aspose_slides-for-python-via-java.svg" liveDemosLink="https://products.aspose.app/slides/family/" PricingLink="https://purchase.aspose.com/pricing/slides/python-java/" buyLink="https://purchase.aspose.com/pricing/slides/python-java/" docsLink="https://docs.aspose.com/slides/python-java/" installationsDocsLink="https://docs.aspose.com/slides/python-java/installation/" nugetLink="" nugetPackageName="" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/slides/python-java/" >}}

{{% blocks/products/pf/feature-page-section %}}

<p><strong>Aspose.Slides for Python via Java</strong> is a Python library for creating, modifying, rendering, and converting PowerPoint and OpenDocument presentations. It supports slides, shapes, text, charts, tables, images, SmartArt, OLE objects, audio, video, animations, transitions, and VBA macros. The API can also merge, clone, split, compare, and print presentations without Microsoft PowerPoint.</p>

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Why Choose Aspose.Slides for Python via Java?" %}}

Aspose.Slides for Python via Java offers several advantages for PowerPoint automation:

- **Cross-platform compatibility**: Use it on Windows, Linux, macOS, and other operating systems.
- **Easy integration and deployment**: Integrate it with existing applications and deploy it on servers or cloud environments without Microsoft Office.
- **Comprehensive presentation processing**: Create and modify slides; work with shapes, text, images, animations, transitions, charts, and tables; apply themes and layouts; insert audio and video; and export or print presentations.
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
    Aspose.Slides for Python via Java can run on Windows, Linux, and macOS when the following software is installed:
    <ul>
      <li>JRE 8 or later</li>
      <li>Python 3.7 through 3.12</li>
      <li><code>JPype1</code> 1.5.0 or later</li>
    </ul>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">How to Install</h2>
    <p>Install Aspose.Slides for Python via Java from its <a href="https://pypi.org/project/aspose-slides-java/">PyPI package page</a>:</p>
    <pre>pip install aspose-slides-java</pre>
   </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Create New PowerPoint Presentation in Python</h2>
        <p>The following example accesses the first slide through a variable, adds a rectangle with <code>addAutoShape</code>, and saves the presentation as PPTX.</p>
        <pre>
            <code class="python">
presentation = Presentation()
try:
    slide = presentation.getSlides().get_Item(0)
    slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 150, 300, 200)
    presentation.save("presentation.pptx", SaveFormat.Pptx)
finally:
    presentation.dispose()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Merge Presentations in Python</h2>
        <p>This example uses <code>addClone</code> to copy every slide from a source presentation to a destination presentation.</p>
        <pre>
            <code class="python">
destination_presentation = Presentation("presentation1.pptx")
try:
    source_presentation = Presentation("presentation2.pptx")
    try:
        slide_count = source_presentation.getSlides().size()

        for slide_index in range(slide_count):
            slide = source_presentation.getSlides().get_Item(slide_index)
            destination_presentation.getSlides().addClone(slide)

        destination_presentation.save("combined-presentation.pptx", SaveFormat.Pptx)
    finally:
        source_presentation.dispose()
finally:
    destination_presentation.dispose()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Import a Presentation from PDF in Python</h2>
        <p>This example removes the default blank slide, calls <code>addFromPdf</code>, and saves the imported pages as a PPTX presentation.</p>
        <pre>
            <code class="python">
presentation = Presentation()
try:
    presentation.getSlides().removeAt(0)
    presentation.getSlides().addFromPdf("document.pdf")
    presentation.save("presentation.pptx", SaveFormat.Pptx)
finally:
    presentation.dispose()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to PDF in Python</h2>
        <p>This example calls <code>save</code> with <code>SaveFormat.Pdf</code> to convert a PowerPoint or OpenDocument presentation to PDF using the default options.</p>
        <pre>
            <code class="python">
presentation = Presentation("presentation.pptx")
try:
    presentation.save("document.pdf", SaveFormat.Pdf)
finally:
    presentation.dispose()
            </code>
        </pre>
    </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to JPG in Python</h2>
        <p>The following example calls <code>getImage</code> for each slide and saves the rendered images with <code>ImageFormat.Jpeg</code>.</p>
        <pre>
            <code class="python">
presentation = Presentation("presentation.pptx")
try:
    slide_count = presentation.getSlides().size()

    for slide_index in range(slide_count):
        slide = presentation.getSlides().get_Item(slide_index)
        slide_image = slide.getImage(2, 2)
        try:
            file_path = f"slide-{slide_index + 1}.jpg"
            slide_image.save(file_path, ImageFormat.Jpeg)
        finally:
            slide_image.dispose()
finally:
    presentation.dispose()
            </code>
        </pre>
    </div>
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< blocks/products/pf/agp/faq imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/headers/aspose_slides-brand.svg" >}}
{{< blocks/products/pf/agp/faq-item question="What has to be installed before `pip install aspose-slides-java` will work?" answer="A JRE 8 or later, Python 3.7 through 3.12, and `JPype1` 1.5.0 or later. The library talks to a Java runtime through JPype, so the JRE is a hard requirement." >}}
{{< blocks/products/pf/agp/faq-item question="How is this different from Aspose.Slides for Python via .NET?" answer="Same capabilities, different bridge. This build calls into Java and needs a JRE; the [Python via .NET build](/slides/python-net/) carries its own runtime and needs nothing else installed. Choose this one if a JVM is already part of your environment." >}}
{{< blocks/products/pf/agp/faq-item question="Why do the methods look like `getSlides()` and `get_Item(0)`?" answer="Because the API is the Java one surfaced through JPype, so it keeps Java naming. Code written against the Python via .NET build will not run here unchanged." >}}
{{< blocks/products/pf/agp/faq-item question="Do I need to release the presentation explicitly?" answer="Yes. Call `presentation.dispose()` in a `finally` block, as the sample on this page does — the underlying Java object is not freed by Python's garbage collector on its own." >}}
{{< /blocks/products/pf/agp/faq >}}

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
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-net/" imgSrc="/slides/images/aspose_slides-for-nodejs-via-net.svg" sdkName="Node.js via .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-java/" imgSrc="/slides/images/aspose_slides-for-nodejs-via-java.svg" sdkName="Node.js via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/sharepoint/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-sharepoint.svg" sdkName="SharePoint" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/reporting-services/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-reporting-services.svg" sdkName="Reporting Services" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/jasperreports/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-jasperreports.svg" sdkName="JasperReports" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
