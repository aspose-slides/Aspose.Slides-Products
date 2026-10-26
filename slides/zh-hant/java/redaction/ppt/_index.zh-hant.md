---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 對 PPT 簡報檔案進行去識別化
url: /zh-hant/java/redaction/ppt/
description: 使用 Aspose.Slides for Java 在 Java 中尋找和取代 PPT 簡報中的文字。
keywords: PPT 去識別化，在 PPT 中尋找和取代文字，更新 PPT 簡報
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 對 PPT 進行去識別化" h2="建置透過伺服器端 API 在簡報檔案中尋找和取代文字的 Java 應用程式。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 Java 對 PPT 簡報進行去識別化" variant="code" %}}

透過 [Aspose.Slides for Java](/slides/zh-hant/java/)，您可以在 PPT 簡報中尋找和取代文字。使用 `SlideUtil.findAndReplaceText` 方法搜尋簡報，並將相符的文字取代為新值。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 對 PPT 簡報進行去識別化" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 Java 對 PPT 進行去識別化" intro="依照下列步驟對 PPT 簡報進行去識別化。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `SlideUtil.findAndReplaceText` 方法尋找和取代文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Ppt` 儲存更新後的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="以 Aspose.Slides 建置" title="線上對 PPT 檔案進行去識別化" description="免費的 Aspose.Slides Redaction 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Redaction" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找和取代文字。
- 在您的 PPT 檔案中尋找和取代文字，支援規則運算式。
- 下載去識別化後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援去識別化的格式" subTitle="使用 Java，您也可以對下列格式進行去識別化。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
