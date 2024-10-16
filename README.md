# bag-info.txt fields
#### format version: `1.0.0`


## Standard Bagit Tags
### Bag-Count
X of X, or X of ?: where X is an integer
### Bag-Software-Agent
### Bagging-Date
### Contact-Email
### Contact-Name
### Contact-Phone
### External-Identifier
### Internal-Sender-Identifier
### Organization-Address
### Payload-Oxum
### Source-Organization

## NYU Tags
### nyu-dl-archivesspace-accession-url
optional used only for unproceessed accessions being uploaded to r*
### nyu-dl-archivesspace-resource-url
/repositories/x/resources/x : where x is an integer
### nyu-dl-content-classification
either: `open`, `closed`, or `restricted`
### nyu-dl-content-type	
always `electronic_records`
### nyu-dl-hostname
the host from where the transfer to rstar is initiated
### nyu-dl-pathname
the unix path on the host where the transfer is initiated from
### nyu-dl-project-name
the rstar partner and project name, e.g. fales/mss100
### nyu-dl-resource-id
### nyu-dl-resource-title
### nyu-dl-transfer-type
determines package routing within the repository  
if the `nyu-dl-transfer-type` label **is** present, acceptable values are: `XIP` or `AIP`   
if the `nyu-dl-transfer-type` label **is NOT** present, the package is routed as if `XIP` were specified  
### nyu-dl-use-statement