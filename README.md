**This project demonstrates on how to use ML-Kit Doc Scanner API.**
---------------
APIs Used:
1. GmsDocumentScanning.getClient(options): Returns GmsDocumentScanner object which initialise to scanner.
2. GmsDocumentScannerOptions.Builder(): Builder to build the scanning options like scanner mode, Gallery or Camera allowed, Page Limit, etc.
3. GmsDocumentScanner's getStartScanIntent(activity): Which listens to success/failure of scans.
