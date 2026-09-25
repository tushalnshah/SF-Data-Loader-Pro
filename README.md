<img width="512" height="512" alt="playstore" src="https://github.com/user-attachments/assets/fed7a3df-af28-4576-b633-d63c175fa457" />

# SF-Data-Loader-Pro
A high-performance, cross-platform desktop application for bulk exporting Salesforce data. Built with Electron and React, it leverages the Salesforce Bulk API v2 to stream massive datasets directly to local CSV files without memory limits.

Key Features
1. Secure OAuth Login: Connect to Production or Sandbox environments (credentials are never stored).
2. Smart Object Explorer: Browse, search, sort, and favorite standard and custom objects. View real-time record counts before initiating exports.
3. Delta Exports: Apply CreatedDate or LastModifiedDate filters to download only new or updated records.
4. Massive Scale: Streams data directly to disk. Supports downloading millions of records with automated polling and timeout handling.
5. Persistent Download Manager: Track live export progress, cancel active jobs, and view historical download metadata (file size, exact filters used, success rates) across app restarts.
6. Modern Stack: Electron, React, Vite, Tailwind CSS, and JSforce.
