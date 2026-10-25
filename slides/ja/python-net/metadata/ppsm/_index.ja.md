---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PPSM のメタデータを表示または編集
url: /ja/python-net/metadata/ppsm/
description: Python で PPSM ファイルの組み込みメタデータ プロパティとカスタム メタデータ プロパティを表示、編集します。
keywords: PPSM メタデータの編集, PPSM メタデータの表示, PPSM プロパティの編集, PPSM プロパティの表示
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PPSM のメタデータを表示、編集" h2="Aspose.Slides を使用して、プレゼンテーションの組み込みプロパティとカスタム プロパティを読み取り、変更する Python アプリを構築します。" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PPSM のメタデータを表示、変更" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/ja/python-net/) を使用すると、PPSM プレゼンテーションの組み込みメタデータを読み取って更新し、カスタム ドキュメント プロパティを追加、更新、削除できます。`Presentation.document_properties` から [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) オブジェクトにアクセスして変更し、プレゼンテーションを PPSM 形式で保存します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM の組み込みプロパティの更新 - Python" >}}
```python
with slides.Presentation("presentation.ppsm") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.ppsm", slides.export.SaveFormat.PPSM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM のカスタム プロパティの追加と削除 - Python" >}}
```python
with slides.Presentation("presentation.ppsm") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.ppsm", slides.export.SaveFormat.PPSM)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で PPSM のメタデータを編集する方法" intro="次の手順に従って、PPSM ファイルのメタデータを編集します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で PPSM ファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.document_properties` から `IDocumentProperties` オブジェクトにアクセスします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}組み込みプロパティを更新するか、カスタム プロパティには `set_custom_property_value` と `remove_custom_property` を使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.save` と `SaveFormat.PPSM` でプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides で構築" title="PPSM のメタデータをオンラインで表示、編集" description="無料の Aspose.Slides Metadata アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PPSM ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Metadata を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がプロパティをどう読み書きするかを確認できます。
- PPSM ファイルの組み込みプロパティとカスタム プロパティを表示、編集できます。
- 更新したファイルを保存してダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされているメタデータ形式" subTitle="Python では、サポートされている他のプレゼンテーション形式のメタデータも管理できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
