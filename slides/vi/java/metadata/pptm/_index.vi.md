---
title: Xem hoặc chỉnh sửa siêu dữ liệu tệp PPTM bằng Java
url: /vi/java/metadata/pptm/
keywords: Chỉnh sửa siêu dữ liệu PPTM, Xem siêu dữ liệu PPTM, Chỉnh sửa thuộc tính PPTM, Xem thuộc tính PPTM
description: mã nguồn Java để chỉnh sửa hoặc xem siêu dữ liệu định dạng PPTM.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Chỉnh sửa thuộc tính PPTM bằng Java" h2="Xây dựng các ứng dụng Java của riêng bạn để sửa đổi các thuộc tính Tích hợp và Tùy chỉnh trong tệp bản trình bày bằng cách sử dụng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTM" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Sửa đổi Thuộc tính PPTM qua Java" %}}
Khi sử dụng Aspose.Slides for Java, nhà phát triển có thể truy cập và sửa đổi giá trị của thuộc tính tích hợp cũng như thuộc tính tùy chỉnh. Nhà phát triển có thể sử dụng thuộc tính [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) do đối tượng Bản trình bày hiển thị để truy cập các thuộc tính tài liệu của tệp bản trình bày.
{{% blocks/products/pf/agp/code-block title="Sửa đổi Thuộc tính tích hợp PPTM - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.pptm");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.pptm", SaveFormat.Pptm);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Thêm thuộc tính tùy chỉnh vào PPTM - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.pptm", SaveFormat.Pptm);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách trích xuất siêu dữ liệu của PPTM qua Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Trích xuất siêu dữ liệu từ tệp PPTM." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Khởi tạo lớp Trình bày với đường dẫn đến tệp PPTM
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nhận đối tượng DocumentProperties được liên kết với Bản trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lặp lại các mục trong đối tượng DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Truy cập và sửa đổi thuộc tính tùy chỉnh
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng siêu dữ liệu được hỗ trợ khác" subTitle="Sử dụng Java, Bạn cũng có thể thao tác với siêu dữ liệu của nhiều định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}