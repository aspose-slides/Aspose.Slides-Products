---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 解除鎖定 PPT 簡報
url: /zh-hant/python-net/unlock/ppt/
description: 使用 Python 移除 PPT 簡報的加密與防寫保護。
keywords: 解除鎖定 PPT, 移除 PPT 密碼, 移除 PPT 加密, 移除 PPT 防寫保護
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 解除鎖定 PPT 簡報" h2="建置使用 Aspose.Slides 移除 PPT 簡報開啟密碼與防寫保護設定的 Python 應用程式。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 移除 PPT 的加密與防寫保護" variant="code" %}}

透過 [Aspose.Slides for Python via .NET](/slides/zh-hant/python-net/)，您可以移除開啟 PPT 簡報時需要輸入密碼的加密，或清除其防寫保護設定。若要開啟加密檔案，請透過 `LoadOptions` 提供目前的密碼。

{{< blocks/products/pf/slides-design-update-10-2026/code title="移除 PPT 簡報的加密 – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="移除 PPT 簡報的防寫保護 – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 移除 PPT 的保護" intro="依照下列步驟移除 PPT 簡報的保護。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}若為加密的 PPT 檔案，請在 `LoadOptions` 中設定目前的密碼，然後使用 `Presentation` 開啟檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `ProtectionManager.remove_encryption` 移除開啟密碼，或呼叫 `ProtectionManager.remove_write_protection` 清除防寫保護。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 儲存產生的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="以 Aspose.Slides 建置" title="線上解除鎖定 PPT 檔案" description="免費的 Aspose.Slides Unlock 應用程式以 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh-hant/python-net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Unlock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何移除保護。
- 移除 PPT 檔案的密碼或防寫保護。
- 下載已解除鎖定的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援解除鎖定的格式" subTitle="使用 Python 移除其他支援的簡報格式的保護。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
