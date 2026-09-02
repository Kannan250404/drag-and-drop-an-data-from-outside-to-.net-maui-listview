# drag-and-drop-an-data-from-outside-to-.net-maui-listview

This demo explains about how to perform dragging and dropping the data from outside into .NET MAUI ListView (SfListView).

### Steps
1.Create a custom <b>ListViewExt</b> by inheriting from <a href="https://help.syncfusion.com/cr/maui/Syncfusion.Maui.ListView.SfListView.html">SfListView</a> and implement auto-scrolling support using the <b>ListViewScrollView</b> and <b>VisualContainer</b>. Determine whether the dragged item is near the visible boundaries and automatically scroll the list while dragging.

2.Define a <b>BindableLayout</b> with a custom <b>GridDragBehavior</b> attached to each item to enable drag-and-drop interactions. Use the helper methods in <b>ListViewExt</b> to identify the target item index, update the drop position, and reorder items while maintaining smooth auto-scrolling behavior.

## Requirements to run the demo

* [Visual Studio 2017](https://visualstudio.microsoft.com/downloads/) or [Visual Studio for Mac](https://visualstudio.microsoft.com/vs/mac/)
* Xamarin add-ons for Visual Studio (available via the Visual Studio installer).

## Troubleshooting

### Path too long exception

If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

### Conclusion

I hope you enjoyed learning about how to show or hide accordion item in .NET MAUI Accordion(SfAccordion).

You can refer to our [.NET MAUI Accordion](https://www.syncfusion.com/maui-controls/maui-accordion) feature tour page to know about its other groundbreaking feature representations. You can also explore our [.NET MAUI Accordion documentation](https://help.syncfusion.com/maui/accordion/getting-started) to understand how to present and manipulate data.

For current customers, you can check out our components from the [License and Downloads](https://www.syncfusion.com/account/login) page. If you are new to Syncfusion, you can try our 30-day [free trial](https://www.syncfusion.com/downloads/maui) to check out our other controls.

If you have any queries or require clarifications, please let us know in the comments section below. You can also contact us through our [support forums](https://www.syncfusion.com/forums/), [Direct-Trac](https://support.syncfusion.com/create), or [feedback portal](https://www.syncfusion.com/feedback/maui?control=sflistview). We are always happy to assist you!
