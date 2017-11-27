# The benchmark for exception-related bugs

This repository contains the benchmark for exception-related bugs. From the five Apache projects such as aries, cassandra, derby, lucene, and mahout, we collected bug fixes whose reports mention exceptions. In the buglist folder, we present three files to describe our extracted mappings. 

1. bug_exception.txt lists the mappings from bug reports to mentioned exceptions. If a bug report contains a stack trace, we parse it and build the mappings from a thrown exception to its corresponding methods in the stack trace.

2. exception_bug.txt lists the mappings from mentioned exceptions to bug reports.

3. bug_revision.txt lists the mappings from bug reports to revisions. The revisions are extracted by ChangeDistiller.  