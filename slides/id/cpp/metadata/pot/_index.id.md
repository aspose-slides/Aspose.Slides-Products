---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lihat atau Edit Metadata POT menggunakan C++
url: /id/cpp/metadata/pot/
description: Lihat dan edit metadata POT di C++. Gunakan Aspose.Slides for C++ untuk memperbarui properti bawaan dan kustom presentasi.
keywords: edit metadata POT, lihat metadata POT, edit properti POT, lihat properti POT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit Metadata POT menggunakan C++" h2="Gunakan Aspose.Slides for C++ untuk melihat dan memperbarui properti bawaan dan kustom dalam file presentasi." related="FODP,ODP,OTP,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ubah Properti POT melalui C++" variant="code" %}}

Aspose.Slides for C++ memungkinkan Anda membaca dan memperbarui metadata file POT tanpa Microsoft PowerPoint. Gunakan objek [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) yang disediakan `Presentation::get_DocumentProperties` untuk mengubah properti bawaan seperti `Author` dan `Title`, atau mengelola properti kustom dengan `idx_set`, `GetCustomPropertyName`, dan `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ubah Properti Bawaan POT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pot");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.pot", SaveFormat::Pot);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Properti Kustom ke POT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pot");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.pot", SaveFormat::Pot);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Melihat atau Mengedit Metadata POT di C++" intro="Ikuti langkah-langkah berikut untuk melihat atau mengedit metadata POT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file POT dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ambil objek `DocumentProperties` dengan `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Baca atau perbarui properti bawaan seperti `Author` dan `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan, baca, atau hapus properti kustom dengan `idx_set`, `GetCustomPropertyName`, dan `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Dibuat dengan Aspose.Slides" title="Lihat dan Edit Metadata POT Secara Online" description="Aplikasi Aspose.Slides Metadata gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file POT Anda sendiri." button="Buka Aspose.Slides Metadata" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membaca dan menulis properti sebelum menulis kode.
- Lihat dan edit properti bawaan dan kustom file POT Anda.
- Simpan dan unduh file yang diperbarui.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Metadata Lain yang Didukung" subTitle="Dengan C++, Anda juga dapat mengelola metadata format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
