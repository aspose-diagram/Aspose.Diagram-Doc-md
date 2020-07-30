+++
title = "Printing a Diagram in VSTO and Aspose.Diagram" 
description = "" 
weight = 16104 
+++

Aspose.Diagram for .NET : Printing a Diagram in VSTO and Aspose.Diagram  

# Aspose.Diagram for .NET : Printing a Diagram in VSTO and Aspose.Diagram


## VSTO

Below is the code to show how to print diagram:

{{< code lang="cs" >}}
  Application.ActiveDocument.Print();
{{< /code >}}

## Aspose.Diagram

Printing of the diagram to the **default printer** is quite simple in Aspose.Diagram for .NET. Perform the following steps in order to print the diagram to default printer:

*   Create an instance of Diagram class to load a diagram that is to be printed
*   Call the Print method with no parameters as exposed by the Diagram object

Printing of the diagram to the **specific printer** requires the name of the printer as parameter to the Print method of the Diagram. Perform the following steps in order to print the diagram to the desired printer:

*   Create an instance of Diagram class to load a diagram that is to be printed
*   Call the Print method of the Diagram class with printer name as string parameter to the Print method

Below is the code of using default and specific printer:

{{< code lang="cs" >}}
 string FilePath = "demo.vsd";
 //Load the diagram
 Diagram diagram = new Diagram(FilePath);

 //Call the print method to print whole Diagram to the default printer
 diagram.Print();

 //Call the print method to print whole Diagram to the desired printer
 diagram.Print("LaserJet1100");

 PrinterSettings settings = new PrinterSettings();
 settings.PrinterName = "LaserJet1100";
 //Call the print method to print whole Diagram to the desired printer and set document name in print job
 diagram.Print(settings, "Job name while printing with Aspose.Diagram");

{{< /code >}}

## Download Sample Code

*   [Codeplex](https://asposevsto.codeplex.com/releases/view/617141)
*   [Github](https://github.com/aspose-diagram/Aspose.Diagram-for-.NET/releases/tag/AsposeDiagramVsVSTOv1.1)
*   [Code.MSDN](https://code.msdn.microsoft.com/AsposeDiagram-Vs-VSTO-fb086932)

## Download Running Code

*   [Codeplex](https://asposevsto.codeplex.com/SourceControl/latest#Aspose.Diagram Vs VSTO Visio/Printing a Diagram/)
*   [Github](https://github.com/aspose-diagram/Aspose.Diagram-for-.NET/tree/master/Plugins/Aspose.Diagram%20Vs%20VSTO%20Visio/Code%20Comparison%20of%20Common%20Features/Printing%20a%20Diagram)
*   [Code.MSDN](https://code.msdn.microsoft.com/AsposeDiagram-Vs-VSTO-fb086932/view/SourceCode#content)
