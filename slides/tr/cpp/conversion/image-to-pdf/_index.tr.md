---
title: C++'da Image biçimini PDF biçimine dönüştürün
url: /tr/cpp/conversion/image-to-pdf/
keywords: Image'tan PDF'a, Image'ı PDF'a Dönüştür, C++ API, C++ Kitaplığı, Image, PDF
description: C++'da Image öğesini PDF biçimine dönüştürün. Image dosyalarını PDF dosyalarına dönüştürmek için C++ kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++'da Image biçimini PDF biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası C++ Kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="C++'da Image biçimini PDF biçimine dönüştürün" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir C++ kitaplığıdır. Ayrıca, Image biçimini PDF biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for C++** kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık C++ koduyla Image dosyasını PDF dosyasına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for C++, Image dosyalarını hızlı bir şekilde PDF dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, Image biçimini PDF biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ kullanarak Image biçimini PDF biçimine dönüştürün" %}}
Image dosyasını PDF biçimine dönüştürmek için, Image dosyasından Sunu oluşturmanız ve onu PDF olarak kaydetmeniz gerekir.

{{% blocks/products/pf/agp/code-block title="Image biçimini PDF biçimine dönüştürmek için C++ kodu" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for C++ API kullanarak Image biçimini PDF biçimine dönüştürme" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, C++'da Image biçimini PDF biçimine dönüştürme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C++ projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak Image dosyalarını C++ ile açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PDF dosyası olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Image biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca Image dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}