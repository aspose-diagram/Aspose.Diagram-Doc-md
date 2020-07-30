+++
title = "Retrieve All Layers from the Visio Diagram in PHP" 
description = "" 
weight = 20201 
+++

Aspose.Diagram for Java : Retrieve All Layers from the Visio Diagram in PHP  

# Aspose.Diagram for Java : Retrieve All Layers from the Visio Diagram in PHP


## Aspose.Diagram - Retrieve All Layers

To Retrieve All Layers using **Aspose.Diagram Java for PHP**, simply invoke **GetAllLayers** module. Here you can see example code.

**PHP Code**

{{< code lang="cs" >}}
# Create instance of Diagram
$diagram = new Diagram($dataDir . "Drawing.vsd");

# get Visio page
$page=$diagram->getPages()->getPage(0);

$layers=$page->getPageSheet()->getLayers();

$i = 0;
while ($i<(int)(string)$layers->getCount()) {
$layer=$layers->get($i);
print "Name: " . (string)$layer->getName()->getValue();
print "Visibility: " . (string)$layer->getVisible()->getValue();
print "Status: " . (string)$layer->getStatus()->getValue();
$i += 1;
}
{{< /code >}}

## Download Running Code

Download **Retrieve All Layers from the Visio Diagram (Aspose.Diagram)** from any of the below mentioned social coding sites:

*   [GitHub](https://github.com/asposediagram/Aspose.Diagram-for-Java/blob/master/Plugins/Aspose_Diagram_Java_for_PHP/src/aspose/diagram/WorkingwithLayers/GetAllLayers.php)
*   [CodePlex](https://asposediagramjavaphp.codeplex.com/SourceControl/latest#src/aspose/diagram/WorkingwithLayers/GetAllLayers.php)
