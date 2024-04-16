---
title: Chuyển đổi POTX sang BMP trong Python
url: /vi/python-java/conversion/potx-to-bmp/
keywords: Chuyển đổi bản trình bày Python, chuyển đổi bản trình bày sang Python, Python cho bản trình bày, Aspose.Slides Python, chuyển đổi POTX sang BMP, thư viện bản trình bày Python
description: Chuyển đổi POTX thành BMP bằng Python. Sử dụng API thư viện Python để chuyển đổi tệp POTX sang BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Dễ dàng chuyển đổi POTX sang BMP bằng Python: Aspose.Slides to the Rescue!" h2="Thổi sức sống mới vào bài thuyết trình của bạn bằng Python. Hướng dẫn của chúng tôi sẽ hướng dẫn bạn cách chuyển đổi các trang chiếu PowerPoint hiện có thành các bản trình bày Python hấp dẫn." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi POTX sang BMP trong Python" %}}

Bạn mệt mỏi khi vật lộn với phần mềm trình chiếu phức tạp? Không cần tìm đâu xa ngoài [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/)! Thư viện mạnh mẽ này cho phép bạn tạo, chỉnh sửa và chuyển đổi bản trình bày giữa các định dạng khác nhau một cách dễ dàng. Bạn cần chuyển từ POTX sang BMP? Aspose.Slides làm cho nó trở nên dễ dàng, chỉ cần một vài dòng mã Python.

Là một API xử lý tài liệu tiên tiến, **Aspose.Slides for Python via Java** tự hào có tốc độ chuyển đổi nhanh như chớp, đảm bảo chuyển đổi nhanh chóng các bản trình bày POTX của bạn sang định dạng BMP. Loại bỏ những hạn chế của các công cụ truyền thống - Aspose.Slides cho phép bạn linh hoạt chuyển đổi bản trình bày từ POTX sang không chỉ BMP mà còn nhiều định dạng khác, cho phép bạn điều chỉnh bản trình bày của mình một cách hoàn hảo cho mọi tình huống.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi POTX sang BMP bằng Python" %}}
Để chuyển đổi POTX sang BMP, bạn cần tạo Bản trình bày từ tệp POTX và lưu dưới dạng BMP.

{{% blocks/products/pf/agp/code-block title="Hướng dẫn Python để chuyển đổi POTX thành BMP" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.potx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hướng dẫn Python. Cách chuyển đổi POTX sang BMP bằng Aspose.Slides cho Python thông qua API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Để chuyển đổi POTX sang BMP bằng Aspose.Slides cho Python qua Java, bạn cần nhập gói vào tập lệnh Python và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn POTX bằng Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi POTX sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi POTX và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}