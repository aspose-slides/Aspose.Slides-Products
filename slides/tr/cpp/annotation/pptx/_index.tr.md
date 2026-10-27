---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: C++ ile PPTX ek açıklamalarını kaldırma
url: /tr/cpp/annotation/pptx/ 
description: PPTX sunumlarından ek açıklamaları kaldırmak için C++ kaynak kodu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile PPTX dosyasından yorumları ve yorum yazarlarını kaldırma" h2="Sunucu tarafı API'lerle sunum dosyalarındaki yorumları ve yazarları yöneten C++ uygulamaları oluşturun." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ ile PPTX dosyasından yorumları kaldırma" variant="code" %}}

PPTX sunumlarından yorumları ve yorum yazarlarını kaldırmak için [Aspose.Slides for C++](/slides/tr/cpp/) kullanın. Aşağıdaki örnek, `get_CommentAuthors` içindeki her yazarın yorumlarını ve ardından yorum yazarı koleksiyonunu temizler.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX dosyasından ek açıklamaları silme – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.pptx");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile PPTX dosyasından yorumlar nasıl kaldırılır" intro="Bir PPTX sunumundan yorumları ve yorum yazarlarını kaldırmak için bu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for C++'ı yükleyin. Bkz. [Kurulum](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_CommentAuthors` içindeki yorum yazarlarında dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her yazarın yorumlarını `get_Comments()->Clear()` ile temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Yorum yazarı koleksiyonunu temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Güncellenen sunumu `SaveFormat::Pptx` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides ile geliştirildi" title="PPTX yorumlarını çevrimiçi kaldırma" description="Ücretsiz Aspose.Slides Annotation uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Annotation uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın yorumları nasıl kaldırdığını görün.
- PPTX dosyanızdaki tüm yorumları kaldırın.
- Temizlenen dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ek açıklamalar için desteklenen diğer biçimler" subTitle="C++ ile diğer biçimlerden de ek açıklamaları kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
