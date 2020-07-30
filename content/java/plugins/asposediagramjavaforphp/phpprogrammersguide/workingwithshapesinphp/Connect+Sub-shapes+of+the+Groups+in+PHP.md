+++
title = "Connect Sub-shapes of the Groups in PHP" 
description = "" 
weight = 20211 
+++

Aspose.Diagram for Java : Connect Sub-shapes of the Groups in PHP  

# Aspose.Diagram for Java : Connect Sub-shapes of the Groups in PHP


## Aspose.Diagram - Connect Sub-shapes of the Groups

To Connect Sub-shapes of the Groups using **Aspose.Diagram Java for PHP**, simply invoke **ConnectSubShapes** module. Here you can see example code.

**PHP Code**

{{< code lang="cs" >}}
# Create instance of Diagram
$diagram = new Diagram($dataDir."drawing.vsd");

# Access a particular page
$page = $diagram->getPages()->getPage("Flow 1");

# Set sub shape ids
$shape_from_id = 1;
$shape_to_id = 9;

# Initialize connector shape
$shape=new Shape();
$shape->getLine()->getEndArrow()->setValue(5);
$shape->getLine()->getLineWeight()->setValue(0.01388);

# Add shape
$connecter_id=$diagram->addShape($shape,"Dynamic connector",$page->getID());

# Connect sub-shapes
$connection_point_place = new ConnectionPointPlace();
$page->connectShapesViaConnector($shape_from_id,$connection_point_place->RIGHT,$shape_to_id,$connection_point_place->LEFT,$connecter_id);

# Save diagram
$saveFileFormat=new SaveFileFormat();
$diagram->save($dataDir."ConnectSubShapes.vdx",$saveFileFormat->VDX);
print "Connected sub-shapes of a group.".PHP_EOL;
{{< /code >}}

## Download Running Code

Download **Connect Sub-shapes of the Groups (Aspose.Diagram)** from any of the below mentioned social coding sites:

*   [GitHub](https://github.com/asposediagram/Aspose.Diagram-for-Java/blob/master/Plugins/Aspose_Diagram_Java_for_PHP/src/aspose/diagram/WorkingwithShapes/ConnectSubShapes.php)
*   [CodePlex](https://asposediagramjavaphp.codeplex.com/SourceControl/latest#src/aspose/diagram/WorkingwithShapes/ConnectSubShapes.php)
