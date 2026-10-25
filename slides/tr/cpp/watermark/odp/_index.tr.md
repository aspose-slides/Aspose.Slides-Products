---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ ile ODP sunularına filigran ekleme
url: /tr/cpp/watermark/odp/
description: C++ ile ODP sunularına metin veya görüntü filigranı ekleyin. Sunu slaytlarına filigran yerleştirmek için Aspose.Slides for C++ kullanın.
keywords: ODP dosyasına filigran ekle, ODP dosyasına metin filigranı ekle, ODP dosyasına görüntü filigranı ekle
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile ODP sunusuna filigran ekleme" h2="Microsoft PowerPoint olmadan sunu dosyalarına metin veya görüntü filigranı eklemek için Aspose.Slides for C++ kullanın." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ aracılığıyla ODP sunusuna filigran ekleme" variant="code" %}}

Aspose.Slides for C++ ile ODP sunularına metin veya görüntü filigranı ekleyebilirsiniz. `AddAutoShape` ile asıl slayda filigran şekli ekleyin, `AddTextFrame` ile metin ekleyin veya şekli `File::ReadAllBytes` ve `AddImage` ile yüklenen bir görüntüyle doldurun.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ ile ODP dosyasına metin filigranı ekleme" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ ile ODP sunusuna görüntü filigranı ekleme" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile ODP dosyasına filigran nasıl eklenir" intro="ODP dosyalarına metin veya görüntü filigranı eklemek için şu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Masters` koleksiyonundan asıl slaydı seçin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddAutoShape` yöntemiyle bir filigran şekli ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddTextFrame` yöntemiyle filigran metni ekleyin veya `AddImage` ile resim dolgusu ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filigranlı dosyayı `SaveFormat::Odp` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides ile geliştirildi" title="ODP dosyalarına çevrimiçi filigran ekleyin" description="Ücretsiz Aspose.Slides Watermark uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Watermark uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın filigranları nasıl eklediğini görün.
- ODP dosyanıza metin veya görüntü filigranı ekleyin.
- Filigranlı dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Filigranı destekleyen diğer biçimler" subTitle="C++ ile aşağıdaki biçimlere de filigran ekleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
