---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sensor File Presentasi PPT menggunakan Java
url: /id/java/redaction/ppt/
description: Cari dan ganti teks dalam presentasi PPT di Java menggunakan Aspose.Slides for Java.
keywords: sensor PPT, cari dan ganti teks di PPT, perbarui presentasi PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sensor PPT menggunakan Java" h2="Bangun aplikasi Java yang mencari dan mengganti teks dalam file presentasi menggunakan API sisi server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sensor Presentasi PPT melalui Java" variant="code" %}}

Dengan [Aspose.Slides for Java](/slides/id/java/), Anda dapat mencari dan mengganti teks dalam presentasi PPT. Gunakan metode `SlideUtil.findAndReplaceText` untuk menelusuri presentasi dan mengganti teks yang cocok dengan nilai baru.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sensor Presentasi PPT menggunakan Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menyensor PPT melalui Java" intro="Ikuti langkah-langkah berikut untuk menyensor presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `SlideUtil.findAndReplaceText` untuk mencari dan mengganti teks.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang telah diperbarui dengan `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Dibuat dengan Aspose.Slides" title="Sensor File PPT Secara Online" description="Aplikasi Aspose.Slides Redaction gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Redaction" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mencari dan mengganti teks sebelum Anda menulis kode.
- Cari dan ganti teks di file PPT Anda, termasuk dengan ekspresi reguler.
- Unduh file yang telah disensor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Penyensoran" subTitle="Dengan Java, Anda juga dapat menyensor format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
