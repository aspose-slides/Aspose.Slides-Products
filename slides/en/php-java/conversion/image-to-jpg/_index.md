---
lastmod: 2026-09-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to JPG in PHP
url: /php-java/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, PHP API, PHP Library, Image, JPG
description: Convert an image to JPG in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to JPG in PHP" h2="Load an image and save it in JPEG format with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to JPG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can load an image file and save it in JPEG format, keeping the image's width and height.

The image API uses `Images::fromFile` to load the source image, `save` to write it, and `ImageFormat::Jpeg` to select JPEG output.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Image to JPG using PHP" %}}
To convert an image to JPG, load it with `Images::fromFile`, save it with `ImageFormat::Jpeg`, and dispose of it when you are done.

{{% blocks/products/pf/agp/code-block title="PHP code for converting Image into JPG" offSpacer="true" %}}

```php
$image = Images::fromFile("input.png");
try {
    $image->save("output.jpg", ImageFormat::Jpeg);
} finally {
    $image->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert Image to JPG using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert Image to JPG in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source image with `Images::fromFile`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the image with `save` and `ImageFormat::Jpeg`, then call `dispose` to release it.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert Image To Other Supported Formats" subTitle="You can also convert Image and save to other file formats. See all supported formats below:" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
