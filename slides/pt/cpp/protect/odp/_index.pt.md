---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger apresentações ODP usando C++
url: /pt/cpp/protect/odp/
description: Proteja apresentações ODP em C++. Use o Aspose.Slides for C++ para criptografar arquivos e definir proteção contra gravação.
keywords: Proteção contra gravação ODP, criptografar ODP, bloquear apresentação ODP, proteger ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloquear ou proteger com senha um ODP usando C++" h2="Use o Aspose.Slides for C++ para criptografar apresentações e definir proteção contra gravação sem o Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger uma apresentação ODP com C++" variant="code" %}}

O Aspose.Slides for C++ permite impedir que apresentações ODP sejam abertas ou modificadas. Use o objeto `ProtectionManager` da classe `Presentation` para criptografar um arquivo com `Encrypt` ou restringir a edição com `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Criptografar uma apresentação ODP usando C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Definir proteção contra gravação para uma apresentação ODP usando C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como proteger com senha um ODP com C++" intro="Siga estas etapas para proteger uma apresentação ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo ODP com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Proteja a apresentação com o objeto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `Encrypt` para proteção com senha ou `SetWriteProtection` para proteção contra gravação.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo protegido com `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Criado com Aspose.Slides" title="Proteger arquivos ODP com senha online" description="O aplicativo gratuito Aspose.Slides Lock é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Lock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides protege apresentações antes de escrever código.
- Defina uma senha para abrir ou editar seu arquivo ODP.
- Baixe o arquivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com proteção" subTitle="Com C++, você também pode proteger os seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
