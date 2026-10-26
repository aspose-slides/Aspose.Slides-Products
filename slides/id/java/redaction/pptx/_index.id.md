---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sensor File Presentasi PPTX menggunakan Java
url: /id/java/redaction/pptx/
description: Cari dan ganti teks dalam presentasi PPTX di Java menggunakan Aspose.Slides for Java.
keywords: sensor PPTX, cari dan ganti teks di PPTX, perbarui presentasi PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sensor PPTX menggunakan Java" h2="Bangun aplikasi Java yang mencari dan mengganti teks dalam file presentasi menggunakan API sisi server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sensor Presentasi PPTX melalui Java" variant="code" %}}

Dengan [Aspose.Slides for Java](/slides/id/java/), Anda dapat mencari dan mengganti teks dalam presentasi PPTX. Gunakan metode `SlideUtil.findAndReplaceText` untuk menelusuri presentasi dan mengganti teks yang cocok dengan nilai baru.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sensor Presentasi PPTX menggunakan Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menyensor PPTX melalui Java" intro="Ikuti langkah-langkah berikut untuk menyensor presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `SlideUtil.findAndReplaceText` untuk mencari dan mengganti teks.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang telah diperbarui dengan `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Dibuat dengan Aspose.Slides" title="Sensor File PPTX Secara Online" description="Aplikasi Aspose.Slides Redaction gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Redaction" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mencari dan mengganti teks sebelum Anda menulis kode.
- Cari dan ganti teks di file PPTX Anda, termasuk dengan ekspresi reguler.
- Unduh file yang telah disensor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Penyensoran" subTitle="Dengan Java, Anda juga dapat menyensor format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
