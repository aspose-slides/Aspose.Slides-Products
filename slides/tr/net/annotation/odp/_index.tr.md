---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: .NET ile ODP ek açıklamalarını kaldırma
url: /tr/net/annotation/odp/ 
description: C# ile ODP sunumlarından yorumları ve yorum yazarlarını kaldırın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile ODP dosyasından yorumları ve yorum yazarlarını kaldırma" h2="Sunucu tarafı API'lerle sunum dosyalarındaki yorumları ve yazarları yöneten .NET uygulamaları oluşturun." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile ODP dosyasından yorumları kaldırma" variant="code" %}}

ODP sunum dosyalarından yorumları ve yorum yazarlarını kaldırmak için [Aspose.Slides for .NET](/slides/tr/net/) kullanın. Aşağıdaki örnek, her yazarın `Comments` koleksiyonunu ve ardından sunumun `CommentAuthors` koleksiyonunu temizler.

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP dosyasından ek açıklamaları silme – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile ODP dosyasından yorumlar nasıl kaldırılır" intro="Bir ODP sunumundan yorumları ve yorum yazarlarını kaldırmak için bu adımları izleyin." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aspose.Slides for .NET'i yükleyin. Bkz. [Kurulum](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`CommentAuthors` koleksiyonunda dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her yorum yazarının `Comments` koleksiyonunu temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`CommentAuthors` koleksiyonunu temizleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Güncellenen sunumu `SaveFormat.Odp` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Aspose.Slides ile geliştirildi" title="ODP yorumlarını çevrimiçi kaldırma" description="Ücretsiz Aspose.Slides Annotation uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Annotation uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın yorumları nasıl kaldırdığını görün.
- ODP dosyanızdaki tüm yorumları kaldırın.
- Temizlenen dosyayı indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ek açıklamalar için desteklenen diğer biçimler" subTitle="C# ile diğer biçimlerden de ek açıklamaları kaldırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
