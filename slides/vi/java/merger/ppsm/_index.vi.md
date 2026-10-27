---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Hợp nhất các tệp PPSM qua Java
weight: 3190
url: /vi/java/merger/ppsm/ 
description: Mã mẫu Java để kết hợp các tài liệu PPSM trên Môi trường thời gian chạy Java cho Ứng dụng JSP / JSF và Ứng dụng máy tính để bàn.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hợp nhất các định dạng PPSM trong Java" h2="Hợp nhất tài liệu PPSM gốc bằng cách sử dụng các API Java phía máy chủ."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cách hợp nhất các tệp PPSM bằng Java" %}}

Để hợp nhất tệp PPSM, chúng tôi sẽ sử dụng
 [Aspose.Slides dành cho Java](https://products.aspose.com/slides/vi/java/)
 API là một API hợp nhất giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Kho" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Sự phụ thuộc" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hợp nhất các tệp PPSM - Java" >}}
```cs
// Load first PPSM File
Presentation prest1 = new Presentation("prest1.ppsm");

// Load second PPSM File
Presentation prest2 = new Presentation("prest2.ppsm");

// Merge
for (ISlide slide : prest2.getSlides()) {
	// Merge from source to target
	prest1.getSlides().addClone(slide);
}

// Save the File
prest1.save("merged-presentation.ppsm", SaveFormat.Ppsm);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Các bước để hợp nhất tệp PPSM trong Java" intro="Việc hợp nhất và nối tài liệu cơ bản với API [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/) có thể được thực hiện chỉ với vài dòng mã." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tệp PPSM đầu tiên với một phiên bản của lớp Trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tải tài liệu PPSM thứ hai với một thể hiện của lớp Trình bày.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lặp qua từng trang chiếu của tệp PPSM thứ hai.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Với mỗi lần lặp, sử dụng addClone () để thêm các trang trình bày với tệp đầu tiên.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sử dụng phương thức save () để lưu tại đường dẫn được chỉ định{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="yêu cầu hệ thống" intro="Aspose.Slides cho Java hỗ trợ trên tất cả các nền tảng và Hệ điều hành chính. Vui lòng đảm bảo rằng bạn có các điều kiện tiên quyết sau." %}}

- Microsoft Windows hoặc hệ điều hành tương thích với Môi trường thời gian chạy Java cho Ứng dụng JSP / JSF và Ứng dụng máy tính để bàn.
- Nhận phiên bản mới nhất của Aspose.Slides cho Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Hợp nhất các tệp PDF trực tuyến"
  description="[Cách hợp nhất PDF trong Python](https://products.aspose.com/slides/vi/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

Các tệp có phần mở rộng `.PPSM` là tệp trình chiếu hỗ trợ macro, được tạo bằng Microsoft PowerPoint 2007 trở lên. Tệp `PPSM` mở dưới dạng trình chiếu và có thể chứa macro.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Các định dạng hợp nhất được hỗ trợ khác" subTitle="Sử dụng Java, Người ta cũng có thể hợp nhất nhiều định dạng tệp khác bao gồm .." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/odp/" name="ODP" description="Định dạng bản trình bày OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/otp/" name="OTP" description="Định dạng chuẩn OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/pot/" name="POT" description="Tệp mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/potm/" name="POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/potx/" name="POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/pps/" name="PPS" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/ppsx/" name="PPSX" description="Trình chiếu PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/pptm/" name="PPTM" description="Tệp trình bày hỗ trợ macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/vi/java/merger/pptx/" name="PPTX" description="Định dạng bản trình bày XML mở" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
