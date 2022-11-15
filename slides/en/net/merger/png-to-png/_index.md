---
title:  Merge PNG Images in C#
url: /net/merge/png-to-png
keywords: Merge PNG, PNG to PNG, Join PNG, Combine PNG, C# API, .NET Library
description: Merge PNG to PNG in C#. Use .NET library API to combine PNG files
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PNG in C#" h2="Powerful cross-platform .NET API for merging PNG images using C# code on NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="Merge PNG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/) is a powerful .NET library used to merge and manipulate presentations, images, and other files. When you merge PNG to PNG, you are effectively combining two images to get one picture.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge PNG to PNG in C#" %}}
Using [**Aspose.Slides for .NET**](https://products.aspose.com/slides/net/), you can merge PNG files quickly with just a few lines of code

{{% blocks/products/pf/agp/code-block title="C# code for merging PNG to PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
            {
                IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
                pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

                IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
                pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

                pres.Slides[0].GetThumbnail(new Size(960, 720)).Save($"merged-image.png", ImageFormat.Png);
            }
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge PNG in C#" >}}


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
Load the PNG files you want to merge as picture frames.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting PNG image.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Merge other files" subTitle="You can also combine files in other formats to get a single file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/png-to-pdf/" name="PNG TO PDF" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/merge/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}