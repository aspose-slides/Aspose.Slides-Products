---
title: Konvertieren Sie ODP in BMP in Python
url: /de/python-java/conversion/odp-to-bmp/
keywords: Konvertierung von Python-Präsentationen, Konvertierung von Präsentationen in Python, Python für Präsentationen, Aspose.Slides Python, Konvertierung von ODP nach BMP, Python-Präsentationsbibliothek
description: Konvertieren Sie ODP in BMP in Python. Verwenden Sie die Python-Bibliotheks-API, um ODP-Dateien in BMP zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie ODP mühelos in BMP mit Python: Aspose.Slides zur Rettung!" h2="Hauchen Sie Ihren Präsentationen mit Python neues Leben ein. Unser Leitfaden führt Sie durch die Konvertierung vorhandener PowerPoint-Folien in ansprechende Python-Präsentationen." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie ODP in BMP in Python" %}}

Sind Sie es leid, sich mit komplexer Präsentationssoftware auseinanderzusetzen? Suchen Sie nicht weiter als nach [**Aspose.Slides für Python über Java**](https://products.aspose.com/slides/de/python-java/)! Mit dieser leistungsstarken Bibliothek können Sie problemlos Präsentationen erstellen, bearbeiten und in verschiedene Formate konvertieren. Müssen Sie von ODP zu BMP wechseln? Aspose.Slides macht es zum Kinderspiel und erfordert nur ein paar Zeilen Python-Code.

Als hochmoderne Dokumentenverarbeitungs-API bietet **Aspose.Slides für Python über Java** blitzschnelle Konvertierungsgeschwindigkeiten und gewährleistet eine schnelle Umwandlung Ihrer ODP-Präsentationen in das BMP-Format. Vergessen Sie die Einschränkungen herkömmlicher Tools – Aspose.Slides bietet Ihnen die Flexibilität, Präsentationen nicht nur von ODP in BMP, sondern auch in eine Vielzahl anderer Formate zu konvertieren, sodass Sie Ihre Präsentationen perfekt an jede Situation anpassen können.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie ODP mit Python in BMP" %}}
Um das ODP in BMP zu konvertieren, müssen Sie eine Präsentation aus der ODP-Datei erstellen und diese als BMP speichern.

{{% blocks/products/pf/agp/code-block title="Python-Tutorial zum Konvertieren von ODP in BMP" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.odp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python-Tutorial. So konvertieren Sie ODP in BMP mit Aspose.Slides für Python über die Java-API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Um ODP in BMP mit Aspose.Slides für Python über Java zu konvertieren, müssen Sie das Paket in Ihr Python-Skript importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Python über Java**](https://products.aspose.com/slides/de/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Python-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien ODP in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als BMP-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie ODP in andere unterstützte Formate" subTitle="Sie können ODP auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-png/" name="ODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/python-java/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}