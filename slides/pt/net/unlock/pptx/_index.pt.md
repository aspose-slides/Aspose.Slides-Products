---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear arquivos de apresentação PPTX com .NET
url: /pt/net/unlock/pptx/
description: Código-fonte C# para remover a proteção por senha de apresentações PPTX.
keywords: Remover proteção contra gravação PPTX, descriptografar PPTX, desbloquear apresentação PPTX, desproteger PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear arquivos PPTX usando C#" h2="Crie aplicativos .NET que removem a criptografia e a proteção contra gravação de apresentações com APIs do lado do servidor." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remover a proteção de uma apresentação PPTX usando C#" variant="code" %}}

Com o [Aspose.Slides for .NET](/slides/pt/net/), você pode remover a criptografia ou a proteção contra gravação de uma apresentação PPTX. Para remover a criptografia, carregue a apresentação com a senha correta e chame `ProtectionManager.RemoveEncryption`. Para remover a proteção contra gravação, chame `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a criptografia de uma apresentação PPTX usando C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a proteção contra gravação de uma apresentação PPTX usando C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como remover a proteção de uma apresentação PPTX usando C#" intro="Siga estas etapas para remover a proteção de uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPTX com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Para um arquivo criptografado, informe a senha por meio de `LoadOptions.Password` antes de carregá-lo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `ProtectionManager.RemoveEncryption` ou `ProtectionManager.RemoveWriteProtection`, de acordo com a proteção aplicada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação desbloqueada com `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Criado com Aspose.Slides" title="Desbloquear arquivos PPTX online" description="O aplicativo gratuito Aspose.Slides Unlock é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Unlock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides remove a proteção antes de escrever código.
- Remova a senha ou a proteção contra gravação do seu arquivo PPTX.
- Baixe o arquivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com desbloqueio" subTitle="Com C#, você também pode remover a proteção dos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
