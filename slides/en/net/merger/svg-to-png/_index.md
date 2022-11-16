---
title:  Merge SVG to PNG in C#
url: /net/merger/svg-to-png
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, C# API, .NET Library
description: Merge SVG to PNG in C#. Use .NET library API to combine SVG and PNG files
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge SVG to PNG in C#" h2="Powerful cross-platform .NET API for merging SVG to PNG images using C# code on NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="Merge SVG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/) is a powerful .NET library used to merge and manipulate presentations, images, and other files. When you merge SVG to PNG, you are effectively combining SVG images to get a PNG picture.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge SVG to PNG in C#" %}}
Using [**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/), you can merge SVG to PNG files quickly with just a few lines of code

{{% blocks/products/pf/agp/code-block title="C# code for merging SVG to PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
            {
                ISvgImage svgImage = new SvgImage("doc.svg");
                IPPImage image = pres.Images.AddImage(svgImage);
                pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

                ISvgImage svgImage2 = new SvgImage("doc.svg");
                IPPImage image2 = pres.Images.AddImage(svgImage);
                pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

                pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
            }
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge SVG to PNG in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for .NET**. See [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the Presentation class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the SVG files you want to merge together.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting PNG image.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}