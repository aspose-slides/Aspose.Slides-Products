---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++'da JPG biçimini PDF biçimine dönüştürün
url: /tr/cpp/conversion/jpg-to-pdf/
keywords: JPG'tan PDF'a, JPG'ı PDF'a Dönüştür, C++ API, C++ Kitaplığı, JPG, PDF
description: C++'da JPG öğesini PDF biçimine dönüştürün. JPG dosyalarını PDF dosyalarına dönüştürmek için C++ kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++'da JPG biçimini PDF biçimine dönüştürün" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan Microsoft PowerPoint ve OpenOffice sunum dosyalarını oluşturma, birleştirme, inceleme veya dönüştürme becerisine sahip uygulamaların geliştirilmesine yardımcı olan yüksek hızlı ve platformlar arası C++ Kitaplığı." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ kullanarak JPG biçimini PDF biçimine dönüştürün" variant="code" %}}

JPG dosyasını PDF biçimine dönüştürmek için, JPG dosyasından Sunu oluşturmanız ve onu PDF olarak kaydetmeniz gerekir.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JPG biçimini PDF biçimine dönüştürmek için C++ kodu" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++'da JPG biçimini PDF biçimine dönüştürün" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir C++ kitaplığıdır. Ayrıca, JPG biçimini PDF biçimine dönüştürmek için esnek yollar sağlar. **Aspose.Slides for C++** kullanan herhangi bir geliştirici veya uygulama, yalnızca birkaç satırlık C++ koduyla JPG dosyasını PDF dosyasına dönüştürebilir.

Modern bir belge işleme API'si olarak Aspose.Slides for C++, JPG dosyalarını hızlı bir şekilde PDF dosya biçimlerine aktarır. Aspose PowerPoint kitaplığı, JPG biçimini PDF biçimlerine ve diğer birçok dosya biçimine dönüştürmenize izin verir

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for C++ API kullanarak JPG biçimini PDF biçimine dönüştürme" intro="Bunlar, C++'da JPG biçimini PDF biçimine dönüştürme adımlarıdır." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}C++ projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kaynak JPG dosyalarını C++ ile açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sonucu PDF dosyası olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ücretsiz Çevrimiçi Dönüştürücü"
  description="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="JPG biçimini Desteklenen Diğer Biçimlere Dönüştürün" subTitle="Ayrıca JPG dosyasını dönüştürebilir ve diğer dosya biçimlerine kaydedebilirsiniz. Aşağıda desteklenen tüm biçimleri görün" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
