---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 保護 PPTX 簡報檔案
url: /zh-hant/java/protect/pptx/
description: 在 Java 中保護 PPTX 簡報。使用 Aspose.Slides for Java 加密簡報檔案並設定防寫保護。
keywords: PPTX 防寫保護, 加密 PPTX 檔案, 鎖定 PPTX 簡報, 保護 PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 鎖定 PPTX 或以密碼保護" h2="建置透過伺服器端 API 保護簡報檔案的 Java 應用程式。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 Java 保護 PPTX 簡報" variant="code" %}}

透過 [Aspose.Slides for Java](/slides/zh-hant/java/)，您可以設定密碼，防止 PPTX 簡報被開啟或修改。使用 `Presentation` 類別中的 `ProtectionManager` 物件呼叫 `encrypt` 和 `setWriteProtection` 等方法。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 加密 PPTX 簡報" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 為 PPTX 簡報設定防寫保護" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 Java 以密碼保護 PPTX" intro="依照下列步驟保護 PPTX 簡報。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `ProtectionManager` 物件的 `encrypt` 方法或 `setWriteProtection` 方法。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 儲存受保護的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="以 Aspose.Slides 建置" title="線上以密碼保護 PPTX 檔案" description="免費的 Aspose.Slides Lock 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Lock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何保護簡報。
- 設定開啟或編輯 PPTX 檔案所需的密碼。
- 下載受保護的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援保護的格式" subTitle="使用 Java，您也可以保護下列格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
