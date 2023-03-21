---
title: C++を使用したさまざまな形式へのMicrosoftPowerPointプレゼンテーションの変換
url: /ja/cpp/conversion/
description: Microsoft PowerPointスライドを、C ++ベースのアプリケーション内でHTML、PDF、および画像形式を含む複数のファイルに変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup>C++によるPowerPointプレゼンテーション変換" h2="スライドを画像、HTML、PDF、その他の形式に変換するためのさまざまな変換シナリオのC++サンプルコード。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Microsoft<sup>®</sup>PowerPoint形式の変換プロセスは、C++PowerPointライブラリを使用してプロセスを自動化するのが簡単で簡単です。開発者は、関連するソースコードを拡張し、アプリケーション内に統合できます。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointフォーマットの相互変換" %}}
PPT、PPTXを含むMicrosoft<sup>®</sup> PowerPointドキュメントの相互変換は、プログラムで2行のコードです。 [プレゼンテーションクラス]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation）を使用してファイルを読み込み、[保存メソッド]（https://apireference.aspose.com/slides）を呼び出します/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e）出力ファイルとSaveFormat.OutputFormatsをパラメーターとして持ちます。

{{% blocks/products/pf/feature-page-code h3="C++変換コード" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPointファイルをPDFに変換する" %}}

Microsoft<sup>®</sup>PowerPointをPDFに変換することは、PDFドキュメントが大量に共有されるため、一般的なシナリオです。プログラマーはそれを自動化し、[PdfOptionsクラス]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options）を使用して関連するPDF変換設定を設定できます。テキスト圧縮レベル、JPEG品質[JpegQuality]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861）、PDFコンプライアンスレベル[コンプライアンス]などの特定の設定のいくつか（https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f）、非表示のスライドを変換する[ShowHiddenSlides]（https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23）、選択したスライドとロックされた[Password]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7） 。

{{% blocks/products/pf/feature-page-code h3="C++PowerPointからPDFへの変換コード" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointスライドを画像として保存" %}}
プレゼンテーションコンテンツをWebに表示する場合は常に、ファイルをHTMLまたは画像JPG、TIFF、PNGなどとしてレンダリングする必要があります。スライドを画像として変換するプロセスは簡単です。 [get_Slides（）]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c）を使用してすべてのスライドを取得し、各スライドを1つずつ繰り返します。各反復中に、スライド画像に[ISlide-> GetThumbnail]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783）を使用して、必要な画像形式で保存します。 

{{% blocks/products/pf/feature-page-code h3="C++PowerPointから画像への変換" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}