---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PDF'yi C++ ile düzenleyin
url: /tr/cpp/editor/pdf/
keywords: PDF, PDF, C++ API, C++ Kitaplığını Düzenle
description: PDF'yi C++ ile düzenleyin. PDF belgesini düzenlemek için C++ kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PDF'yi C++ ile düzenleyin" h2="C++ kodunu kullanarak PDF düzenlemek için yüksek hızlı ve platformlar arası C++ kitaplığı" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF'yi C++ ile düzenleyin" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) kullanarak, yalnızca birkaç satır kodla bir PDF belgesine yeni bir metin satırı ekleyebilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PDF'yi düzenlemek için C++ kodu" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak PDF'yi düzenleyin" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), sunumları, PDF belgelerini ve diğer dosyaları işlemek ve düzenlemek için kullanılan güçlü bir C++ kitaplığıdır. Yeni bir metin satırı ekleyerek bir PDF belgesini düzenleyebilirsiniz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++'da PDF nasıl düzenlenir" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for C++** yükleyin. Bakınız [**Kurulum**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Düzenlemek istediğiniz PDF belgesini yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yeni bir metin satırı ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen PDF dosyasını kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
