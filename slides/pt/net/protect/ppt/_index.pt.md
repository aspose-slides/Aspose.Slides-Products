---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger arquivos de apresentação PPT com .NET
url: /pt/net/protect/ppt/
description: Código-fonte C# para proteger apresentações PPT com senha.
keywords: Proteção contra gravação PPT, criptografar PPT, bloquear apresentação PPT, proteger PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloquear ou proteger com senha arquivos PPT usando C#" h2="Crie aplicativos .NET que criptografam apresentações e restringem modificações com APIs do lado do servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger uma apresentação PPT usando C#" variant="code" %}}

Com o [Aspose.Slides for .NET](/slides/pt/net/), você pode criptografar uma apresentação PPT ou restringir sua modificação com uma senha. Abrir uma apresentação criptografada com `ProtectionManager.Encrypt` exige a senha. Use `ProtectionManager.SetWriteProtection` para permitir abrir a apresentação e, ao mesmo tempo, restringir alterações.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Criptografar uma apresentação PPT usando C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Definir proteção contra gravação para uma apresentação PPT usando C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como proteger com senha uma apresentação PPT usando C#" intro="Siga estas etapas para proteger com senha uma apresentação PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPT com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Criptografe a apresentação com `ProtectionManager.Encrypt` ou restrinja alterações com `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo protegido com `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Criado com Aspose.Slides" title="Proteger arquivos PPT com senha online" description="O aplicativo gratuito Aspose.Slides Lock é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Lock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides protege apresentações antes de escrever código.
- Defina uma senha para abrir ou editar seu arquivo PPT.
- Baixe o arquivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com proteção" subTitle="Com C#, você também pode proteger os seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
