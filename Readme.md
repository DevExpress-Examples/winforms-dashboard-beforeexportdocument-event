<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/WinForms_Dashboard_BeforeExportEvent_Example/Form1.cs) (VB: [Form1.vb](./VB/WinForms_Dashboard_BeforeExportEvent_Example/Form1.vb))
<!-- default file list end -->

# How to Handle the BeforeExportDocument Event to Hide the Dashboard Filter Items

This example demonstrates how to hide dashboard filter items when a dashboard is exported to PDF and the [ExportFilters](https://docs.devexpress.com/Dashboard/DevExpress.DashboardCommon.DashboardPdfExportOptions.ExportFilters) export option is set to **false**.

This approach can be used to handle the following events:

* [DashboardDesigner.BeforeExportDocument](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardDesigner.BeforeExportDocument)
* [DashboardViewer.BeforeExportDocument](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardViewer.BeforeExportDocument)
* [ASPxDashboard.BeforeExportDocument](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWeb.ASPxDashboard.BeforeExportDocument)
* [DashboardConfigurator.BeforeExportDocument](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWeb.DashboardConfigurator.BeforeExportDocument)
* [DashboardControl.BeforeExportDocument](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWpf.DashboardControl.BeforeExportDocument)

![screenshot](images/screenshot.png)

API in this example:

* [DashboardDesigner.BeforeExportDocument](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardDesigner.BeforeExportDocument) event
* [BeforeExportDocumentEventArgs](https://docs.devexpress.com/Dashboard/DevExpress.DashboardCommon.BeforeExportDocumentEventArgs) class
* [DashboardDesigner.CustomizeDashboardTitle](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardDesigner.CustomizeDashboardTitle) event
* [DashboardDesigner.ExportToPdf](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardDesigner.ExportToPdf.overloads) method
* [DashboardDesigner.ConfigureDataConnection ](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardDesigner.ConfigureDataConnection) event
