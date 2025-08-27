# Syncfusion® Document SDK .NET MAUI examples 
 
This repository contains comprehensive demos of [Syncfusion Document Processing Libraries for .NET MAUI](https://www.syncfusion.com/document-processing/maui?utm_source=github&utm_medium=listing). This is the best place to check our file format libraries to get more insight about creating, editing, and converting documents programmatically. 

This section guides you to use the Syncfusion Document SDK .NET MAUI examples in your applications.

* [Requirements to run the demo](#requirements-to-run-the-demo)
* [How to run the demos](#how-to-run-the-demos)
* [Document SDK Libraries](#document-sdk-libraries)
* [Key Features](#key-features)
* [Documentation](#documentation)
* [License](#license)
* [Support and Feedback](#support-and-feedback)

## <a name="requirements-to-run-the-demo"></a>Requirements to run the demo ##

* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/) or [Visual Studio for Mac](https://visualstudio.microsoft.com/vs/mac/)
* .NET 9.0 SDK
* .NET MAUI workload installed

### Platform Requirements:
* **Android**: API level 21 (Android 5.0) or later
* **iOS**: iOS 15.0 or later
* **macOS**: macOS 12.0 or later (Mac Catalyst)
* **Windows**: Windows 10 version 1809 (build 17763) or later

## <a name="how-to-run-the-demos"></a>How to run the demos ##

### Individual Document Format Demos

Each document format library has its own dedicated sample browser:

1. **DocIO (Word Processing)**: Navigate to `MAUI/DocIO/` folder and open `SampleBrowser.Maui.DocIO.sln`
2. **PDF**: Navigate to `MAUI/Pdf/` folder and open `SampleBrowser.Maui.Pdf.sln`
3. **Presentation (PowerPoint)**: Navigate to `MAUI/Presentation/` folder and open `SampleBrowser.Maui.Presentation.sln`
4. **XlsIO (Excel)**: Navigate to `MAUI/XlsIO/` folder and open `SampleBrowser.Maui.XlsIO.sln`

### Building and Running:

1. Open the desired solution file in Visual Studio 2022
2. Set your target platform (Android, iOS, Windows, or Mac Catalyst)
3. Build and run the application
4. Browse through various samples to explore different document processing capabilities

## <a name="document-sdk-libraries"></a>Document SDK Libraries ##

| Library | Description | Supported Formats |
|---------|-------------|-------------------|
| **[DocIO](https://help.syncfusion.com/maui/docio/overview)** | Word document processing | DOC, DOCX, RTF, HTML, TXT |
| **[PDF](https://help.syncfusion.com/maui/pdf/overview)** | PDF document processing | PDF, PDF/A |
| **[Presentation](https://help.syncfusion.com/maui/presentation/overview)** | PowerPoint processing | PPT, PPTX |
| **[XlsIO](https://help.syncfusion.com/maui/xlsio/overview)** | Excel document processing | XLS, XLSX, CSV |

## <a name="key-features"></a>Key Features ##

### DocIO (Word Processing)
* Create, read, edit, and convert Word documents
* Mail merge and template processing
* Document comparison and protection
* Convert Word to PDF, HTML, and other formats
* Insert images, tables, headers, footers
* LaTeX and SmartArt support

### PDF Library
* Create PDF documents from scratch
* Merge, split, and manipulate PDF files
* Digital signatures and encryption
* PDF/A compliance
* Image to PDF conversion
* Annotations and form filling

### Presentation (PowerPoint)
* Create and modify PowerPoint presentations
* Insert charts, images, and multimedia
* Convert presentations to PDF and images
* Slide manipulation and formatting
* Encryption and password protection

### XlsIO (Excel)
* Create, read, and write Excel files
* Advanced formula calculations
* Charts and pivot tables
* Data validation and formatting
* Excel to PDF conversion
* Template markers for data binding

## Platform Support ##

All Document SDK libraries support the following .NET MAUI platforms:

<table>
	<tr>
		<th align="center">Library</th>
		<th align="center">Android</th>
		<th align="center">iOS</th>
		<th align="center">Mac Catalyst</th>
		<th align="center">Windows</th>
	</tr>
	<tr>
		<td><strong>DocIO</strong></td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
	</tr>
	<tr>
		<td><strong>PDF</strong></td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
	</tr>
	<tr>
		<td><strong>Presentation</strong></td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
	</tr>
	<tr>
		<td><strong>XlsIO</strong></td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
		<td>✓</td>
	</tr>
</table>

## <a name="documentation"></a>Documentation ##

### User Guides:
* [DocIO User Guide](https://help.syncfusion.com/maui/docio/overview)
* [PDF User Guide](https://help.syncfusion.com/maui/pdf/overview)
* [Presentation User Guide](https://help.syncfusion.com/maui/presentation/overview)
* [XlsIO User Guide](https://help.syncfusion.com/maui/xlsio/overview)

### API References:
* [DocIO API Reference](https://help.syncfusion.com/cr/maui/Syncfusion.DocIO.html)
* [PDF API Reference](https://help.syncfusion.com/cr/maui/Syncfusion.Pdf.html)
* [Presentation API Reference](https://help.syncfusion.com/cr/maui/Syncfusion.Presentation.html)
* [XlsIO API Reference](https://help.syncfusion.com/cr/maui/Syncfusion.XlsIO.html)

## <a name="license"></a>License ##

Syncfusion has no liability for any damage or consequence that may arise by the use or viewing of the examples. The examples are for demonstrative purposes and if you choose to use or access the examples you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, accessing or otherwise viewing the examples. By accessing, viewing, or otherwise seeing the examples you acknowledge and agree Syncfusion's examples will not allow you to seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize or otherwise do anything with Syncfusion's examples.

## Using the examples ##

The examples use the Syncfusion Document Processing Libraries, which require a valid license for production use. You can use the examples for evaluation purposes without a license. For production use, you'll need to obtain a [Syncfusion license](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing).

### Installation Requirements:

1. Install the .NET MAUI workload:
   ```
   dotnet workload install maui
   ```

2. Install required Syncfusion NuGet packages (automatically restored when building the project):
   - Syncfusion.DocIORenderer.NET
   - Syncfusion.Pdf.Imaging.NET
   - Syncfusion.Presentation.NET
   - Syncfusion.XlsIO.NET

**Notes:**
* Before you unzip the archive, right-click it, select Properties, and then select Unblock.
* Be sure to unzip the entire archive, and not just individual examples. The samples depend on shared resources in the archive.
* If you unzip individual examples, they will not build due to references to other portions of the ZIP file that were not unzipped. You must unzip the entire archive if you intend to build the examples.

## <a name="support-and-feedback"></a>Support and Feedback ##

* For getting started with .NET MAUI document processing using Syncfusion libraries, refer to the [documentation](https://help.syncfusion.com/maui/docio/overview) that will help you build your own application.

* For any other queries, reach our [Syncfusion support team](https://www.syncfusion.com/support/directtrac/incidents/newincident?utm_source=github&utm_medium=listing) or post the queries through the [community forums](https://www.syncfusion.com/forums?utm_source=github&utm_medium=listing).

* To renew the subscription, click [here](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing) or contact our sales team at <salessupport@syncfusion.com>.

---
  
<p>Copyright © 2001-2025 Syncfusion, Inc. Updated on 2025-01-27 at 17:12:36 EST.</p> 
