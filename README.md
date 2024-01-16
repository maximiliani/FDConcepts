# FDConcepts
Examples of JSON Documents for different types of elements in the FAIR Data Ecosystem

| :exclamation:  This is not meant to be a reference document for correct data schemas!   |
|-----------------------------------------|


## Table of Contents

- [FAIR Digital Objects](Objects/README.md)
- [FAIR Digital Data Types](Data%20Types/README.md)
- [FAIR Digital Type Profiles](Type%20Profiles/README.md)
- [FAIR Digital Operations](Operations/README.md)
- [FAIR Digital Operation Type Profiles](Operation%20Type%20Profiles/README.md)


## Signs and Symbols

| Symbol   | Meaning                               | Example                                                                 |
|----------|---------------------------------------|-------------------------------------------------------------------------|
| `PID ->` | A PID pointing to thing after it      | `PID -> Schema`                                                         |
| `-INH->` | Something inherits from another thing | `SHA256 -INH-> Checksum`<br/> `HTTPLocation -INH-> URL -INH-> Location` |
| `OR`     | Describes an alternative              | `any OR PID->JSON`                                                      |
