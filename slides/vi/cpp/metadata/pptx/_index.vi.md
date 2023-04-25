---
title: Xem hoặc chỉnh sửa siêu dữ liệu tệp PPTX bằng C++
url: /vi/cpp/metadata/pptx/
keywords: Chỉnh sửa siêu dữ liệu PPTX, Xem siêu dữ liệu PPTX, Chỉnh sửa thuộc tính PPTX, Xem thuộc tính PPTX
description: mã nguồn C++ để chỉnh sửa hoặc xem siêu dữ liệu định dạng PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Chỉnh sửa thuộc tính PPTX bằng C++" h2="Xây dựng các ứng dụng C++ của riêng bạn để sửa đổi các thuộc tính Tích hợp và Tùy chỉnh trong tệp bản trình bày bằng cách sử dụng API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Sửa đổi Thuộc tính PPTX qua C++" %}}
Khi sử dụng Aspose.Slides for C++, nhà phát triển có thể truy cập và sửa đổi giá trị của thuộc tính tích hợp cũng như thuộc tính tùy chỉnh. Nhà phát triển có thể sử dụng thuộc tính [DocumentProperties](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) do đối tượng Bản trình bày hiển thị để truy cập các thuộc tính tài liệu của tệp bản trình bày.
{{% blocks/products/pf/agp/code-block title="Sửa đổi Thuộc tính tích hợp PPTX - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class that represents the Presentation
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"presentation.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

// Set the builtin properties
documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Thêm thuộc tính tùy chỉnh vào PPTX - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class
auto presentation = System::MakeObject<Presentation>();

// Getting Document Properties
auto documentProperties = presentation->get_DocumentProperties();

// Adding Custom properties
documentProperties->idx_set(u"New Custom", ObjectExt::Box<int32_t>(12));
documentProperties->idx_set(u"My Name", ObjectExt::Box<String>(u"Aspose Metadata Editor"));
documentProperties->idx_set(u"Custom", ObjectExt::Box<int32_t>(124));

// Getting property name at particular index
String getPropertyName = documentProperties->GetCustomPropertyName(2);

// Removing selected property
documentProperties->RemoveCustomProperty(getPropertyName);

// Saving presentation
presentation->Save(u"CustomDocumentProperties_out.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cách trích xuất siêu dữ liệu của PPTX qua C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để Trích xuất siêu dữ liệu từ tệp PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Khởi tạo lớp Trình bày với đường dẫn đến tệp PPTX
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

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng siêu dữ liệu được hỗ trợ khác" subTitle="Sử dụng C++, Bạn cũng có thể thao tác với siêu dữ liệu của nhiều định dạng khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/cpp/metadata/pptm/" name="PPTM" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}