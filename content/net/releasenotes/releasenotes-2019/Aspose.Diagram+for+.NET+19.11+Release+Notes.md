+++
title = "Aspose.Diagram for .NET 19.11 Release Notes" 
description = "" 
weight = 12118 
+++

Aspose.Diagram for .NET : Aspose.Diagram for .NET 19.11 Release Notes  

# Aspose.Diagram for .NET : Aspose.Diagram for .NET 19.11 Release Notes


This page contains release notes information for Aspose.Diagram for .NET 19.11.

## Improvements and Changes

{{< table style="table-striped" >}}
|Key|Summary|Category|
|:----|:----|:----|
|DIAGRAMNET-50004|Add support to [apply stylesheet](https://docs2.aspose.com/diagram/net/developerguide/workingwithpages/format+visio+pages) for full page|Enhancement|
|DIAGRAMNET-50576|Add support to dispose a Diagram class object|Enhancement|
|DIAGRAMNET-50098|Set page background color|Bug|
|DIAGRAMNET-51722|Diagram to SVG - output image has faults|Bug|
| DIAGRAMNET-51724|Errors in the Chrome console when viewing output SVG|Bug|
|DIAGRAMNET-51725|Retrieve z-index of shapes in Diagram|Bug|
|DIAGRAMNET-51726|Background Image Missing (PowerPoint is added in the VISIO) while removing unused master shapes and styles|Bug|
|DIAGRAMNET-51727|CheckBox (CheckBox Control) Missing while removing unused master shapes and styles|Bug|
|DIAGRAMNET-51728|Line Missing while removing unused master shapes and styles|Bug|
{{< /table >}}

### **Public API and Backwards Incompatible Changes**

The following is a list of any changes made to the public API such as added, renamed, removed or deprecated members as well as any non-backward compatible change made to Aspose.Diagram for .NET. If you have concerns about any change listed, please raise it on the Aspose.Diagram support forum.

### Added ApplyStyle in Page

Applies style to full page.

{{< code lang="cs" >}}
StyleSheet st = new StyleSheet();
st.ID = dia.StyleSheets.Count + 1;
Aspose.Diagram.Char ch = new Aspose.Diagram.Char();
ch.Color.Value = "#00ff00";
ch.IX = 0;
st.Chars.Add(ch);
st.Line.LineColor.Value = "#ff0000";
st.Line.LinePattern.Value = 1;
st.Line.LineWeight.Value = 0.01;
st.Fill.FillForegnd.Value = "#0000ff";
st.Fill.FillPattern.Value = 1;
st.Fill.ShdwPattern.Value = 0;
dia.StyleSheets.Add(st);
foreach (Shape shape in dia.Pages[0].Shapes)
{
     shape.Line.LinePattern.Value = 1;
     shape.Fill.FillPattern.Value = 1;
}
dia.Pages[0].ApplyStyle(st.ID, st.ID, st.ID);
{{< /code >}}

### Added Dispose in Diagram

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

diagram.Dispose();
