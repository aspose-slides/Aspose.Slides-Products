---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 對 PPTX 簡報去識別化
url: /zh-hant/cpp/redaction/pptx/
description: 在 C++ 中對 PPTX 簡報進行去識別化。使用 Aspose.Slides for C++ 尋找並取代簡報檔案中的敏感文字。
keywords: PPTX 去識別化，在 PPTX 中尋找和取代文字，更新 PPTX 簡報
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 對 PPTX 進行去識別化" h2="使用 Aspose.Slides for C++ 尋找並取代簡報檔案中的敏感文字，無需 Microsoft PowerPoint。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 對 PPTX 簡報進行去識別化" variant="code" %}}

Aspose.Slides for C++ 可透過取代投影片中的敏感文字，對 PPTX 簡報進行去識別化。將 `SlideUtil::FindAndReplaceText` 與 `Presentation` 物件搭配使用來搜尋簡報，並在儲存更新後的檔案之前取代相符的文字。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 對 PPTX 簡報進行去識別化" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 C++ 對 PPTX 進行去識別化" intro="依照下列步驟對 PPTX 簡報進行去識別化。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) 方法尋找並取代敏感文字。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Pptx` 儲存去識別化後的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="以 Aspose.Slides 建置" title="線上對 PPTX 檔案進行去識別化" description="免費的 Aspose.Slides Redaction 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Redaction" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，了解 Aspose.Slides 如何尋找和取代文字。
- 在您的 PPTX 檔案中尋找和取代文字，支援規則運算式。
- 下載去識別化後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援去識別化的格式" subTitle="使用 C++，您也可以對下列格式進行去識別化。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
