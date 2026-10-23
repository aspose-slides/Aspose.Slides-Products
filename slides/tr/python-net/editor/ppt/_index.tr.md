---
lastmod: 2023-01-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python'da PPT'yi düzenleyin
url: /tr/python-net/editor/ppt/
keywords: PPT'yi Düzenle, PowerPoint'i Düzenle, PPT, PowerPoint, Python API, Python Kitaplığı
description: Python'da PPT'yi düzenleyin. PowerPoint sunumunu düzenlemek için Python kitaplığı API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python'da PPT'yi düzenleyin" h2="Python kodunu kullanarak PPT'yi düzenlemek için yüksek hızlı ve platformlar arası Python kitaplığı" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python'da PPT'yi düzenleyin" variant="code" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/) kullanarak, bir PPT belgesine yalnızca birkaç satırla yeni bir metin satırı ekleyebilirsiniz. Kod satırları.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT'yi düzenlemek için Python kodu" >}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak PPT'yi düzenleyin" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/tr/python-net/), sunumları işlemek ve düzenlemek için kullanılan güçlü bir Python kitaplığıdır. Yeni bir metin satırı ekleyerek bir PPT sunumunu düzenleyebilirsiniz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python'da PPT nasıl düzenlenir" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Python'u .NET üzerinden** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Düzenlemek istediğiniz PPT sunumunu yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yeni bir metin satırı ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Değiştirilen PowerPoint dosyasını kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarını Çevrimiçi Düzenleyin" description="Ücretsiz Aspose.Slides Editor uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Editor uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyalarınızı nasıl işlediğini görün.
- PPTX dosyalarınızı yükleyin ve anında düzenleyin.
- Düzenlenen dosyayı kaydedin ve indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
