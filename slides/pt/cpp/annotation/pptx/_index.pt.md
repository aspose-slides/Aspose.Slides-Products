---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Remover anotações de PPTX usando C++
url: /pt/cpp/annotation/pptx/ 
description: Código-fonte C++ para remover anotações de apresentações PPTX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Remover comentários e autores de comentários de PPTX em C++" h2="Crie aplicativos C++ que manipulam comentários e autores em arquivos de apresentação com APIs do lado do servidor." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remover comentários de PPTX com C++" variant="code" %}}

Use o [Aspose.Slides for C++](/slides/pt/cpp/) para remover comentários e autores de comentários de apresentações PPTX. O exemplo abaixo limpa os comentários de cada autor de `get_CommentAuthors` e, em seguida, limpa a coleção de autores de comentários.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Excluir anotações de PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.pptx");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como remover comentários de PPTX com C++" intro="Siga estas etapas para remover comentários e autores de comentários de uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o Aspose.Slides for C++. Consulte [Instalação](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPTX com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os autores de comentários de `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Limpe os comentários de cada autor com `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Limpe a coleção de autores de comentários.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação atualizada com `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Criado com Aspose.Slides" title="Remover comentários de PPTX online" description="O aplicativo gratuito Aspose.Slides Annotation é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Annotation" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides remove comentários antes de escrever código.
- Remova todos os comentários do seu arquivo PPTX.
- Baixe o arquivo limpo.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com anotações" subTitle="Com C++, você também pode remover anotações de outros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
