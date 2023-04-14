---
title: Chuyển đổi HTML sang PPTX trong Java
url: /vi/java/conversion/html-to-pptx/
keywords: Chuyển đổi HTML sang PPTX, HTML sang PPTX, PowerPoint, HTML, PPTX, API Java, Thư viện Java
description: Chuyển đổi HTML sang PPTX trong Java. Sử dụng API thư viện Java để chuyển HTML sang PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Chuyển đổi HTML sang PPTX trong Java" h2="API Java đa nền tảng mạnh mẽ để chuyển đổi HTML sang PPTX bằng mã Java" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi HTML sang PPTX bằng Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/) là một thư viện Java mạnh mẽ được sử dụng để tạo, chuyển đổi và thao tác các bản trình bày PowerPoint, PDF, tài liệu HTML và các tài liệu khác các tập tin. Khi bạn chuyển đổi HTML sang PPTX, về cơ bản, bạn đang di chuyển nội dung trong tài liệu HTML sang các trang chiếu trong bản trình bày PowerPoint.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi HTML sang PPTX trong Java" %}}
Sử dụng [**Aspose.Slides for Java**](https://products.aspose.com/slides/vi/java/), bạn có thể chuyển đổi tài liệu HTML sang bản trình bày PowerPoint chỉ bằng một vài dòng mã:

{{% blocks/products/pf/agp/code-block title="Mã Java để chuyển đổi HTML sang PPTX" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.pptx", SaveFormat.Pptx);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cách chuyển đổi HTML sang PPTX trong Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt **Aspose.Slides cho Java**. Xem [**Cài đặt**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm thư viện làm tài liệu tham khảo trong dự án của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tạo một thể hiện của lớp Trình bày.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải tài liệu HTML mà bạn muốn chuyển đổi sang PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu tệp kết quả dưới dạng bản trình bày PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Chuyển đổi trực tuyến miễn phí" sectionDescription="[Cách chuyển đổi PPT sang HTML bằng Python](https://products.aspose.com/slides/vi/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PowerPoint được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi các tệp ở các định dạng khác sang PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}