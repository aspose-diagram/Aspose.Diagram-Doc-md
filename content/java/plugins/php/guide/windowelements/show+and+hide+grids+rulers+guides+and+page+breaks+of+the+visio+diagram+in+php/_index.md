---
title : "Show and Hide Grids Rulers Guides and Page Breaks of the Visio Diagram in PHP" 
description : "" 
weight : 20240 
toc : false
type: docs
url: /java/plugins/php/guide/windowelements/show+and+hide+grids+rulers+guides+and+page+breaks+of+the+visio+diagram+in+php/
---

# Aspose.Diagram for Java : Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram in PHP


## Aspose.Diagram - Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram

To Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram using **Aspose.Diagram Java for PHP**, simply invoke **ShowHideProperties** module. Here you can see example code.

**PHP Code**

{{< code lang="cs" >}}
# Create instance of Diagram
$diagram =new Diagram($dataDir."Drawing.vsd");

# get window object by index
$window=$diagram->getWindows()->get(0);

# set visibility of grid
$window->setShowGrid(1);

# set visibility of guides
$window->setShowGuides(1);

# set visibility of rulers
$window->setShowRulers(1);

# set visibility of page breaks
$window->setShowPageBreaks(1);

# save in any supported format
$saveFileFormat=new SaveFileFormat();
$diagram->save($dataDir."ShowHideProperties.vdx", $saveFileFormat->VDX);
print "Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram.".PHP_EOL;
{{< /code >}}

## Download Running Code

Download **Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram (Aspose.Diagram)** from any of the below mentioned social coding sites:

*   [GitHub](https://github.com/asposediagram/Aspose.Diagram-for-Java/blob/master/Plugins/Aspose_Diagram_Java_for_PHP/src/aspose/diagram/WorkingwithWindowElements/ShowHideProperties.php)
*   [CodePlex](https://asposediagramjavaphp.codeplex.com/SourceControl/latest#src/aspose/diagram/WorkingwithWindowElements/ShowHideProperties.php)
