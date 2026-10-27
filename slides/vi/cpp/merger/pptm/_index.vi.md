---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Hợp nhất các tệp PPTM qua C ++
weight: 8630
url: /vi/cpp/merger/pptm/ 
description: Mã ví dụ C ++ để kết hợp các tài liệu PPTM trên Môi trường thời gian chạy C ++ cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hợp nhất các tệp PPTM bằng C ++" h2="Hợp nhất tài liệu PPTM bằng cách sử dụng API C ++ phía máy chủ."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách hợp nhất tệp PPTM bằng C ++" %}}

Để hợp nhất tệp PPTM, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho C ++](https://products.aspose.com/slides/vi/cpp/)
 API là một API hợp nhất tài liệu giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng C ++. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp, chỉ cần mở
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 quản lý gói, tìm kiếm
 ** Aspose.Slides.Cpp **
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Yêu cầu" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hợp nhất các tệp PPTM - C ++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.pptm";
const String sourceFilePath2 = u"SourceFile3.pptm";
const String outputFilePath = u"mergedOutput.pptm";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptm);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước để hợp nhất tệp PPTM trong C ++" intro="Việc hợp nhất và nối tài liệu cơ bản với API [Aspose.Slides for C ++](https://products.aspose.com/slides/vi/cpp/) có thể được thực hiện chỉ với vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải cả hai tệp PPTM.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sử dụng phương thức get \ _Slides () để lặp qua từng trang trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sử dụng chức năng AddClone để hợp nhất với tệp mong muốn.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sử dụng phương thức Save () để lưu tại đường dẫn được chỉ định{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Aspose.Slides for C ++ hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với C ++ Runtime Environment dành cho Windows 32 bit, Windows 64 bit và Linux 64 bit.
- Aspose.Slides cho C ++ DLL được tham chiếu trong dự án của bạn.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Hợp nhất các tệp PDF trực tuyến"
  description="[Cách hợp nhất PDF trong Python](https://products.aspose.com/slides/vi/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

Các tệp có phần mở rộng `.PPTM` là tệp bản trình bày hỗ trợ macro, được giới thiệu cùng Microsoft PowerPoint 2007. Chúng tương tự tệp PPTX, nhưng tệp PPTM có thể lưu mã macro VBA, còn tệp PPTX thì không. Tệp PPTM có thể được mở và chỉnh sửa trong Microsoft PowerPoint. Định dạng liên quan PPSM mặc định mở ở dạng xem Trình chiếu nhưng cũng có thể được mở trong PowerPoint để chỉnh sửa. Giống như tệp PPTX, tệp PPTM có thể chứa văn bản, hình ảnh, video, biểu đồ và nội dung trình bày khác.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng hợp nhất được hỗ trợ khác" subTitle="Sử dụng C ++, Người ta cũng có thể hợp nhất nhiều định dạng tệp khác bao gồm .." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/odp/" name="ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/otp/" name="OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/pot/" name="POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/potm/" name="POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/potx/" name="POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/pps/" name="PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/ppsm/" name="PPSM" description="Trình chiếu hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/ppsx/" name="PPSX" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/cpp/merger/pptx/" name="PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
