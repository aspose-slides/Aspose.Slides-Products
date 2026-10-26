---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 在 ODP 簡報檔案中搜尋文字
url: /zh-hant/java/search/odp/
description: 使用 Aspose.Slides for Java 在 Java 中搜尋 ODP 簡報中的文字。
keywords: 在 ODP 中搜尋單字，在 ODP 中搜尋文字，搜尋 ODP 簡報文字
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 在 ODP 中搜尋文字" h2="建置透過伺服器端 API 在簡報檔案中搜尋文字的 Java 應用程式。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 Java 在 ODP 簡報中搜尋文字" variant="code" %}}

透過 [Aspose.Slides for Java](/slides/zh-hant/java/)，您可以在 ODP 簡報中搜尋文字。使用 `SlideUtil.getAllTextBoxes` 方法收集文字框架，然後檢查 `ITextFrame`、`IParagraph` 和 `IPortion` 物件。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 在 ODP 簡報中搜尋文字" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 Java 在 ODP 中搜尋文字" intro="依照下列步驟在 ODP 簡報中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `SlideUtil.getAllTextBoxes` 方法收集每張投影片的文字框架。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}檢查 `ITextFrame`、`IParagraph` 和 `IPortion` 物件以找出相符的文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="以 Aspose.Slides 建置" title="線上搜尋 ODP 檔案中的文字" description="免費的 Aspose.Slides Search 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Search" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找文字。
- 在您的 ODP 檔案中搜尋純文字或規則運算式。
- 將相符結果下載為文字檔。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援搜尋的格式" subTitle="使用 Java，您也可以在下列格式中搜尋文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
