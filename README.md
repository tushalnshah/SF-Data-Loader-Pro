# SF-Data-Loader-Pro
A high-performance, cross-platform desktop application for bulk exporting Salesforce data. Built with Electron and React, it leverages the Salesforce Bulk API v2 to stream massive datasets directly to local CSV files without memory limits.

Key Features
Secure OAuth Login: Connect to Production or Sandbox environments (credentials are never stored).
Smart Object Explorer: Browse, search, sort, and favorite standard and custom objects. View real-time record counts before initiating exports.
Delta Exports: Apply CreatedDate or LastModifiedDate filters to download only new or updated records.
Massive Scale: Streams data directly to disk. Supports downloading millions of records with automated polling and timeout handling.
Persistent Download Manager: Track live export progress, cancel active jobs, and view historical download metadata (file size, exact filters used, success rates) across app restarts.
Modern Stack: Electron, React, Vite, Tailwind CSS, and JSforce.
