## Functionality

Status: 19.05.2021

| Function              | Supported | Remarks         |
| ---------------------:| :-------: | :-------------- |
| Register Schema       | (+)       | must be configured  | 
| Update Schema         | (+)       | overwrites the previous version | 
| Validate Schema       |  -        |                 | 
| Ingest Metadata       |  +        |                 | 
| Update Metadata       |  +        | overwrites document (create a version in beforehand to prevent loss of 'old' document (experimental))  | 
| Validate Metadata     |  +        | via hooks       | 
| Search by ...         |           |                 | 
| ... Administrative MD |  +        |                 | 
| ... Content           |  +        | via external service | 
| Persistent Identifier |  +        | via external service | 


