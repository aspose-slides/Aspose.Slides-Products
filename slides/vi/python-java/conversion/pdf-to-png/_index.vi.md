---
title: Chuyển đổi PDF sang PNG trong Python
url: /vi/python-java/conversion/pdf-to-png/
keywords: Chuyển đổi bản trình bày Python, chuyển đổi bản trình bày sang Python, Python cho bản trình bày, Aspose.Slides Python, chuyển đổi PDF sang PNG, thư viện bản trình bày Python
description: Chuyển đổi PDF thành PNG bằng Python. Sử dụng API thư viện Python để chuyển đổi tệp PDF sang PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Dễ dàng chuyển đổi PDF sang PNG bằng Python: Aspose.Slides to the Rescue!" h2="Thổi sức sống mới vào bài thuyết trình của bạn bằng Python. Hướng dẫn của chúng tôi sẽ hướng dẫn bạn cách chuyển đổi các trang chiếu PowerPoint hiện có thành các bản trình bày Python hấp dẫn." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PDF sang PNG trong Python" %}}

Bạn mệt mỏi khi vật lộn với phần mềm trình chiếu phức tạp? Không cần tìm đâu xa ngoài [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/)! Thư viện mạnh mẽ này cho phép bạn tạo, chỉnh sửa và chuyển đổi bản trình bày giữa các định dạng khác nhau một cách dễ dàng. Bạn cần chuyển từ PDF sang PNG? Aspose.Slides làm cho nó trở nên dễ dàng, chỉ cần một vài dòng mã Python.

Là một API xử lý tài liệu tiên tiến, **Aspose.Slides for Python via Java** tự hào có tốc độ chuyển đổi nhanh như chớp, đảm bảo chuyển đổi nhanh chóng các bản trình bày PDF của bạn sang định dạng PNG. Loại bỏ những hạn chế của các công cụ truyền thống - Aspose.Slides cho phép bạn linh hoạt chuyển đổi bản trình bày từ PDF sang không chỉ PNG mà còn nhiều định dạng khác, cho phép bạn điều chỉnh bản trình bày của mình một cách hoàn hảo cho mọi tình huống.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF sang PNG bằng Python" %}}
Để chuyển đổi PDF sang PNG, bạn cần tạo Bản trình bày từ tệp PDF và lưu dưới dạng PNG.

{{% blocks/products/pf/agp/code-block title="Hướng dẫn Python để chuyển đổi PDF thành PNG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation();

pres.getSlides().removeAt(0);
pres.getSlides().addFromPdf("welcome-to-powerpoint.{format_from}");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hướng dẫn Python. Cách chuyển đổi PDF sang PNG bằng Aspose.Slides cho Python thông qua API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Để chuyển đổi PDF sang PNG bằng Aspose.Slides cho Python qua Java, bạn cần nhập gói vào tập lệnh Python và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn PDF bằng Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PDF sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PDF và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}