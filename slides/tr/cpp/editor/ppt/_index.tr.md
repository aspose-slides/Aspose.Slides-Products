---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT'yi C++ ile düzenleyin
url: /tr/cpp/editor/ppt/
keywords: PPT'yi Düzenle, PowerPoint'i Düzenle, PPT, PowerPoint, C++ API, C++ Kitaplığı
description: PPT'yi C++ ile düzenleyin. PowerPoint sunumunu düzenlemek için C++ kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT'yi C++ ile düzenleyin" h2="C++ kodunu kullanarak PPT'yi düzenlemek için yüksek hızlı ve platformlar arası C++ kitaplığı" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT'yi C++ ile düzenleyin" variant="code" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) kullanarak, yalnızca birkaç satır kodla bir PPT belgesine yeni bir metin satırı ekleyebilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT'yi düzenlemek için C++ kodu" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak PPT'yi düzenleyin" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), sunumları işlemek ve düzenlemek için kullanılan güçlü bir C++ kitaplığıdır. Yeni bir metin satırı ekleyerek bir PPT sunumunu düzenleyebilirsiniz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++'da PPT nasıl düzenlenir?" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for C++** yükleyin. Bakınız [**Kurulum**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Düzenlemek istediğiniz PPT sunumunu yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yeni bir metin satırı ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen PowerPoint dosyasını kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
