---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPSM para JPG em Python
weight: 1820
url: /pt/python-net/conversion/ppsm-to-jpg/ 
keywords: "Convert, PowerPoint, PPSM, JPG, Presentation, Python"
description: Código de exemplo para conversão de PPSM para JPG Python. Use a API Python do PowerPoint para arquivos PPSM de conversão em lote para arquivos JPG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPSM para JPG em Python" h2="Poderosa biblioteca Python do PowerPoint para converter PPSM para JPG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PPSM para JPG em Python" %}}

Precisa converter arquivos PPSM para JPG programaticamente? Usando [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/pt/python-net/) qualquer desenvolvedor pode converter o formato PPSM para JPG com apenas algumas linhas de código Python.

Como uma API de processamento de apresentação moderna, o Aspose.Slides for Python cria JPG a partir do PPSM rapidamente. Teste a qualidade da conversão de PPSM para JPG diretamente no seu [navegador](https://products.aspose.app/slides/conversion/ppt-to-jpg). A biblioteca Aspose PowerPoint PPTX permite converter arquivos PPSM para muitos formatos populares.

Você pode instalar a biblioteca de [PyPI](https://pypi.org/project/Aspose.Slides/) usando o seguinte comando pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salvar PPSM como JPG em Python" %}}

Use o aplicativo gratuito para ver uma demonstração do processo de conversão de PPSM para JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de amostra mostra a conversão de PPSM para JPG Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PPSM para JPG em Python" intro="Estas são as etapas para converter um arquivo PPSM em JPG usando Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregar arquivo PPSM com uma instância da classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.JPG como parâmetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}O arquivo PPSM será salvo no caminho especificado{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Antes de executar o código-fonte da amostra de conversão do Python, verifique se você tem os seguintes pré-requisitos." %}}

- SO baseado em Microsoft Windows ou Linux (veja [mais](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ou posterior
- Aspose.Slides para Python referenciado em seu projeto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplicativo gratuito para converter PPSM para JPG"
  description="[Experimente nosso aplicativo gratuito para converter PPT para JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPSM para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Formato de metarquivo aprimorado" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Formato padrão do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Gráficos Portáteis de Rede" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
