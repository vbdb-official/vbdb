```text
+------------------------------------------------------+
|                   Client Applications                |
|  (Web Apps, Mobile Apps, BI Tools, Admin Consoles)   |
+-------------------------+----------------------------+
                          |
                          v
+------------------------------------------------------+
|                Database API / Interface Layer        |
|  - SQL Interface                                      |
|  - REST / gRPC APIs                                   |
|  - Authentication & Authorization                     |
+-------------------------+----------------------------+
                          |
                          v
+------------------------------------------------------+
|                  Query Processing Layer              |
|  - SQL Parser                                         |
|  - Query Validator                                    |
|  - Query Rewriter                                     |
|  - Cost-Based Query Optimizer                         |
|  - Query Executor                                     |
+-------------------------+----------------------------+
                          |
                          v
+------------------------------------------------------+
|                Transaction Management Layer          |
|  - Transaction Manager                                |
|  - Concurrency Control (Locks / MVCC)                 |
|  - Deadlock Detection & Resolution                    |
|  - Isolation Level Management                         |
+-------------------------+----------------------------+
                          |
                          v
+------------------------------------------------------+
|                  Storage Management Layer            |
|  - Buffer Manager (Cache)                             |
|  - File Manager                                       |
|  - Index Manager (B+ Tree, Hash, LSM)                 |
|  - Record Manager                                     |
+-------------------------+----------------------------+
                          |
                          v
+------------------------------------------------------+
|              Recovery & Logging Layer                |
|  - Write-Ahead Logging (WAL)                          |
|  - Checkpointing                                      |
|  - Crash Recovery                                    |
+-------------------------+----------------------------+
                          |
                          v
+------------------------------------------------------+
|                Physical Storage Layer                |
|  - Data Files                                         |
|  - Index Files                                        |
|  - Log Files                                          |
|  - Metadata Catalog                                  |
+------------------------------------------------------+

```
