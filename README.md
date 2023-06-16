# SlowCheetah

This package allows you to automatically transform your app.config (or any file) when you press F5 in Visual Studio 2022. You can have different transformations based on the build configuration. This will enable you to easily have different app settings, connection strings, etc for Debug versus Release. If you want to transform other files you can do that too.

The NuGet package used is [Microsoft.VisualStudio.SlowCheetah](https://www.nuget.org/packages/Microsoft.VisualStudio.SlowCheetah/).

I highly recommend installing its extension [SlowCheetah](https://marketplace.visualstudio.com/items?itemName=vscps.SlowCheetah-XMLTransforms-VS2022) in your Visual Studio. When you done it, a new button called `Add Transform` will appear when you right-click on the `App.cofig` configuration file.

![add-transform](https://raw.githubusercontent.com/microsoft/slow-cheetah/v4.0.50/doc/AddTransforms.png)

For more information, please consult the following resources:

- https://marketplace.visualstudio.com/items?itemName=vscps.SlowCheetah-XMLTransforms-VS2022
- https://github.com/Microsoft/slow-cheetah

__Did you not see the `Add Transform` button?__ I had problems installing for the first time the extension because I had an unstable Visual Studio version, until I upgraded to a newer one and the extension worked perfectly. Maybe you should also try restarting your computer.