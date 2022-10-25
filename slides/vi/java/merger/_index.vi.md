---
title: Hợp nhất PDF, PPT, PPTX và nhiều định dạng tệp khác bằng Java
url: /vi/java/merger/
keywords: Hợp nhất, Tham gia, PowerPoint, Bản trình bày, Java, Aspose
description: Hợp nhất nhiều tệp trong Java PPT, PPTX, ODP, PDF, PNG, JPG và nhiều tệp khác.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Hợp nhất Powerpoint, PDF, PPT hoặc các tài liệu khác với nhau bằng Java" h2="Thư viện Java tốc độ cao để hợp nhất PPT, PPTX, PDF, PNG, JPEG và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất PPT, PPTX, PDF bằng Java" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/vi/java/) là một thư viện Java mạnh mẽ để tạo và thao tác các tệp trình bày. Hơn nữa, nó cung cấp các cách linh hoạt để kết hợp nhiều bài thuyết trình PPT / PPTX. Khi bạn hợp nhất một bản trình bày với một bản trình bày khác, bạn đang kết hợp hiệu quả các trang trình bày của chúng trong một bản trình bày duy nhất để có được một tệp. Aspose.Slides cho phép bạn hợp nhất hai bản trình bày theo những cách khác nhau. Bạn có thể hợp nhất các bản trình bày với tất cả các hình dạng, phong cách, văn bản, định dạng, nhận xét, hoạt ảnh, v.v. của chúng mà không phải lo lắng về việc mất chất lượng hoặc dữ liệu.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các bản trình bày PowerPoint trong Java" %}}
Để hợp nhất các bản trình bày PowerPoint, bạn sẽ cần sao chép các trang chiếu từ bản trình bày này sang bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Hợp nhất các tệp PPTX bằng Java" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hợp nhất các bản trình bày với Slide Master bằng Java" %}}
Mã Java này trình bày cách hợp nhất một số bản trình bày thành một và áp dụng các kiểu từ mẫu bản trình bày chính của trang chiếu. Vì vậy, bản trình bày kết quả sẽ giữ nguyên định dạng nguồn và sẽ chứa định dạng từ trang chiếu chính của bản trình bày khác.

{{% blocks/products/pf/agp/code-block title="Hợp nhất nhiều PPT thành một trong Java" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách hợp nhất các bản trình bày bằng cách sử dụng Aspose.Slides cho Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để hợp nhất hai tệp PPTX và lưu kết quả dưới dạng PDF trong Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [** Aspose.Slides cho Java **](https://docs.aspose.com/slides/java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Java của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở các tệp PPTX nguồn bằng Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kết hợp các tệp PPTX bằng phương thức ** addClone **.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu bản trình bày và nhận kết quả dưới dạng tệp PDF duy nhất.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng được hỗ trợ khác để hợp nhất" subTitle="Bạn cũng có thể kết hợp các định dạng tệp khác. Xem các định dạng được hỗ trợ khác bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}