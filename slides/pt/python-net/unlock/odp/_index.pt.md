---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear apresentações ODP com Python
url: /pt/python-net/unlock/odp/
description: Remova a criptografia e a proteção contra gravação de apresentações ODP com Python.
keywords: desbloquear ODP, remover senha de ODP, remover criptografia de ODP, remover proteção contra gravação de ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear apresentações ODP com Python" h2="Crie aplicativos Python que removem senhas de abertura e a proteção contra gravação de apresentações ODP com o Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remover criptografia e proteção contra gravação de ODP com Python" variant="code" %}}

Com o [Aspose.Slides for Python via .NET](/slides/pt/python-net/), você pode remover a criptografia que exige uma senha para abrir uma apresentação ODP ou desativar sua proteção contra gravação. Para abrir um arquivo criptografado, informe a senha atual por meio de `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a criptografia de uma apresentação ODP – Python" >}}
```python
load_options = slides.LoadOptions()
load_options.password = "current_password"

with slides.Presentation("encrypted-presentation.odp", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("decrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a proteção contra gravação de uma apresentação ODP – Python" >}}
```python
with slides.Presentation("write-protected-presentation.odp") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como remover a proteção de ODP com Python" intro="Siga estas etapas para remover a proteção de uma apresentação ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Para um arquivo ODP criptografado, defina a senha atual em `LoadOptions` e, em seguida, abra o arquivo com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `ProtectionManager.remove_encryption` para remover a senha de abertura ou `ProtectionManager.remove_write_protection` para desativar a proteção contra gravação.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação resultante com `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Criado com Aspose.Slides" title="Desbloquear arquivos ODP online" description="O aplicativo gratuito Aspose.Slides Unlock é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Unlock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides remove a proteção antes de escrever código.
- Remova a senha ou a proteção contra gravação do seu arquivo ODP.
- Baixe o arquivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com desbloqueio" subTitle="Use Python para remover a proteção de outros formatos de apresentação compatíveis." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
