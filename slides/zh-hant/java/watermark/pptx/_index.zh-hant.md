---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 為 PPTX 簡報檔案新增浮水印
url: /zh-hant/java/watermark/pptx/
description: 使用 Aspose.Slides for Java 在 Java 中為 PPTX 簡報新增文字與圖片浮水印。
keywords: 為 PPTX 新增浮水印, 為 PPTX 新增文字浮水印, 為 PPTX 新增圖片浮水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 為 PPTX 簡報新增浮水印" h2="建置使用伺服器端 API 在簡報檔案中插入文字或圖片浮水印的 Java 應用程式。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 Java 為 PPTX 簡報新增浮水印" variant="code" %}}

透過 [Aspose.Slides for Java](/slides/zh-hant/java/)，可以為 PPTX 簡報新增文字與圖片浮水印。將浮水印圖形新增到投影片母片，浮水印就會顯示在使用該母片的投影片上。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 為 PPTX 新增文字浮水印" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 為 PPTX 簡報新增圖片浮水印" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Java 為 PPTX 新增浮水印" intro="依照下列步驟為 PPTX 檔案新增文字或圖片浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 `PPTX` 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `getMasters` 方法選取投影片母片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `addAutoShape` 方法新增浮水印圖形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `addTextFrame` 方法新增浮水印文字，或使用 `addImage` 新增圖片浮水印。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}將加上浮水印的簡報儲存為 PPTX 格式。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="以 Aspose.Slides 建置" title="線上為 PPTX 檔案新增浮水印" description="免費的 Aspose.Slides Watermark 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Watermark" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何新增浮水印。
- 為 PPTX 檔案新增文字或圖片浮水印。
- 下載加上浮水印的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援浮水印的格式" subTitle="使用 Java，也可以為下列格式新增浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
