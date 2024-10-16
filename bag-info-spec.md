# bag-info.txt fields
#### format version: `1.0.0`


## Standard Bagit Tags
### Bag-Count
Two numbers separated by "of", in particular, "N of T", where T is the total number of bags in a group of bags and N is the ordinal number within the group; if T is not known, specify it as "?" (question mark). Examples: 1 of 2, 4 of 4, 3 of ?, 89 of 145.
### Bagging-Date
(YYYY-MM-DD) that the content was prepared for delivery.
### Contact-Email
Fully qualified email address of person or position responsible.
### Contact-Name
Person at the source organization who is responsible for the content transfer.
### Contact-Phone
International format telephone number of person or position responsible.
### External-Identifier
A sender-supplied identifier for the bag.
### Internal-Sender-Identifier
An alternate sender-specific identifier for the content and/or bag.
### Organization-Address
Organization-Address Mailing address of the organization.
### Payload-Oxum
The "octetstream sum" of the payload, namely, a two-part number of the form "OctetCount.StreamCount", where OctetCount is the total number of octets (8-bit bytes) across all payload file content and StreamCount is the total number of payload files.
### Source-Organization
Organization transferring the content.

## Archivematica Tags
### Bag-Software-Agent

## NYU Tags
### nyu-dl-archivesspace-accession-url
optional archivespace url used only for unproceessed accessions being uploaded to r*<br>
`/repositories/x/accessions/x` : where *x* is an integer
### nyu-dl-archivesspace-resource-url
`/repositories/x/resources/x` : where *x* is an integer
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
