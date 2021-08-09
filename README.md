# ASM.DEK.Printer.ProgrammingViewer

# Did not include the source code because the project can not be run on your local machine due to company protection

# Overview

Programming Viewer is standalone application used internally within ASM Assembly Systems for reading files with information about the current programs runned on the machine before it crashes. The information is stored within .xml files once read it connects the references and displays the information into an easy-to-understand UI.
You can choose whether to navigate to zipped file, or ProgramRepository folder.

# Software used

Language: C#

Project: WPF

Framework: .NET, Prism

IoC Container: Ninject

Design patterns: MVVM, Singleton, Factory, etc.

Advanced features: Reflection, Selection Tree, DataTemplates, etc.

# User Interface

# Initial UI

![](Images/Initialize.png)

# Browse to files

![](Images/Browse.png)

# Once files are read

![](Images/ProgramTree.png)

# Search data between different programs

![](Images/ProgramData.png)

# Activity and class diagram

![](Images/ActivityDiagram.png)

![](Images/GeneralClassDiagram.png)

# Some parts of the code

# Main Program class

![](Images/ProgramItemCode.png)

# Reflection

![](Images/Reflection.png)

# DataTemplates

![](Images/DataTemplates.png)

# Ninject Module

![](Images/NinjectModule.png)
