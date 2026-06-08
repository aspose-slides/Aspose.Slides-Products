---
title: Node.js via .NET PowerPoint API by Aspose.Slides
weight: 5890
url: /nodejs-net/
description: Aspose.Slides for Node.js via .NET is a Node.js PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Node.js.
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Node.js PowerPoint API for Presentations" h2="Create, read, modify, and convert PowerPoint and OpenOffice presentations using Node.js without external software." logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-net.svg" pfName="Aspose.Slides" subTitlepfName="for Node.js via .NET" downloadUrl="https://releases.aspose.com/slides/nodejs-net/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Node.js via .NET" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-net.svg" liveDemosLink="https://products.aspose.app/slides/family/" PricingLink="https://purchase.aspose.com/pricing/slides/nodejs-net/" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/slides/nodejs-net/" installationsDocsLink="https://docs.aspose.com/slides/nodejs-net/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Slides.NET6.CrossPlatform" nugetPackageName="Aspose.Slides.NET6.CrossPlatform" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/slides/nodejs-net/" >}}

{{% blocks/products/pf/feature-page-section %}}

<p><strong>Aspose.Slides for Node.js via .NET</strong> is a Node.js library for creating, modifying, and converting PowerPoint presentations. It supports presentation elements such as slides, shapes, text, charts, tables, images, SmartArt, OLE objects, multimedia, and VBA macros. The API also supports merging, cloning, splitting, comparing, rendering, and printing presentations without Microsoft PowerPoint.</p>

<p><strong>Aspose.Slides for Node.js via .NET</strong> provides these popular features:</p>
<ul>
    <li>Loading, opening, and viewing presentations.</li>
    <li>Editing presentations.</li>
    <li>Converting presentation files to popular presentation formats, such as PPT, PPTX, and ODP.</li>
    <li>Exporting presentations to PDF, JPG, HTML, GIF, SVG, and many other formats.</li>
    <li>Rendering and printing presentations.</li>
    <li>Encrypting and decrypting presentations; password-protecting presentations and removing passwords.</li>
    <li>Manipulating presentation entities, such as master slides, shapes, charts, picture frames, audio frames, video frames, OLE, VBA macros, animations, etc.</li>
    <li>Automatically translating presentations using AI-powered translation through external language model integration.</li>
</ul>

<p>Node.js is a popular, free, open-source, cross-platform JavaScript runtime environment that lets developers write command line tools and server-side scripts outside of a browser. For this reason, the <strong>Aspose.Slides</strong> team is proud to offer <strong>Aspose.Slides for Node.js via .NET</strong> to the Node.js community.</p>

{{% /blocks/products/pf/feature-page-section %}}

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray singleproduct">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">Advanced Node.js PowerPoint API Features</h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-copy ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Create slides or clone existing slides from templates</p>
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
    <ul>
      <li>Aspose.Slides for Node.js via .NET is a server-side JavaScript API based on Node.js. It can run on Windows, Linux, and macOS with .NET 6 or later.</li>
    </ul>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">How to Install</h2>
    <p>Use npm to install the Aspose.Slides Node.js library for presentation processing from the <a href="https://www.npmjs.com/package/aspose.slides.via.net">npm package repository</a>:</p>
    <pre><code>npm install aspose.slides.via.net</code></pre>
   </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Create a New PowerPoint Presentation in Node.js</h2>
        <p>In the example given below, we have added a rectangle to the first slide of the presentation.</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat, ShapeType } = asposeSlides;

let presentation = new Presentation();
try {
    const slide = presentation.slides.get(0);
    slide.shapes.addAutoShape(ShapeType.Rectangle, 50, 150, 300, 200);

    presentation.save("presentation.pptx", SaveFormat.Pptx);
}
finally {
    presentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Add/Remove/Clone Slides and Edit Shape Properties in Node.js</h2>
        <p>This Node.js code shows you how to edit various properties and clone slides:</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, BackgroundType, FillType } = asposeSlides;

let presentation = new Presentation();
let sourcePresentation = null;
try {
    // Add an empty slide to the presentation.
    let layoutSlide = presentation.layoutSlides.get(0);
    presentation.slides.addEmptySlide(layoutSlide);

    // Create another presentation and add its clone to the main presentation.
    sourcePresentation = new Presentation();
    presentation.slides.addClone(sourcePresentation.slides.get(0));

    // Access and modify properties of the first slide.
    const slide = presentation.slides.get(0);

    // Set the background of the first slide.
    slide.background.type = BackgroundType.OwnBackground;
    slide.background.fillFormat.fillType = FillType.Solid;
    slide.background.fillFormat.solidFillColor.color = "#AEC025F4";
}
finally {
    if(sourcePresentation != null) sourcePresentation.dispose();
    presentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to PDF in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint presentation to a PDF document.</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

let presentation = new Presentation("presentation.pptx");
try {
    presentation.save("presentation.pdf", SaveFormat.Pdf);
}
finally {
    presentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to GIF in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint presentation to a GIF image.</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

let presentation = new Presentation("presentation.pptx");
try {
    presentation.save("presentation.gif", SaveFormat.Gif);
}
finally {
    presentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to HTML in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint presentation to an HTML document.</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

let presentation = new Presentation("presentation.pptx");
try {
    presentation.save("presentation.html", SaveFormat.Html);
}
finally {
    presentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to ODP in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint presentation to an ODP document.</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

let presentation = new Presentation("presentation.pptx");
try {
    presentation.save("presentation.odp", SaveFormat.Odp);
}
finally {
    presentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Merge Presentations in Node.js</h2>
        <p>This Node.js code shows you how to merge presentations:</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

let dstPresentation = new Presentation("presentation1.pptx");
let srcPresentation = new Presentation("presentation2.pptx");
try {
    for (let slideIndex = 0; slideIndex < srcPresentation.slides.count; slideIndex++) {
        let slide = srcPresentation.slides.get(slideIndex);
        dstPresentation.slides.addClone(slide);
    }

    dstPresentation.save("combined_presentation.pptx", SaveFormat.Pptx);
}
finally {
    dstPresentation.dispose();
    srcPresentation.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Retrieve Various Properties of a PowerPoint Presentation</h2>
        <p>The following example shows you how to retrieve various properties of a PowerPoint presentation.</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation } = asposeSlides;

let presentation = new Presentation("presentation.pptx");
try {
    // Retrieve various properties of the presentation.
    const countSlides = presentation.slides.count;
    const countMastersSlides = presentation.masters.count;
    const countLayoutSlides = presentation.layoutSlides.count;
    const firstSlideNumber = presentation.firstSlideNumber;
    const lastView = presentation.viewProperties.lastView;
    const masterThemeName = presentation.masterTheme.name;
    const sourceFormat = presentation.sourceFormat;
    const countVideos = presentation.videos.count;
    const countImages = presentation.images.count;

    // Log presentation properties to the console.
    console.log("countSlides:" + countSlides);
    console.log("countMastersSlides:" + countMastersSlides);
    console.log("countLayoutSlides:" + countLayoutSlides);
    console.log("firstSlideNumber:" + firstSlideNumber);
    console.log("lastView=" + lastView);
    console.log("masterThemeName:" + masterThemeName);
    console.log("sourceFormat:" + sourceFormat);
    console.log("countVideos:" + countVideos);
    console.log("countImages:" + countImages);
}
finally {
    presentation.dispose();
}
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
        {{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/slides/nodejs-net/" >}}
        {{< blocks/products/pf/slr-element name="API References" href="https://docs.aspose.com/slides/nodejs-net/api-reference/" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
        {{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/slides" >}}
        {{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
        {{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/slides/" >}}
        {{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/slides/nodejs-net/release-notes/" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Slides for Node.js via .NET?" tabId="success-stories" >}}
        {{< blocks/products/pf/slr-element name="Customers List" href="https://about.aspose.com/customers/" >}}
        {{< blocks/products/pf/slr-element name="Success Stories" href="https://about.aspose.com/customers/success-stories/" >}}
    {{< /blocks/products/pf/slr-tab >}}
{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/slides/nodejs-net/" pricingInformationLink="https://purchase.aspose.com/pricing/slides/nodejs-net/" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Slides" description="Aspose.Slides is also available for other popular development environments, as listed below:" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sdkName=".NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sdkName="Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/cpp/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sdkName="C++" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/python-net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sdkName="Python via .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/python-java/" imgSrc="https://products.aspose.com/slides/images/aspose_slides-for-python-via-java.svg" sdkName="Python via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/android-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-android-java.svg" sdkName="Android via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-net/" imgSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-net.svg" sdkName="Node.js via .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-java/" imgSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-java.svg" sdkName="Node.js via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/php-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sdkName="PHP via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/sharepoint/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-sharepoint.svg" sdkName="SharePoint" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/reporting-services/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-reporting-services.svg" sdkName="Reporting Services" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/jasperreports/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-jasperreports.svg" sdkName="JasperReports" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

