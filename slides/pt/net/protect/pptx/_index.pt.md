---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger arquivos de apresentação PPTX com .NET
url: /pt/net/protect/pptx/
description: Código-fonte C# para proteger apresentações PPTX com senha.
keywords: Proteção contra gravação PPTX, criptografar PPTX, bloquear apresentação PPTX, proteger PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloquear ou proteger com senha arquivos PPTX usando C#" h2="Crie aplicativos .NET que criptografam apresentações e restringem modificações com APIs do lado do servidor." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger uma apresentação PPTX usando C#" variant="code" %}}

Com o [Aspose.Slides for .NET](/slides/pt/net/), você pode criptografar uma apresentação PPTX ou restringir sua modificação com uma senha. Abrir uma apresentação criptografada com `ProtectionManager.Encrypt` exige a senha. Use `ProtectionManager.SetWriteProtection` para permitir abrir a apresentação e, ao mesmo tempo, restringir alterações.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Criptografar uma apresentação PPTX usando C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Definir proteção contra gravação para uma apresentação PPTX usando C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como proteger com senha uma apresentação PPTX usando C#" intro="Siga estas etapas para proteger com senha uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPTX com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Criptografe a apresentação com `ProtectionManager.Encrypt` ou restrinja alterações com `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo protegido com `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Criado com Aspose.Slides" title="Proteger arquivos PPTX com senha online" description="O aplicativo gratuito Aspose.Slides Lock é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Lock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides protege apresentações antes de escrever código.
- Defina uma senha para abrir ou editar seu arquivo PPTX.
- Baixe o arquivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com proteção" subTitle="Com C#, você também pode proteger os seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
