---
title: "New Toolbar Resource Dialog Box (C++)"
ms.date: "11/04/2016"
f1_keywords: ["vc.editors.newtoolbarresource"]
helpviewer_keywords: ["New Toolbar Resource dialog box [C++]"]
ms.assetid: 52dd01ad-e748-4ab2-b3eb-59f5df990ca6
---
# New Toolbar Resource Dialog Box (C++)

The **New Toolbar Resource** dialog box allows you to specify the width and height of the buttons you are adding to a toolbar resource in a C++ project. The default is 16 × 15 pixels.

A bitmap that is used to create a toolbar has a maximum width of 2048. So if you set the **Button Width** to 512, you can only have four buttons. If you set the width to 513, you can only have three buttons.

### Button Width

Provides a space for you to enter the width for the toolbar buttons you are converting from a bitmap resource to a toolbar resource. The images are cropped to the width and height specified, and the colors are adjusted to use standard toolbar colors (16 colors).

### Button Height

Provides a space for you to enter the height for the toolbar buttons you are converting from a bitmap resource to a toolbar resource. The images are cropped to the width and height specified, and the colors are adjusted to use standard toolbar colors (16 colors).

For information on adding resources to managed projects, please see [Resources in Desktop Apps](/dotnet/framework/resources/index) in the *.NET Framework Developer's Guide*. For information on manually adding resource files to managed projects, accessing resources, displaying static resources, and assigning resource strings to properties, see [Creating Resource Files for Desktop Apps](/dotnet/framework/resources/creating-resource-files-for-desktop-apps). For information on globalization and localization of resources in managed apps, see [Globalizing and Localizing .NET Framework Applications](/dotnet/standard/globalization-localization/index).

## Requirements

MFC or ATL

## See Also

[Toolbar Button Properties](../windows/toolbar-button-properties.md)<br/>
[Converting Bitmaps to Toolbars](../windows/converting-bitmaps-to-toolbars.md)<br/>
[Toolbar Editor](../windows/toolbar-editor.md)