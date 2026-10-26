---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tarjar apresentações PPT usando C++
url: /pt/cpp/redaction/ppt/
description: Tarje apresentações PPT em C++. Use o Aspose.Slides for C++ para localizar e substituir texto confidencial em arquivos de apresentação.
keywords: tarjar PPT, localizar e substituir texto em PPT, atualizar apresentação PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tarjar PPT usando C++" h2="Use o Aspose.Slides for C++ para localizar e substituir texto confidencial em arquivos de apresentação sem o Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tarjar uma apresentação PPT com C++" variant="code" %}}

O Aspose.Slides for C++ permite tarjar apresentações PPT substituindo o texto confidencial dos slides. Use `SlideUtil::FindAndReplaceText` com um objeto `Presentation` para pesquisar a apresentação e substituir o texto correspondente antes de salvar o arquivo atualizado.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tarjar uma apresentação PPT usando C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como tarjar PPT com C++" intro="Siga estas etapas para tarjar uma apresentação PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPT com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use o método [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) para localizar e substituir texto confidencial.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo tarjado com `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Criado com Aspose.Slides" title="Tarjar arquivos PPT online" description="O aplicativo gratuito Aspose.Slides Redaction é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Redaction" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza e substitui texto antes de escrever código.
- Localize e substitua texto no seu arquivo PPT, inclusive com expressões regulares.
- Baixe o arquivo tarjado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com tarjamento" subTitle="Com C++, você também pode tarjar os seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
