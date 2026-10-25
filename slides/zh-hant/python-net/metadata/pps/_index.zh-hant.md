---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 檢視或編輯 PPS 中繼資料
url: /zh-hant/python-net/metadata/pps/
description: 使用 Python 檢視和編輯 PPS 檔案中的內建與自訂中繼資料屬性。
keywords: 編輯 PPS 中繼資料, 檢視 PPS 中繼資料, 編輯 PPS 屬性, 檢視 PPS 屬性
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 檢視和編輯 PPS 中繼資料" h2="建置使用 Aspose.Slides 讀取和修改簡報內建屬性與自訂屬性的 Python 應用程式。" related="FODP,ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 檢視和修改 PPS 中繼資料" variant="code" %}}

透過 [**Aspose.Slides for Python via .NET**](/slides/zh-hant/python-net/)，可以讀取和更新 PPS 簡報的內建中繼資料，並新增、更新或移除自訂文件屬性。透過 `Presentation.document_properties` 存取 [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) 物件，修改後將簡報儲存為 PPS 格式。

{{< blocks/products/pf/slides-design-update-10-2026/code title="更新 PPS 內建屬性 - Python" >}}
```python
with slides.Presentation("presentation.pps") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pps", slides.export.SaveFormat.PPS)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="新增和移除 PPS 自訂屬性 - Python" >}}
```python
with slides.Presentation("presentation.pps") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pps", slides.export.SaveFormat.PPS)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 編輯 PPS 中繼資料" intro="依照下列步驟編輯 PPS 檔案的中繼資料。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 PPS 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}透過 `Presentation.document_properties` 存取其 `IDocumentProperties` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}更新內建屬性，或對自訂屬性使用 `set_custom_property_value` 和 `remove_custom_property`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation.save` 和 `SaveFormat.PPS` 儲存簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="以 Aspose.Slides 建置" title="線上檢視和編輯 PPS 中繼資料" description="免費的 Aspose.Slides Metadata 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPS 檔案。" button="開啟 Aspose.Slides Metadata" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何讀寫屬性。
- 檢視和編輯 PPS 檔案的內建屬性與自訂屬性。
- 儲存並下載更新後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援的中繼資料格式" subTitle="使用 Python，也可以管理其他支援的簡報格式的中繼資料。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
