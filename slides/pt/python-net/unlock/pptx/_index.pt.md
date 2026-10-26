---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear apresentações PPTX com Python
url: /pt/python-net/unlock/pptx/
description: Remova a criptografia e a proteção contra gravação de apresentações PPTX com Python.
keywords: desbloquear PPTX, remover senha de PPTX, remover criptografia de PPTX, remover proteção contra gravação de PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear apresentações PPTX com Python" h2="Crie aplicativos Python que removem senhas de abertura e a proteção contra gravação de apresentações PPTX com o Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remover criptografia e proteção contra gravação de PPTX com Python" variant="code" %}}

Com o [Aspose.Slides for Python via .NET](/slides/pt/python-net/), você pode remover a criptografia que exige uma senha para abrir uma apresentação PPTX ou desativar sua proteção contra gravação. Para abrir um arquivo criptografado, informe a senha atual por meio de `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a criptografia de uma apresentação PPTX – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a proteção contra gravação de uma apresentação PPTX – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como remover a proteção de PPTX com Python" intro="Siga estas etapas para remover a proteção de uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Para um arquivo PPTX criptografado, defina a senha atual em `LoadOptions` e, em seguida, abra o arquivo com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `ProtectionManager.remove_encryption` para remover a senha de abertura ou `ProtectionManager.remove_write_protection` para desativar a proteção contra gravação.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação resultante com `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Criado com Aspose.Slides" title="Desbloquear arquivos PPTX online" description="O aplicativo gratuito Aspose.Slides Unlock é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Unlock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides remove a proteção antes de escrever código.
- Remova a senha ou a proteção contra gravação do seu arquivo PPTX.
- Baixe o arquivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com desbloqueio" subTitle="Use Python para remover a proteção de outros formatos de apresentação compatíveis." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
