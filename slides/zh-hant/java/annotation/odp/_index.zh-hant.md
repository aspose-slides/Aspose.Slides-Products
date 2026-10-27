---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: 使用 Java 移除 ODP 註解
url: /zh-hant/java/annotation/odp/ 
description: 透過 Aspose.Slides for Java，使用 Java 從 ODP 簡報中移除註解和註解作者。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 從 ODP 移除註解和註解作者" h2="使用 Aspose.Slides for Java 從簡報檔案中移除註解和註解作者。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 Java 從 ODP 移除註解" variant="code" %}}

Aspose.Slides for Java 可讓您從 ODP 簡報中移除註解和註解作者。使用 `Presentation` 類別載入檔案，逐一處理 `getCommentAuthors` 傳回的 `ICommentAuthor` 物件並清除其註解，然後儲存更新後的簡報。

{{< blocks/products/pf/slides-design-update-10-2026/code title="從 ODP 刪除註解 – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 Java 從 ODP 移除註解" intro="依照下列步驟，從 ODP 簡報中移除註解和註解作者。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝 Aspose.Slides for Java。請參閱[安裝](https://docs.aspose.com/slides/java/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理 `getCommentAuthors` 傳回的 `ICommentAuthor` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `getComments().clear()` 清除每位作者的註解。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}清空註解作者集合並儲存更新後的 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="以 Aspose.Slides 建置" title="線上移除 ODP 註解" description="免費的 Aspose.Slides Annotation 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Annotation" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何移除註解。
- 移除 ODP 檔案中的所有註解。
- 下載清理後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="註解支援的其他格式" subTitle="使用 Java，您也可以從其他格式移除註解。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
