---
title: Converter OTP para PNG em Python
weight: 530
url: /pt/python-net/conversion/otp-to-png/ 
keywords: "Convert, PowerPoint, OTP, PNG, Presentation, Python"
description: Código de exemplo para conversão de OTP para PNG Python. Use a API Python do PowerPoint para arquivos OTP de conversão em lote para arquivos PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter OTP para PNG em Python" h2="Poderosa biblioteca Python do PowerPoint para converter OTP para PNG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converter OTP para PNG em Python" %}}

Precisa converter arquivos OTP para PNG programaticamente? Usando [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/pt/python-net/) qualquer desenvolvedor pode converter o formato OTP para PNG com apenas algumas linhas de código Python.

Como uma API de processamento de apresentação moderna, o Aspose.Slides for Python cria PNG a partir de OTP rapidamente. Teste a qualidade da conversão de OTP para PNG diretamente no seu [navegador](https://products.aspose.app/slides/conversion/ppt-to-png). A biblioteca Aspose PowerPoint PPTX permite converter arquivos OTP para muitos formatos populares.

Você pode instalar a biblioteca de [PyPI](https://pypi.org/project/Aspose.Slides/) usando o seguinte comando pip:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Como converter OTP para PNG em Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter um arquivo OTP para PNG usando Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar arquivo OTP com uma instância da classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.PNG como parâmetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
O arquivo OTP será salvo no caminho especificado
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte da amostra de conversão do Python, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- SO baseado em Microsoft Windows ou Linux (veja [mais](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ou posterior
- Aspose.Slides para Python referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de exemplo mostra a conversão de OTP para PNG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.otp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Salvar OTP como PNG em Python" %}}
Use o aplicativo gratuito para ver uma demonstração do processo de conversão de OTP para PNG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="otp-to-png"
        sectionTitle="Aplicativo gratuito para converter OTP para PNG" 
        sectionDescription="[Experimente nosso aplicativo gratuito para converter PPT para PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter OTP para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-bmp/" name="OTP TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-emf/" name="OTP TO EMF" description="Formato de metarquivo aprimorado" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-fodp/" name="OTP TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-gif/" name="OTP TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-html/" name="OTP TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-jpg/" name="OTP TO JPG" description="Imagem JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-odp/" name="OTP TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-pdf/" name="OTP TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-pot/" name="OTP TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-potm/" name="OTP TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-potx/" name="OTP TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-pps/" name="OTP TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Apresentação de slides habilitada para macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-svg/" name="OTP TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-swf/" name="OTP TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/otp-to-xps/" name="OTP TO XPS" description="Especificações do papel XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}