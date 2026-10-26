---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 保護 PPT 簡報檔案
url: /zh-hant/python-net/protect/ppt/
description: 使用 Python 加密 PPT 簡報或設定防寫保護。
keywords: PPT 防寫保護, 使用 Python 加密 PPT, 鎖定 PPT 簡報, 使用 Python 保護 PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 保護 PPT 簡報" h2="建置使用 Aspose.Slides 加密簡報或設定防寫保護的 Python 應用程式。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 保護 PPT 簡報" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/zh-hant/python-net/) 提供兩種不同的保護機制。呼叫 `ProtectionManager.encrypt` 可加密 PPT 簡報，開啟時需要輸入密碼。您也可以呼叫 `ProtectionManager.set_write_protection`，在不加密檔案的情況下阻止修改。使用者仍可開啟受防寫保護的簡報，並將變更儲存到其他檔案。

{{< blocks/products/pf/slides-design-update-10-2026/code title="加密 PPT 簡報 – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="為 PPT 簡報設定防寫保護 – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 保護 PPT" intro="依照下列步驟保護 PPT 檔案。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 開啟 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager.encrypt` 要求開啟時輸入密碼，或使用 `ProtectionManager.set_write_protection` 阻止變更。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 將受保護的簡報另存為 PPT。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="以 Aspose.Slides 建置" title="線上以密碼保護 PPT 檔案" description="免費的 Aspose.Slides Lock 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Lock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何保護簡報。
- 設定開啟或編輯 PPT 檔案所需的密碼。
- 下載受保護的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援保護的格式" subTitle="使用 Python 保護其他支援的簡報格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
