---
title: Chuyển đổi PPT sang BMP trong Python
url: /vi/python-java/conversion/ppt-to-bmp/
keywords: Chuyển đổi bản trình bày Python, chuyển đổi bản trình bày sang Python, Python cho bản trình bày, Aspose.Slides Python, chuyển đổi PPT sang BMP, thư viện bản trình bày Python
description: Chuyển đổi PPT thành BMP bằng Python. Sử dụng API thư viện Python để chuyển đổi tệp PPT sang BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Dễ dàng chuyển đổi PPT sang BMP bằng Python: Aspose.Slides to the Rescue!" h2="Thổi sức sống mới vào bài thuyết trình của bạn bằng Python. Hướng dẫn của chúng tôi sẽ hướng dẫn bạn cách chuyển đổi các trang chiếu PowerPoint hiện có thành các bản trình bày Python hấp dẫn." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PPT sang BMP trong Python" %}}

Bạn mệt mỏi khi vật lộn với phần mềm trình chiếu phức tạp? Không cần tìm đâu xa ngoài [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/)! Thư viện mạnh mẽ này cho phép bạn tạo, chỉnh sửa và chuyển đổi bản trình bày giữa các định dạng khác nhau một cách dễ dàng. Bạn cần chuyển từ PPT sang BMP? Aspose.Slides làm cho nó trở nên dễ dàng, chỉ cần một vài dòng mã Python.

Là một API xử lý tài liệu tiên tiến, **Aspose.Slides for Python via Java** tự hào có tốc độ chuyển đổi nhanh như chớp, đảm bảo chuyển đổi nhanh chóng các bản trình bày PPT của bạn sang định dạng BMP. Loại bỏ những hạn chế của các công cụ truyền thống - Aspose.Slides cho phép bạn linh hoạt chuyển đổi bản trình bày từ PPT sang không chỉ BMP mà còn nhiều định dạng khác, cho phép bạn điều chỉnh bản trình bày của mình một cách hoàn hảo cho mọi tình huống.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPT sang BMP bằng Python" %}}
Để chuyển đổi PPT sang BMP, bạn cần tạo Bản trình bày từ tệp PPT và lưu dưới dạng BMP.

{{% blocks/products/pf/agp/code-block title="Hướng dẫn Python để chuyển đổi PPT thành BMP" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppt");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hướng dẫn Python. Cách chuyển đổi PPT sang BMP bằng Aspose.Slides cho Python thông qua API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Để chuyển đổi PPT sang BMP bằng Aspose.Slides cho Python qua Java, bạn cần nhập gói vào tập lệnh Python và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn PPT bằng Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PPT sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPT và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}