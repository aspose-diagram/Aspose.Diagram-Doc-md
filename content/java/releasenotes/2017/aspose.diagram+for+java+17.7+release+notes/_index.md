---
title : "Aspose.Diagram for Java 17.7 Release Notes" 
description : "" 
weight : 12281 
toc : false
type: docs
url: /java/releasenotes/2017/aspose.diagram+for+java+17.7+release+notes/
---

# Aspose.Diagram for Java : Aspose.Diagram for Java 17.7 Release Notes


This page contains release notes for [Aspose.Diagram for Java 17.7](http://maven.aspose.com/repository/simple/ext-release-local/com/aspose/aspose-diagram/17.7/).

## Improvements and Changes

{{< table style="table-striped" >}}
|Key|Summary|Category|
|:----|:----|:----|
|DIAGRAMJAVA-50491|Cannot retrieve the new formulated shape height.|Enhancement|
|DIAGRAMJAVA-50510|VSD to SVG - incorrect fill color pattern in the shapes.|Enhancement|
|DIAGRAMJAVA-50483|Incomplete connection of shapes when saving a drawing in VSDX format.|Bug|
|DIAGRAMJAVA-50488|Additional text items are added when converting a VSD to SVG.|Bug|
|DIAGRAMJAVA-50490|Vertical border lines of predefined process box are thick when generating a VSDX drawing.|Bug |
|DIAGRAMJAVA-50495|Output VSDX - incorrect layout of connector line when adding text to shapes.|Bug|
|DIAGRAMJAVA-50496|Output VSDX - all connectors are drifted upward.|Bug|
|DIAGRAMJAVA-50498|Output VSDX - the vertical text display of shapes instead of the horizontal.|Bug|
|DIAGRAMJAVA-50506|An error occurred on loading a VDX drawing.|Bug|
|DIAGRAMJAVA-50508|Output VSDX - the text overflow when adding multi-line text.|Bug|
|DIAGRAMJAVA-50511|Output VSDX - misplaced text of the dynamic connector.|Bug|
|DIAGRAMJAVA-50512|Output VSDX - the connecting line passing through another shape|Bug|
|DIAGRAMJAVA-50513|Output VSDX - an additional line of connector inside the decision shape|Bug|
|DIAGRAMJAVA-50515|Output VSDX - the entire text of the shape is out of the border|Bug|
{{< /table >}}

### addComment Method is added in the Page class

An overloaded addComment method, exposed by the Page class takes a Shape class instance and text string of the comment.

{{< code lang="cs" >}}
// load diagram
Diagram diagram = new Diagram("c:\\temp\\Drawing1.vsdx");
// retrieve page by name
Page page = diagram.getPages().getPage("Page-1");
// retrieve shape by ID
Shape shape = page.getShapes().getShape(12);
page.addComment(shape, "Hello");
// save diagram
diagram.save("c:\\temp\\Drawing1.vsdx", SaveFileFormat.VSDX);
{{< /code >}}

### Usage Examples

Please check the list of help topics added in the Aspose.Diagram Wiki docs: 

1.  [Add a Shape-Level Comment in Visio Drawing](https://docs2.aspose.com/diagram/java/developerguide/working+with+comments#workingwithcomments-addashape-levelcommentinvisiodrawing)
