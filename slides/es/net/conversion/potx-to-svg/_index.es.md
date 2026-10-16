---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convierta POTX a SVG a través de C#
weight: 7010
url: /es/net/conversion/potx-to-svg/ 
description: Código de muestra para la conversión de POTX a SVG C#. Utilice el código de ejemplo API para la conversión de archivos POTX por lotes a SVG dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convierta POTX a SVG a través de C#" h2="Exporte archivos POTX de PowerPoint® a SVG en plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cómo convertir POTX a SVG usando C#" %}}

Para convertir POTX a SVG, usaremos
 [Aspose.Slides para .NET](https://products.aspose.com/slides/es/net)
 API, que es una API de manipulación y conversión de documentos rica en funciones, potente y fácil de usar para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 administrador de paquetes, busque
 Aspose.Diapositivas
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando de la consola del Administrador de paquetes" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de ejemplo muestra la conversión de POTX a SVG C#" >}}
```cs
using (Presentation pres = new Presentation("template.potx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];

        using (FileStream fileStream = new FileStream($"slide-{index}.svg", FileMode.Create, FileAccess.Write))
        {
            slide.WriteAsSvg(fileStream);   
        }
    }
} 
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Pasos para convertir POTX a SVG a través de C#" intro="Los desarrolladores de .NET pueden cargar y convertir fácilmente archivos POTX a SVG con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo POTX con una instancia de la clase Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método Guardar mientras especifica la ruta del archivo de salida y SaveFormat.Svg como parámetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo SVG se guardará en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Antes de ejecutar el código fuente de ejemplo de conversión de .NET, asegúrese de cumplir los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con las plataformas .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Entorno de desarrollo como Microsoft Visual Studio.
- Aspose.Slides para .NET DLL a la que se hace referencia en su proyecto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplicación gratuita para convertir POTX a SVG"
  description="[Pruebe nuestra aplicación gratuita Editor](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir POTX a muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-bmp/" name="POTX TO BMP" description="Imagen de mapa de bits" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-emf/" name="POTX TO EMF" description="Formato de metarchivo mejorado" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-gif/" name="POTX TO GIF" description="Formato de intercambio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-html/" name="POTX TO HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="Imagen JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-odp/" name="POTX TO ODP" description="Formato de presentación de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-otp/" name="POTX TO OTP" description="Formato estándar de OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-pdf/" name="POTX TO PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-png/" name="POTX TO PNG" description="Gráficos de red portátiles" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-pot/" name="POTX TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-potm/" name="POTX TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-pps/" name="POTX TO PPS" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Archivo de presentación habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Formato de presentación XML abierto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-swf/" name="POTX TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Formato de imagen etiquetada" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/conversion/potx-to-xps/" name="POTX TO XPS" description="Especificaciones de papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
