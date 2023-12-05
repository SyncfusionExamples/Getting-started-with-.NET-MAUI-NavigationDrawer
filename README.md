## Getting started with NavigationDrawer control

This section explains how to add the `.NET MAUI NavigationDrawer control.` This section covers only the basic features needed to get started with Syncfusion .NET MAUI NavigationDrawer.

### Adding the .NET MAUI NavigationDrawer control

Step 1: Add the NuGet to the project and add the namespace as shown in the following code sample:

**[XAML]**
```
    xmlns:navigationdrawer="clr-namespace:Syncfusion.Maui.NavigationDrawer;assembly=Syncfusion.Maui.NavigationDrawer"
```	

**[C#]**
```
    using Syncfusion.Maui.NavigationDrawer;
```

Step 2: Set the NavigationDrawer control to content in `ContentPage.`

**[XAML]**
```
<navigationdrawer:SfNavigationDrawer x:Name="navigationDrawer">
    <navigationdrawer:SfNavigationDrawer.ContentView>
        <Grid/>
    </navigationdrawer:SfNavigationDrawer.ContentView>
</navigationdrawer:SfNavigationDrawer>
```	

**[C#]**
```
          
SfNavigationDrawer navigationDrawer = new SfNavigationDrawer();
Grid grid = new Grid();
navigationDrawer.ContentView = grid;
this.Content = navigationDrawer; 
```

## Project pre-requisites

Make sure that you have the compatible versions of Visual Studio with .NET MAUI workloads and .NET SDK version in your machine before starting to work on this project. Refer to [System Requirements for .NET MAUI](https://help.syncfusion.com/maui/system-requirements).

## How to run this application?

To run this application, you need to first clone the Getting-started-with-.NET-MAUI-NavigationDrawer repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.