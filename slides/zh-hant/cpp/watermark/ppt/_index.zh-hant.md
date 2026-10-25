---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 為 PPT 簡報新增浮水印
url: /zh-hant/cpp/watermark/ppt/
description: 在 C++ 中為 PPT 簡報新增文字或圖片浮水印。使用 Aspose.Slides for C++ 在投影片上放置浮水印。
keywords: 為 PPT 新增浮水印, 為 PPT 新增文字浮水印, 為 PPT 新增圖片浮水印
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 為 PPT 簡報新增浮水印的方法" h2="使用 Aspose.Slides for C++，無需 Microsoft PowerPoint 即可為簡報檔案新增文字或圖片浮水印。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 為 PPT 簡報新增浮水印" variant="code" %}}

透過 Aspose.Slides for C++，可以為 PPT 簡報新增文字或圖片浮水印。使用 `AddAutoShape` 在投影片母片上新增浮水印圖形，使用 `AddTextFrame` 新增文字，或使用透過 `File::ReadAllBytes` 和 `AddImage` 載入的圖片填滿圖形。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 為 PPT 新增文字浮水印" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 為 PPT 簡報新增圖片浮水印" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C++ 為 PPT 新增浮水印" intro="依照下列步驟為 PPT 檔案新增文字或圖片浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}從 `Presentation::get_Masters` 集合中選取投影片母片。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `AddAutoShape` 方法新增浮水印圖形。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `AddTextFrame` 方法新增浮水印文字，或使用 `AddImage` 設定圖片填滿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Ppt` 儲存加上浮水印的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="以 Aspose.Slides 建置" title="線上為 PPT 檔案新增浮水印" description="免費的 Aspose.Slides Watermark 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Watermark" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何新增浮水印。
- 為 PPT 檔案新增文字或圖片浮水印。
- 下載加上浮水印的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援浮水印的格式" subTitle="使用 C++，也可以為下列格式新增浮水印。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
