---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit HTML dalam C#
url: /id/net/editor/html/
keywords: Edit HTML, HTML, C# API, Perpustakaan .NET
description: Edit HTML dalam C#. Gunakan .NET library API untuk mengedit file HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit HTML dalam C#" h2=".NET API lintas platform yang kuat untuk mengedit HTML menggunakan kode C# pada Platform NET Framework, .NET Core, Windows Azure, Mono atau Xamarin" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML dalam C#" variant="code" %}}

Dengan menggunakan [**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/), Anda dapat menambahkan baris teks baru ke dokumen HTML hanya dengan beberapa baris kode.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode C# untuk mengedit HTML" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // removes default empty slide
    pres.Slides.AddFromHtml("page.html");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("page.html", SaveFormat.Html);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML menggunakan Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/) adalah pustaka .NET andal yang digunakan untuk memanipulasi dan mengedit presentasi, dokumen HTML, dan file lainnya. Anda dapat mengedit dokumen HTML dengan menambahkan baris teks baru ke dalamnya.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengedit HTML di C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal **Aspose.Slides untuk .NET**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan perpustakaan sebagai referensi dalam proyek Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat sebuah instance dari kelas Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat dokumen HTML yang ingin Anda edit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan baris teks baru.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file HTML yang diubah.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Mengedit file lain" subTitle="Anda juga dapat mengedit file dalam format lain" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
