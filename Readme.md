<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128655445/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T304338)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# WPF Dock Layout Manager - Automatically Merge Ribbon Controls

The following controls support automatic bar merging:

* [DXTabControl](https://docs.devexpress.com/WPF/7975/controls-and-libraries/layout-management/tab-control/fundamentals/dxtabcontrol)
* [Dock Layout Manager](https://docs.devexpress.com/WPF/6191/controls-and-libraries/layout-management/dock-windows)
  
In this example, the [docklayoutmanager](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DockLayoutManager) component implements the tabbed MDI interface. The main application window and tabs contain ribbon controls.

The example merges a pages, page groups, and items from child ribbons to the main ribbon control.

![image](https://user-images.githubusercontent.com/12169834/174033506-7b471c7b-c6f4-4c36-b84b-548a2f78477e.png)

<!-- default file list -->
## Files to Look At:

* [MainWindow.xaml](./CS/WpfApplication1/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication1/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfApplication1/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfApplication1/MainWindow.xaml.vb))
<!-- default file list end -->

## Documentation

- [Merge Bars and Ribbon in MDI Mode](https://docs.devexpress.com/WPF/9155/controls-and-libraries/layout-management/dock-windows/runtime-features/mdi-bar-merging)
- [DXTabControl.AllowMerging](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.DXTabControl.AllowMerging)
- [DockLayoutManager.MDIMergeStyle](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DockLayoutManager.MDIMergeStyle)
- [DockLayoutManager.AllowMergingAutoHidePanels](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DockLayoutManager.AllowMergingAutoHidePanels)
- [RibbonPage.MergeType](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.RibbonPage.MergeType)
- [RibbonPageGroup.MergeType](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.RibbonPageGroup.MergeType)
- [RibbonPageCategoryBase.MergeOrder](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.RibbonPageCategoryBase.MergeOrder)
- [RibbonPage.MergeOrder](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.RibbonPage.MergeOrder)
- [RibbonPageGroup.MergeOrder](https://docs.devexpress.com/WPF/DevExpress.Xpf.Ribbon.RibbonPageGroup.MergeOrder)
- [BarItemLinkBase.MergeOrder](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.BarItemLinkBase.MergeOrder)

## More Examples

- [WPF Dock Layout Manager - Merge Bars in Controls That Support Automatic Merging](https://github.com/DevExpress-Examples/wpf-docklayoutmanager-merge-bars-in-controls-that-support-automatic-merging)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-docklayoutmanager-merge-ribbon-controls&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-docklayoutmanager-merge-ribbon-controls&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
