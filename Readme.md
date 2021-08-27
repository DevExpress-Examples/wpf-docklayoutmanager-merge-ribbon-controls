<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128655445/15.1.7%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T304338)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/WpfApplication1/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication1/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/WpfApplication1/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfApplication1/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Automatically Merge Ribbon Controls


<p>The automatic ribbon merging is supported by several DevExpress controls

* <strong>DXTabControl</strong> - see <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfCoreDXTabControl_AllowMergingtopic">DXTabControl.AllowMerging Property</a> to learn more on how to enable it.
* <strong>DXDocking</strong> - see <a href="https://documentation.devexpress.com/#WPF/CustomDocument10587">Merging Overview</a> and <a href="https://documentation.devexpress.com/#WPF/CustomDocument9155">MDI Bar Merging</a>.<br><br>In this example, the DockLayoutManager component implements the tabbed MDI interface. The main application window, as well as tabs, contains ribbon controls. The example illustrates pages, page groups and items merging from child ribbons to the main ribbon control.<br><br>There are several properties you can use to control the merging process in DockLayoutManager

* <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDockingDockLayoutManager_MDIMergeStyletopic">DockLayoutManager.MDIMergeStyle</a> - using this property, it is possible to disable merging or specify what panels will be merged: only active panels, or all selected tabs/maximized MDI panels.
* <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDockingDockLayoutManager_AllowMergingAutoHidePanelstopic">DockLayoutManager.AllowMergingAutoHidePanels</a>.
* <strong>MergeType</strong> properties (they are available in <a href="https://documentation.devexpress.com/WPF/DevExpressXpfRibbonRibbonPage_MergeTypetopic.aspx">RibbonPage</a>, <a href="https://documentation.devexpress.com/WPF/DevExpressXpfRibbonRibbonPageGroup_MergeTypetopic.aspx">RibbonPageGroup</a> and <a href="https://documentation.devexpress.com/WPF/DevExpressXpfBarsBarItemLinkBase_MergeTypetopic.aspx">BarItemLinkBase</a>) allow you to control how items with similar captions will be merged.
* <strong>MergeOrder</strong> properties (they are available in <a href="https://documentation.devexpress.com/WPF/DevExpressXpfRibbonRibbonPageCategoryBase_MergeOrdertopic.aspx">RibbonPageCategoryBase</a>, <a href="https://documentation.devexpress.com/WPF/DevExpressXpfRibbonRibbonPage_MergeOrdertopic.aspx">RibbonPage</a>, <a href="https://documentation.devexpress.com/WPF/DevExpressXpfRibbonRibbonPageGroup_MergeOrdertopic.aspx">RibbonPageGroup</a> and <a href="https://documentation.devexpress.com/WPF/DevExpressXpfBarsBarItemLinkBase_MergeOrdertopic.aspx">BarItemLinkBase</a>) can be used to control the merging order.
* <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfRibbonRibbonControl_SelectedPageOnMergingtopic">RibbonControl.SelectedPageOnMerging</a> sets which ribbon's page will be selected when ribbons are merged.<br><br>For more information, refer to <a href="https://documentation.devexpress.com/#WPF/CustomDocument10587">Merging Overview</a>.</p>

<br/>


