---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 檢視或編輯 FODP 中繼資料
url: /zh-hant/cpp/metadata/fodp/
description: 在 C++ 中檢視和編輯 FODP 中繼資料。使用 Aspose.Slides for C++ 更新簡報的內建屬性與自訂屬性。
keywords: 編輯 FODP 中繼資料, 檢視 FODP 中繼資料, 編輯 FODP 屬性, 檢視 FODP 屬性
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 編輯 FODP 中繼資料" h2="使用 Aspose.Slides for C++ 檢視和更新簡報檔案的內建屬性與自訂屬性。" related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 修改 FODP 屬性" variant="code" %}}

透過 Aspose.Slides for C++，無需 Microsoft PowerPoint 即可讀取和更新 FODP 檔案的中繼資料。使用 `Presentation::get_DocumentProperties` 提供的 [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) 物件變更 `Author` 和 `Title` 等內建屬性，或使用 `idx_set`、`GetCustomPropertyName` 和 `RemoveCustomProperty` 管理自訂屬性。

{{< blocks/products/pf/slides-design-update-10-2026/code title="修改 FODP 內建屬性 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.fodp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.fodp", SaveFormat::Fodp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="為 FODP 新增自訂屬性 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.fodp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.fodp", SaveFormat::Fodp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 C++ 中檢視或編輯 FODP 中繼資料" intro="依照下列步驟檢視或編輯 FODP 中繼資料。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 FODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `get_DocumentProperties` 取得 `DocumentProperties` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}讀取或更新 `Author` 和 `Title` 等內建屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `idx_set`、`GetCustomPropertyName` 和 `RemoveCustomProperty` 新增、讀取或移除自訂屬性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="以 Aspose.Slides 建置" title="線上檢視和編輯 FODP 中繼資料" description="免費的 Aspose.Slides Metadata 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 FODP 檔案。" button="開啟 Aspose.Slides Metadata" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何讀寫屬性。
- 檢視和編輯 FODP 檔案的內建屬性與自訂屬性。
- 儲存並下載更新後的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援的中繼資料格式" subTitle="使用 C++，也可以管理下列格式的中繼資料。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
