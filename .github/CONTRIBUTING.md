<!---
  Licensed to the Apache Software Foundation (ASF) under one
  or more contributor license agreements.  See the NOTICE file
  distributed with this work for additional information
  regarding copyright ownership.  The ASF licenses this file
  to you under the Apache License, Version 2.0 (the
  "License"); you may not use this file except in compliance
  with the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing,
  software distributed under the License is distributed on an
  "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
  KIND, either express or implied.  See the License for the
  specific language governing permissions and limitations
  under the License.
-->

## Contributing to OAP

We support GitHub ***Issues*** as a lightweight way to ask questions and engage with the OAP developer community. We use Issues for maintaining a queue ofdevelopment work and as the public record for work on the project. So, feel free to open GitHub issues.

This session includes what is required before submitting a code change.

- We continue to use the Github **Issues** to track the new features/tasks/issues.​

- For every commit, we need an issue id for the commit. ​

- Format the log message as following: **[OAP-issueId][optional:ModuleName] detailed message**​ 

  like [OAP-1406][rpmem-shuffle]Add shuffle block removing operation within one Spark context 

- Always merge your pull request as a single commit and the commit message follow the above format.​

- The formal features names in 0.9 are: **SQL Index**, **SQL Data Source Cache**, **Native SQL Engine**, **Unified Arrow Data Source**, **RDD Cache PMem Extension**, **RPMem Shuffle**, **Remote Shuffle**, **Intel MLlib**.

We don’t strictly request the module id the same as the feature name. Please align in the feature members to use a consistent name in the log message.​

