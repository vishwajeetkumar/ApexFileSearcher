# ApexFileSearcher
To search Text files with content which is not provided by standard salesforce functionality.

To use just pass the search string.

List<String> fileNames=FileContentSearcher.searchFilesContainingString('mkc');

System.debug(fileNames);
