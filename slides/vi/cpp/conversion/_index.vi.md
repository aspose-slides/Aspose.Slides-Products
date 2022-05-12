---
title: Chuyển đổi bản trình bày Microsoft PowerPoint sang các định dạng khác nhau bằng C ++
url: /vi/cpp/conversion/
description: Chuyển đổi Microsoft PowerPoint Slides sang nhiều tệp bao gồm định dạng HTML, PDF và hình ảnh trong các ứng dụng dựa trên C ++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> Chuyển đổi bản trình bày PowerPoint qua C ++" h2="Mã ví dụ C ++ cho các tình huống chuyển đổi khác nhau để chuyển đổi các trang trình bày sang Hình ảnh, HTML, PDF và các định dạng khác." >}}

{{% blocks/products/pf/feature-page-summary %}}

Quá trình chuyển đổi các định dạng Microsoft <sup> ® </sup> PowerPoint rất đơn giản và dễ dàng để tự động hóa các quy trình bằng cách sử dụng thư viện C ++ PowerPoint. Các nhà phát triển có thể nâng cao mã nguồn có liên quan và tích hợp nó trong các ứng dụng của họ. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi giữa các định dạng Microsoft PowerPoint" %}}
Chuyển đổi giữa các tài liệu Microsoft <sup> ® </sup> PowerPoint bao gồm PPT, PPTX theo chương trình chỉ là một đoạn mã hai dòng. Tải tệp bằng [Lớp trình bày](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) và gọi [Phương thức lưu](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) có tệp đầu ra và SaveFormat.OutputFormats làm tham số.

{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi C ++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PowerPoint sang PDF" %}}

Chuyển đổi Microsoft <sup> ® </sup> PowerPoint sang PDF là một kịch bản phổ biến do việc chia sẻ rất nhiều tài liệu PDF. Lập trình viên có thể tự động hóa nó và đặt cài đặt chuyển đổi PDF có liên quan bằng [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Một số cài đặt cụ thể như mức nén văn bản, chất lượng JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), mức tuân thủ PDF [Tuân thủ](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), chuyển đổi trang trình bày ẩn [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), các trang trình bày được chọn và tạo [Mật khẩu] bị khóa (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc39a195) các tệp PDF được bảo vệ .

{{% blocks/products/pf/feature-page-code h3="Mã chuyển đổi C ++ PowerPoint sang PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Lưu các trang trình bày Microsoft PowerPoint dưới dạng hình ảnh" %}}
Khi nào có trường hợp hiển thị nội dung trình chiếu trên web thì cần phải kết xuất các tập tin dưới dạng HTML hoặc hình ảnh JPG, TIFF, PNG,… Quá trình chuyển đổi slide thành hình ảnh rất đơn giản. Tải tất cả các trang trình bày bằng [get_Slides ()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) và lặp lại từng trang một. Trong mỗi lần lặp, hãy sử dụng [ISlide-> GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) cho hình ảnh trang trình bày và sau đó lưu vào định dạng hình ảnh yêu cầu. 

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi PowerPoint sang hình ảnh trong C ++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}