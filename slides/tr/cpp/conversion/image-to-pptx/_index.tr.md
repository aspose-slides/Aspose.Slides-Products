---
title: Görüntüyü C++ ile PPTX'e Dönüştür
url: /tr/cpp/conversion/image-to-pptx/
keywords: Görüntüyü PPTX'e, Görüntüyü PPTX'e Dönüştürme, C++ API, C++ Kitaplığı, Görüntü, PPTX
description: Görüntüyü C++ ile PPTX'e dönüştürün. Görüntü dosyalarını PDF'lere dönüştürmek için C++ kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Görüntüyü C++ ile PPTX'e Dönüştür" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası C++ Kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="Görüntüyü C++ ile PPTX'e Dönüştür" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir C++ kitaplığıdır. Ayrıca, Görüntüyü PPTX'e dönüştürmek için esnek yollar sağlar. **Aspose.Slides for C++** kullanarak, herhangi bir geliştirici veya uygulama, Image'i yalnızca birkaç satırlık C++ koduyla PPTX dosyalarına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for C++, Görüntü dosyalarını hızlı bir şekilde PPTX dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, Görüntüyü PDF'lere ve diğer birçok dosya biçimine dönüştürmenize olanak tanır

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Görüntüyü C++ kullanarak PPTX'e dönüştürün" %}}
Görüntüyü PPTX'e dönüştürmek için, Görüntü dosyasından Sunum oluşturmanız ve PPTX olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="Görüntüyü PPTX'e dönüştürmek için C++ kodu" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.pptx", SaveFormat::Pptx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for C++ API kullanarak Görüntüyü PPTX'e dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, C++'da Görüntüyü PPTX'e dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C++ projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak Görüntü dosyalarını C++ ile açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPTX dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Görüntüyü Desteklenen Diğer Biçimlere Dönüştür" subTitle="Ayrıca Görüntüyü dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}