+++
title = "Working with Window Elements" 
description = "" 
weight = 8046 
+++

Aspose.Diagram for Java : Working with Window Elements  

# Aspose.Diagram for Java : Working with Window Elements


{{< panel title="Contents Summary" style="primary" >}}
*   1 [Retrieve Window Elements from the Visio Drawing](#WorkingwithWindowElements-RetrieveWindowElementsfromtheVisioDrawing)
    *   1.1 [Retrieve Window Elements Programming Sample](#WorkingwithWindowElements-RetrieveWindowElementsProgrammingSample)
*   2 [Add Window Element to the Visio Diagram](#WorkingwithWindowElements-AddWindowElementtotheVisioDiagram)
    *   2.1 [Add Window Element Programming Sample](#WorkingwithWindowElements-AddWindowElementProgrammingSample)
*   3 [Add Support of Dynamic Grids and Connection Points](#WorkingwithWindowElements-AddSupportofDynamicGridsandConnectionPoints)
    *   3.1 [Support of Dynamic Grids and Connection Points in the Visio Drawings](#WorkingwithWindowElements-SupportofDynamicGridsandConnectionPointsintheVisioDrawings)
        *   3.1.1 [Add Support Programming Sample](#WorkingwithWindowElements-AddSupportProgrammingSample)
*   4 [Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram](#WorkingwithWindowElements-ShowandHideGrids,Rulers,GuidesandPageBreaksoftheVisioDiagram)
    *   4.1 [Programming Sample](#WorkingwithWindowElements-ProgrammingSample)
{{< /panel >}}
 

 

## Retrieve Window Elements from the Visio Drawing

The main Visio application window can contain any open Visio files, the same as modern web browsers allow for multiple tabbed web pages in one window. Developers can retrieve Window objects using [Aspose.Diagram for Java API](http://www.aspose.com/java/diagram-component.aspx).

The [`WindowCollection`](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/windowcollection) object represents a list of [Window](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/window) objects available in the drawing. The `Windows` property, exposed by the `Diagram` class, supports a collection of `Aspose.Diagram.Window` objects. This property can be used to retrieve the window information that is, the Window ID, type, height, width and state.

**A console window showing the output from the code.**  
![](http://i.imgur.com/zduARGh.png)

### Retrieve Window Elements Programming Sample

## Add Window Element to the Visio Diagram

The main Visio application window can contain any open Visio files, the same as modern web browsers allow for multiple tabbed web pages in one window. Developers can now add a new Window object in a Microsoft Visio instance using [Aspose.Diagram for Java API](http://www.aspose.com/java/diagram-component.aspx).

The [Window](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/window) object represents an open window in a Microsoft Visio instance. The [Add](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/windowcollection/methods/add(com.aspose.diagram.Window)/) method, exposed by the [WindowCollection](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/windowcollection) class, allows to add a new `Window` object.

### Add Window Element Programming Sample

## Add Support of Dynamic Grids and Connection Points

The dynamic grid helps you position new shapes vertically and horizontally relative to the shapes you've already placed in the drawing. Regarding the connection points, once marked as checked, will help us to see the connection points when we are in the process of connecting to them. We can achieve both options using [Aspose.Diagram for Java API](http://www.aspose.com/java/diagram-component.aspx).

### Support of Dynamic Grids and Connection Points in the Visio Drawings

The [`Window`](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/window) class offers `DynamicGridEnabled` and `ShowConnectionPoints` properties. These properties can be used to apply settings to support dynamic grids and show connection points options.

**A Visio application showing the options in Visio.**  
![](http://i.imgur.com/bxsJIwF.png)

#### Add Support Programming Sample

## Show and Hide Grids, Rulers, Guides and Page Breaks of the Visio Diagram

Microsoft Office Visio has a pair of rulers, a grid, and two types of guides and page breaks flag to see what will be printed on each page. Developers can apply these settings using [Aspose.Diagram for Java API](http://www.aspose.com/java/diagram-component.aspx). The settings apply globally to a single page.

The [Window](http://www.aspose.com/api/java/diagram/com.aspose.diagram/classes/window) class offers `ShowGrid`, `ShowGuides`, `ShowRulers` and `ShowPageBreaks` properties. These properties can be used to apply settings to show and hide grids, guides, rulers and page breaks.

**A Visio application showing the options in Visio.**  
![](http://i.imgur.com/E0pvXbP.png)

### Programming Sample

## Attachments:

![](https://docs2.aspose.com/diagram/java/images/icons/bullet_blue.gif) [Support of Dynamic Grids and Connection Points-001.png](https://docs2.aspose.com/diagram/java/attachments/18612587/18809077.png) (image/png)  
![](https://docs2.aspose.com/diagram/java/images/icons/bullet_blue.gif) [Window Elements from the Visio Drawing-001.png](https://docs2.aspose.com/diagram/java/attachments/18612587/18809091.png) (image/png)  
![](https://docs2.aspose.com/diagram/java/images/icons/bullet_blue.gif) [Show and Hide Grids, Rulers, Guides and Page Breaks-Java-001.png](https://docs2.aspose.com/diagram/java/attachments/18612587/18809090.png) (image/png)  
