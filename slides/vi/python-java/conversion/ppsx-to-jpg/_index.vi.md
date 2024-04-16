---
title: Chuyển đổi PPSX sang JPG trong Python
url: /vi/python-java/conversion/ppsx-to-jpg/
keywords: Chuyển đổi bản trình bày Python, chuyển đổi bản trình bày sang Python, Python cho bản trình bày, Aspose.Slides Python, chuyển đổi PPSX sang JPG, thư viện bản trình bày Python
description: Chuyển đổi PPSX thành JPG bằng Python. Sử dụng API thư viện Python để chuyển đổi tệp PPSX sang JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Dễ dàng chuyển đổi PPSX sang JPG bằng Python: Aspose.Slides to the Rescue!" h2="Thổi sức sống mới vào bài thuyết trình của bạn bằng Python. Hướng dẫn của chúng tôi sẽ hướng dẫn bạn cách chuyển đổi các trang chiếu PowerPoint hiện có thành các bản trình bày Python hấp dẫn." >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi PPSX sang JPG trong Python" %}}

Bạn mệt mỏi khi vật lộn với phần mềm trình chiếu phức tạp? Không cần tìm đâu xa ngoài [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/)! Thư viện mạnh mẽ này cho phép bạn tạo, chỉnh sửa và chuyển đổi bản trình bày giữa các định dạng khác nhau một cách dễ dàng. Bạn cần chuyển từ PPSX sang JPG? Aspose.Slides làm cho nó trở nên dễ dàng, chỉ cần một vài dòng mã Python.

Là một API xử lý tài liệu tiên tiến, **Aspose.Slides for Python via Java** tự hào có tốc độ chuyển đổi nhanh như chớp, đảm bảo chuyển đổi nhanh chóng các bản trình bày PPSX của bạn sang định dạng JPG. Loại bỏ những hạn chế của các công cụ truyền thống - Aspose.Slides cho phép bạn linh hoạt chuyển đổi bản trình bày từ PPSX sang không chỉ JPG mà còn nhiều định dạng khác, cho phép bạn điều chỉnh bản trình bày của mình một cách hoàn hảo cho mọi tình huống.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPSX sang JPG bằng Python" %}}
Để chuyển đổi PPSX sang JPG, bạn cần tạo Bản trình bày từ tệp PPSX và lưu dưới dạng JPG.

{{% blocks/products/pf/agp/code-block title="Hướng dẫn Python để chuyển đổi PPSX thành JPG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppsx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hướng dẫn Python. Cách chuyển đổi PPSX sang JPG bằng Aspose.Slides cho Python thông qua API Java." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Để chuyển đổi PPSX sang JPG bằng Aspose.Slides cho Python qua Java, bạn cần nhập gói vào tập lệnh Python và tạo một phiên bản của lớp Trình bày. Lớp Trình bày đại diện cho một tài liệu PowerPoint và cung cấp các phương thức để truy cập và thao tác các phần tử của nó." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cài đặt [**Aspose.Slides for Python via Java**](https://products.aspose.com/slides/vi/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Thêm tham chiếu thư viện (nhập thư viện) vào dự án Python của bạn.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mở tệp nguồn PPSX bằng Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lưu kết quả dưới dạng tệp JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Chuyển đổi PPSX sang các định dạng được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi PPSX và lưu sang các định dạng tệp khác. Xem tất cả các định dạng được hỗ trợ bên dưới" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/vi/python-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}