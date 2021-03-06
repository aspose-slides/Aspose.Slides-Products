---
title: Chuyển đổi PPT sang HTML trong PHP
weight: 2140
url: /vi/php-java/conversion/ppt-to-html/ 
keywords: "Convert, PowerPoint, PPT, HTML, Presentation, PHP"
description: Mã mẫu cho chuyển đổi PHP từ PPT sang HTML. Sử dụng PowerPoint PHP API để chuyển đổi hàng loạt tệp PPT sang tệp HTML.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi PPT sang HTML trong PHP" h2="Thư viện PHP PowerPoint mạnh mẽ để chuyển đổi PPT sang HTML" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Chuyển đổi PPT sang HTML trong PHP" %}}

Bạn cần chuyển đổi tệp PPT thành HTML theo cách lập trình? Sử dụng [* Aspose.Slides cho PHP qua Java *](https://products.aspose.com/slides/vi/php-java/), bất kỳ nhà phát triển nào cũng có thể chuyển đổi định dạng PPT sang HTML chỉ với một vài dòng mã PHP .

Là một API xử lý bản trình bày hiện đại, Aspose.Slides for PHP tạo HTML từ PPT một cách nhanh chóng. Kiểm tra chất lượng của chuyển đổi PPT sang HTML ngay trong [browser] của bạn (https://products.aspose.app/slides/conversion). Thư viện Aspose PowerPoint PPTX cho phép bạn chuyển đổi tệp PPT sang nhiều định dạng phổ biến.

Bạn có thể cài đặt thư viện từ [Composer](https://packagist.org/packages/aspose/slides) bằng lệnh sau:

{{% blocks/products/pf/agp/code-block title="Bảng điều khiển / Thiết bị đầu cuối" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi PPT sang HTML trong PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Đây là các bước để chuyển đổi tệp PPT thành HTML bằng PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tải tệp PPT bằng một phiên bản của lớp Trình bày
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat. {To_format} làm tham số
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tệp PPT sẽ được lưu tại đường dẫn được chỉ định
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã nguồn mẫu chuyển đổi PHP, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

1. Cài đặt PHP 7, thêm đường dẫn đến PHP vào biến hệ thống `PATH` và đặt` allow_url_include` thành `On` trong tệp` php.ini`.
1. Cài đặt JRE 8. Đặt biến môi trường `JAVA_HOME` làm đường dẫn đến vị trí JRE đã cài đặt.
1. Cài đặt Apache Tomcat 8.0 (xem [thêm](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị Chuyển đổi PHP từ PPT sang HTML" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.html", SaveFormat::Html5);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Lưu PPT dưới dạng HTML trong PHP" %}}
Sử dụng ứng dụng miễn phí để xem trình diễn về quá trình chuyển đổi PPT sang HTML. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPT to HTML" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPT sang nhiều định dạng tệp khác. Xem các chuyển đổi được hỗ trợ khác bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Hình ảnh bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Bản trình bày XML phẳng OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="Định dạng trao đổi đồ họa" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Hình ảnh JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="Định dạng bản trình bày OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="Định dạng chuẩn OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Định dạng tài liệu di động" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-png/" name="PPT TO PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="Tệp mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="Tệp Mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="Bản trình bày mẫu Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Trình chiếu hỗ trợ macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Trình chiếu PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Tệp trình bày hỗ trợ macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Định dạng bản trình bày XML mở" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="Đồ họa vector có thể mở rộng" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-swf/" name="PPT TO SWF" description="Định dạng SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="Thông số kỹ thuật giấy XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}