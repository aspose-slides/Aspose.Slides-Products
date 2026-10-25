---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C# 為 PPT 簡報新增浮水印
url: /zh-hant/net/watermark/ppt/
description: 使用 Aspose.Slides for .NET 在 C# 中為 PPT 簡報新增文字與圖片浮水印。
keywords: 為 PPT 新增浮水印, 為 PPT 新增文字浮水印, 為 PPT 新增圖片浮水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 為 PPT 簡報新增浮水印" h2="建置可在簡報檔案中插入文字或圖片浮水印的 .NET 應用程式。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C# 為 PPT 簡報新增浮水印" variant="code" %}}

透過 [Aspose.Slides for .NET](/slides/zh-hant/net/)，可以為 PPT 簡報新增文字與圖片浮水印。將浮水印圖形新增到投影片母片，浮水印就會顯示在使用該母片的投影片上。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 為 PPT 新增文字浮水印" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 為 PPT 簡報新增圖片浮水印" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 為 PPT 新增浮水印" intro="依照下列步驟為 PPT 檔案新增文字或圖片浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 `PPT` 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}從 `Presentation.Masters` 集合中選取投影片母片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `AddAutoShape` 方法新增浮水印圖形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `AddTextFrame` 方法新增浮水印文字，或使用 `AddImage` 新增圖片浮水印。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Ppt` 儲存加上浮水印的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="以 Aspose.Slides 建置" title="線上為 PPT 檔案新增浮水印" description="免費的 Aspose.Slides Watermark 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Watermark" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何新增浮水印。
- 為 PPT 檔案新增文字或圖片浮水印。
- 下載加上浮水印的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援浮水印的格式" subTitle="使用 C#，也可以為下列格式新增浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
