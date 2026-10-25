---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で POTM のメタデータを表示または編集
url: /ja/cpp/metadata/potm/
description: C++ で POTM のメタデータを表示、編集します。Aspose.Slides for C++ を使用して、プレゼンテーションの組み込みプロパティとカスタム プロパティを更新します。
keywords: POTM メタデータの編集, POTM メタデータの表示, POTM プロパティの編集, POTM プロパティの表示
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で POTM のメタデータを編集" h2="Aspose.Slides for C++ を使用して、プレゼンテーション ファイルの組み込みプロパティとカスタム プロパティを表示、更新します。" related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ で POTM のプロパティを変更" variant="code" %}}

Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしで POTM ファイルのメタデータを読み取り、更新できます。`Presentation::get_DocumentProperties` が返す [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) オブジェクトを使用して、`Author` や `Title` などの組み込みプロパティを変更したり、`idx_set`、`GetCustomPropertyName`、`RemoveCustomProperty` でカスタム プロパティを管理したりできます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM の組み込みプロパティの変更 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.potm");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.potm", SaveFormat::Potm);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM へのカスタム プロパティの追加 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.potm");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.potm", SaveFormat::Potm);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で POTM のメタデータを表示または編集する方法" intro="次の手順に従って、POTM のメタデータを表示または編集します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで POTM ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`get_DocumentProperties` で `DocumentProperties` オブジェクトを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Author` や `Title` などの組み込みプロパティを読み取るか更新します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`idx_set`、`GetCustomPropertyName`、`RemoveCustomProperty` でカスタム プロパティを追加、読み取り、削除します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Aspose.Slides で構築" title="POTM のメタデータをオンラインで表示、編集" description="無料の Aspose.Slides Metadata アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の POTM ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Metadata を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がプロパティをどう読み書きするかを確認できます。
- POTM ファイルの組み込みプロパティとカスタム プロパティを表示、編集できます。
- 更新したファイルを保存してダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他のサポートされているメタデータ形式" subTitle="C++ では次の形式のメタデータも管理できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
