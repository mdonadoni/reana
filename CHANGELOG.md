# Changelog

## [0.9.3](https://github.com/mdonadoni/reana/compare/0.9.2...0.9.3) (2024-03-05)


### Build

* **helm:** add support for Kubernetes 1.29 ([#775](https://github.com/mdonadoni/reana/issues/775)) ([ae90500](https://github.com/mdonadoni/reana/commit/ae90500acbc101913df1e0b25aa3f2d48de997f0))
* **reana-job-controller/certificates:** update expired CERN Grid CA certificate (440) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/docker:** non-editable submodules in "latest" mode (416) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/python:** bump all required packages as of 2024-03-04 (442) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/python:** bump shared REANA packages as of 2024-03-04 (442) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/deps:** pin invenio-userprofiles to 1.2.4 (665) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/docker:** non-editable submodules in "latest" mode (656) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/python:** bump all required packages as of 2024-03-04 (674) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/python:** bump shared modules (676) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/python:** bump shared REANA packages as of 2024-03-04 (674) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/package:** require jsroot&lt;7.6.0 (399) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/package:** update yarn.lock (399) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/docker:** non-editable submodules in "latest" mode (551) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/python:** bump all required packages as of 2024-03-04 (574) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/python:** bump shared REANA packages as of 2024-03-04 (574) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/docker:** install correct extras of reana-commons submodule (261) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/docker:** non-editable submodules in "latest" mode (255) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/python:** bump all required packages as of 2024-03-04 (267) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/python:** bump shared REANA packages as of 2024-03-04 (267) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/docker:** install correct extras of reana-commons submodule (196) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/docker:** non-editable submodules in "latest" mode (190) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/python:** bump all required packages as of 2024-03-04 (200) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/python:** bump shared REANA packages as of 2024-03-04 (200) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/docker:** install correct extras of reana-commons submodule (79) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/docker:** non-editable submodules in "latest" mode (73) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/python:** bump all required packages as of 2024-03-04 (85) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/python:** bump shared REANA packages as of 2024-03-04 (85) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/docker:** install correct extras of reana-commons submodule (256) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/docker:** non-editable submodules in "latest" mode (249) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/python:** bump all required packages as of 2024-03-04 (261) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/python:** bump shared REANA packages as of 2024-03-04 (261) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))


### Features

* **helm:** add value to customise env vars of job controller ([#781](https://github.com/mdonadoni/reana/issues/781)) ([634691f](https://github.com/mdonadoni/reana/commit/634691fd32cfb08d59eafbae66f23ebc384ca84b))
* **helm:** add value to customise PostgreSQL docker image ([#774](https://github.com/mdonadoni/reana/issues/774)) ([07a191f](https://github.com/mdonadoni/reana/commit/07a191f19c60ac5d11cf1373ef8feaa16b80f0ee)), closes [#773](https://github.com/mdonadoni/reana/issues/773)
* **helm:** add value to customise URL of privacy notice ([#778](https://github.com/mdonadoni/reana/issues/778)) ([650ddbd](https://github.com/mdonadoni/reana/commit/650ddbd32441251e3d2ff64d8fce463dedb24e51))
* **helm:** add values to customise env vars of workflow engines ([#781](https://github.com/mdonadoni/reana/issues/781)) ([35ee032](https://github.com/mdonadoni/reana/commit/35ee032da142916b4c966b2a2077a720a5710664))
* **helm:** use PostgreSQL 14.10 in local dev deployment ([#774](https://github.com/mdonadoni/reana/issues/774)) ([43ead8a](https://github.com/mdonadoni/reana/commit/43ead8ab3d2167458ffa590259b614ade233e853)), closes [#744](https://github.com/mdonadoni/reana/issues/744)
* **reana-dev:** add date to commits bumping dependencies ([#787](https://github.com/mdonadoni/reana/issues/787)) ([a4cb84c](https://github.com/mdonadoni/reana/commit/a4cb84cf5967658365f4963fd7da179747bb764e))
* **reana-job-controller/shutdown:** stop all running jobs before stopping workflow (423) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/footer:** link privacy notice to configured URL (393) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/manager:** call shutdown endpoint before workflow stop (559) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/manager:** increase termination period of run-batch pods (572) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/manager:** pass custom env variables to job controller (571) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/manager:** pass custom env variables to workflow engines (571) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/config:** get max number of parallel jobs from env vars (84) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/executor:** upgrade to Snakemake v7.32.4 (81) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))


### Bug fixes

* **reana-dev:** add PR number in commits bumping shared modules ([#783](https://github.com/mdonadoni/reana/issues/783)) ([57c6755](https://github.com/mdonadoni/reana/commit/57c67555e7e2055baeb2ebb6cd7bb0e4ba632a2c))
* **reana-dev:** create commits that conform to conventional style ([#777](https://github.com/mdonadoni/reana/issues/777)) ([86d0133](https://github.com/mdonadoni/reana/commit/86d01331877212baf2081dbddc37f3de20983b56))
* **reana-dev:** delete extra files with git-submodule --update ([#764](https://github.com/mdonadoni/reana/issues/764)) ([e5680ce](https://github.com/mdonadoni/reana/commit/e5680ce8bd1a9f80dde4ca448f9fc8d21aa1c6ca))
* **reana-dev:** detect number of already open PR in commit suffix ([#783](https://github.com/mdonadoni/reana/issues/783)) ([c533c34](https://github.com/mdonadoni/reana/commit/c533c34c85360cec0646f4318b1e6653407f6703))
* **reana-dev:** update container image labels when releasing ([#765](https://github.com/mdonadoni/reana/issues/765)) ([fe6bc2c](https://github.com/mdonadoni/reana/commit/fe6bc2c397e4af2d873761001bfe485e819211be))
* **reana-job-controller/database:** limit the number of open database connections (437) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/startup:** handle signals for graceful shutdown (59) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/launcher:** remove dollar sign in generated Markdown (389) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/progress:** update failed workflows duration using finish time (387) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/router:** show 404 page for invalid URLs (382) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/manager:** graceful shutdown of job-controller (559) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/manager:** use valid group name when calling `groupadd` (566) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/stop:** store engine logs of stopped workflow (563) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/progress:** handle stopped jobs (260) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/progress:** handle stopped jobs (195) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/progress:** handle stopped jobs (78) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/progress:** correctly handle running and stopped jobs (258) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))


### Performance improvements

* **reana-job-controller/cache:** avoid caching jobs when the cache is disabled (435) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))


### Code refactoring

* **docs:** move from reST to Markdown ([#776](https://github.com/mdonadoni/reana/issues/776)) ([79aedb9](https://github.com/mdonadoni/reana/commit/79aedb9ef2ba0c8a933fe2cac334bd51cd32dd85))
* **reana-job-controller/db:** set job status also in the main database (423) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/docs:** move from reST to Markdown (428) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/monitor:** centralise logs and status updates (423) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/monitor:** move fetching of logs to job-manager (423) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/docs:** move from reST to Markdown (65) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/docs:** move from reST to Markdown (671) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/docs:** move from reST to Markdown (391) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/consumer:** do not update status of jobs (559) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/docs:** move from reST to Markdown (567) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/docs:** move from reST to Markdown (263) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/docs:** move from reST to Markdown (198) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/docs:** move from reST to Markdown (82) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/docs:** move from reST to Markdown (259) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))


### Code style

* **black:** format with black v24 ([#772](https://github.com/mdonadoni/reana/issues/772)) ([311e157](https://github.com/mdonadoni/reana/commit/311e1573867b74d722e04835268d5686e5f64f15))
* **reana-job-controller/black:** format with black v24 (426) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/black:** format with black v24 (670) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/black:** format with black v24 (564) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))


### Continuous integration

* **commitlint:** addition of commit message linter ([#767](https://github.com/mdonadoni/reana/issues/767)) ([be77666](https://github.com/mdonadoni/reana/commit/be77666bb80601c0211674a59a3f91d2609712f9))
* **commitlint:** allow release commit style ([#785](https://github.com/mdonadoni/reana/issues/785)) ([a6f95ac](https://github.com/mdonadoni/reana/commit/a6f95aca9ca1b3fb1663ee2fa7d876ff0da2bf02))
* **commitlint:** check for the presence of concrete PR number ([#771](https://github.com/mdonadoni/reana/issues/771)) ([2c34634](https://github.com/mdonadoni/reana/commit/2c34634465723d1b9aa3858ce3898625f4ba572f))
* **reana-job-controller/commitlint:** addition of commit message linter (417) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/commitlint:** allow release commit style (443) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/commitlint:** check for the presence of concrete PR number (425) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/pytest:** move to PostgreSQL 14.10 (429) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/release-please:** initial configuration (417) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/release-please:** update version in Dockerfile/OpenAPI specs (421) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-job-controller/shellcheck:** fix exit code propagation (425) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/commitlint:** addition of commit message linter (60) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/commitlint:** allow release commit style (67) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/commitlint:** check for the presence of concrete PR number (64) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/release-please:** initial configuration (60) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/release-please:** update version in Dockerfile (63) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/shellcheck:** fix exit code propagation (64) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/commitlint:** addition of commit message linter (665) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/commitlint:** allow release commit style (675) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/commitlint:** check for the presence of concrete PR number (669) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/pytest:** move to PostgreSQL 14.10 (672) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/release-please:** initial configuration (665) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/release-please:** update version in Dockerfile/OpenAPI specs (668) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/shellcheck:** fix exit code propagation (669) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/commitlint:** addition of commit message linter (380) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/commitlint:** allow release commit style (400) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/commitlint:** check for the presence of concrete PR number (390) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/release-please:** initial configuration (380) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/release-please:** switch to `simple` release strategy (383) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/release-please:** update version in package.json and Dockerfile (385) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/shellcheck:** exclude node_modules from the analyzed paths (387) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/shellcheck:** fix exit code propagation (390) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/commitlint:** addition of commit message linter (555) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/commitlint:** allow release commit style (575) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/commitlint:** check for the presence of concrete PR number (562) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/pytest:** move to PostgreSQL 14.10 (568) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/release-please:** initial configuration (555) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/release-please:** update version in Dockerfile/OpenAPI specs (558) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/shellcheck:** fix exit code propagation (562) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/commitlint:** addition of commit message linter (256) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/commitlint:** allow release commit style (268) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/commitlint:** check for the presence of concrete PR number (262) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/release-please:** initial configuration (256) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/release-please:** update version in Dockerfile (259) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/shellcheck:** fix exit code propagation (262) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/commitlint:** addition of commit message linter (191) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/commitlint:** allow release commit style (201) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/commitlint:** check for the presence of concrete PR number (197) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/release-please:** initial configuration (191) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/release-please:** update version in Dockerfile (194) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/shellcheck:** fix exit code propagation (197) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/commitlint:** addition of commit message linter (74) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/commitlint:** allow release commit style (86) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/commitlint:** check for the presence of concrete PR number (80) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/release-please:** initial configuration (74) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/release-please:** update version in Dockerfile (77) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/shellcheck:** fix exit code propagation (80) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/commitlint:** addition of commit message linter (251) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/commitlint:** allow release commit style (262) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/commitlint:** check for the presence of concrete PR number (257) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/release-please:** initial configuration (251) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/release-please:** update version in Dockerfile (254) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/shellcheck:** fix exit code propagation (257) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **release-please:** initial configuration ([#767](https://github.com/mdonadoni/reana/issues/767)) ([bb45539](https://github.com/mdonadoni/reana/commit/bb455393ac1b4d149cfef4df6e96ae730c25501c))
* **release-please:** update version in Helm Chart ([#770](https://github.com/mdonadoni/reana/issues/770)) ([09c9210](https://github.com/mdonadoni/reana/commit/09c9210d68e29d094c0e76a4002b17a21fcda701))
* **shellcheck:** fix exit code propagation ([#771](https://github.com/mdonadoni/reana/issues/771)) ([035d51c](https://github.com/mdonadoni/reana/commit/035d51ca95dbab1c225316667ea2d199d924c851))


### Documentation

* **authors:** complete list of contributors ([#779](https://github.com/mdonadoni/reana/issues/779)) ([123eae8](https://github.com/mdonadoni/reana/commit/123eae8d4d97846f895ba652bdf30df35dcd7c00))
* **chat:** remove Gitter ([#782](https://github.com/mdonadoni/reana/issues/782)) ([aba8ac2](https://github.com/mdonadoni/reana/commit/aba8ac2ae1b5cee0a8970edb2c85453657deb159))
* **reana-job-controller/authors:** complete list of contributors (434) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-message-broker/authors:** complete list of contributors (66) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-server/authors:** complete list of contributors (673) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-ui/authors:** complete list of contributors (396) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-controller/authors:** complete list of contributors (570) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/authors:** complete list of contributors (266) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-cwl/conformance-tests:** update CWL conformance test badges (264) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-serial/authors:** complete list of contributors (199) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-snakemake/authors:** complete list of contributors (83) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))
* **reana-workflow-engine-yadage/authors:** complete list of contributors (260) ([d685a2e](https://github.com/mdonadoni/reana/commit/d685a2ef2e5c27aefb5bf260e7f43796b3f637ab))

## 0.9.2 (2023-12-19)

- Users:

  - Adds web interface form allowing to generate launcher URL for any user-provided public analysis, as well as the Markdown snippet for the corresponding Launch-on-REANA badge.
  - Adds web interface option to delete all the runs of a workflow.
  - Changes the Launch-on-REANA web interface page to improve how workflow parameters are shown by displaying them inside a table.
  - Changes CVMFS support to allow users to automatically mount any available repository.
  - Changes the REANA specification schema to use the `draft-07` version of the JSON Schema specification.
  - Changes `reana-client validate` command to show detailed errors when the specification file is not a valid YAML file.
  - Changes validation of REANA specification to make the `environment` property mandatory for the steps of serial workflows.
  - Changes validation of REANA specification to raise a warning for unexpected properties for the steps of serial workflows.
  - Changes validation of REANA specification to report improved validation warnings which also indicate where unexpected properties are located in the file.
  - Changes workflow restarts to allow for more than nine restarts of the same workflows.
  - Changes workflow scheduler logging behaviour to also report the main reason behind scheduling errors to the users.
  - Fixes `reana-client list` command to accept case-insensitive column names when sorting the returned workflow runs via the `--sort` option.
  - Fixes `reana-client run` wrapper command for workflows that do not contain `inputs` clause in their specification.
  - Fixes `reana-client`'s `create_workflow_from_json` API function to always load and send the workflow specification to the server.
  - Fixes creation of image thumbnails for output files in Snakemake HTML execution reports.

- Administrators:

  - Changes several database index definitions in order to improve performance of most common database queries.
  - Changes the names of database table, column, index and key constraints in order to follow the SQLAlchemy upstream naming conventions everywhere.
  - Changes the `Workflow` table to replace the `run_number` column with two new columns `run_number_major` and `run_number_minor` in order to allow for more than nine restarts of user workflows.
  - Changes CVMFS support to allow users to automatically mount any available repository, thanks to CVMFS CSI v2.
  - Fixes the mounting of CVMFS volumes for the REANA deployments that use non-default Kubernetes namespace.
  - Fixes container image building of cluster components for the arm64 architecture.
  - Fixes job monitoring in cases when job creation fails, for example when it is not possible to successfully mount volumes.
  - Fixes job status consumer exception while attempting to fetch workflow engine logs for workflows that could not have been successfully scheduled.
  - Fixes the creation of Kubernetes jobs by retrying in case of error and by correctly handling the error after reaching the retry limit.

- Developers:

  - Adds automated multi-platform container image building of cluster components for amd64 and arm64 architectures.
  - Adds new `--image-name` option to the `reana-dev docker-push` command to customise the name of the docker image to publish.
  - Adds new `--platform` option to the `reana-dev docker-build` and `reana-dev release-docker` commands to build and publish multi-platform images.
  - Adds new `--registry` option to the `reana-dev docker-push` and `reana-dev release-docker` commands to specify the registry where the built docker images should be pushed to.
  - Adds new `--tags-only` option to the `reana-dev release-docker` command to only print the final docker image names, without pushing the images to the registry.
  - Adds new `reana-dev git-create-release-branch` command to create a new Git branch for a new release.
  - Adds new `reana-dev git-upgrade-requirements` command to upgrade the `requirements.txt` file before a new release.
  - Changes `reana-dev git-fork` and `reana-dev git-create-pr` to use the `gh` CLI client instead of `hub`.
  - Changes `reana-dev python-run-tests` command to allow excluding certain Python components.
  - Changes `reana-dev python-run-tests` command to allow execution of selected pytests only by passing over `PYTEST_ADDOPTS` environment variable.
  - Changes validation of REANA specification to expose functions for loading workflow input parameters and workflow specifications.
  - Changes version of `reana-ui` Node.js Docker image from 16 to 18.
  - Changes the workflow deletion endpoint to return a different and more appropriate message when deleting all the runs of a workflow.
  - Changes the workflow list endpoint on how pagination is performed in order to avoid counting twice the total number of records.
  - Fixes `reana-dev python-run-tests` command to create Python-3.8 based virtual environments to use the same version as container images.

## 0.9.1 (2023-09-27)

- Users:

  - Adds support for Python 3.12.
  - Adds support for previewing PDF files present in a workflow's workspace.
  - Adds support for previewing ROOT files present in a workflow's workspace.
  - Adds support for signing-in with a custom third-party Keycloak instance.
  - Adds a new menu item to the workflow actions popup to allow stopping running workflows.
  - Adds `prune` command to delete all intermediate files of a given workflow. Use with care.
  - Changes the deletion of a workflow to automatically delete an open interactive session attached to its workspace.
  - Changes the workflow deletion message to clarify that attached interactive sessions are also closed when a workflow is deleted.
  - Changes the workflow progress bar to always display it as completed for finished workflows.
  - Changes the interactive session notification to also report that the session will be closed after a specified number of days of inactivity.
  - Changes the workflow-details page to make it possible to scroll through the list of workflow steps in the job logs section.
  - Changes the workflow-details page to not automatically refresh the selected job when viewing the related logs, but keeping the user-selected one active.
  - Changes the page titles to conform to the same sentence case style.
  - Changes the launcher page to show warnings when validating the REANA specification file of the workflow to be launched.
  - Changes `open` command to inform user about the auto-closure of interactive sessions after a certain inactivity timeout.
  - Changes `validate` command to display non-critical validation warnings when checking the REANA specification file.
  - Changes Rucio authentication helper to allow users to override the Rucio server and authentication hosts independently of VO name.
  - Fixes job status inconsistency when stopping a workflow by setting the job statuses to `stopped` for any running jobs.
  - Fixes calculation of workflow runtime durations for stopped workflows.
  - Fixes `list` command to correctly list workflows when sorting them by their run number or by the size of their workspace.
  - Fixes `du` command help message typo.
  - Fixes `validation --environments` command to correctly handle fully-qualified image names.
  - Fixes deletion of failed jobs not being performed when Kerberos is enabled.
  - Fixes job monitoring to consider OOM-killed jobs as failed.
  - Fixes detection of default Rucio server and authentication host for ATLAS VO.
  - Fixes the reported total number of jobs for restarted workflows by excluding cached jobs that were simply reused from previous runs in the workspace and not really executed by Snakemake.
  - Fixes an issue where Snakemake workflows could get stuck waiting for already-finished jobs.

- Administrators:

  - Adds support for Kubernetes clusters 1.26, 1.27, 1.28.
  - Adds new configuration option `components.reana_ui.launcher_examples` to customise the demo examples that are shown in the launch page in the REANA UI.
  - Adds new configuration option `interactive_sessions.maximum_inactivity_period` to set a limit in days for the maximum inactivity period of interactive sessions after which they will be closed.
  - Adds new configuration option `interactive_sessions.cronjob_schedule` to set how often interactive session cleanup should be performed.
  - Adds new configuration option `ingress.extra` to define extra Ingress resources, in order to support redirecting HTTP requests to HTTPS with traefik v2 version.
  - Adds new configuration option `ingress.tls.hosts` to define hosts that are present in the TLS certificate, in order to support cert-manager's automatic creation of certificates.
  - Adds new configuration option `notifications.email_config.smtp_ssl` to use SSL when connecting to the SMTP email server.
  - Adds new configuration option `notifications.email_config.smtp_starttls` to use the STARTTLS command to enable encryption after connecting to the SMTP email server.
  - Adds new configuration option `components.reana_ui.file_preview_size_limit` to set the maximum file size that can be previewed in the web interface.
  - Adds new configuration options `login` and `secrets.login` for configuring Keycloak SSO login with third-party authentication services.
  - Adds new `interactive-session-cleanup` command that can be used by REANA administrators to close interactive sessions that are inactive for more than the specified number of days.
  - Adds progress meter to the logs of the periodic quota updater.
  - Adds the content of the `secrets.gitlab.REANA_GITLAB_HOST` configuration option to the list of GitLab instances from which it is possible to launch a workflow.
  - Changes uWSGI configuration to increase buffer size, add vacuum option, etc.
  - Changes CPU and disk quota calculations to improve the performance of periodic quota updater.
  - Changes the system status report to simplify and clarify the disk usage summary.
  - Changes `check-workflows` command to also check the presence of workspaces on the shared volume.
  - Changes `check-workflows` command to not show in-sync runs by default. If needed, they can be shown using the new `--show-all` option.
  - Changes `reana-admin` command options to require the passing of `--admin-access-token` argument more globally.
  - Changes the k8s specification for interactive session pods to include labels for improved subset selection of objects.
  - Changes the k8s specification for interactive session ingress resource to include annotations.
  - Changes nginx configuration to save bandwidth by serving gzip-compressed static files.
  - Changes HTCondor to version 9.0.17 (LTS).
  - Fixes uWSGI memory consumption on systems with very high allowed number of open files.
  - Fixes cronjob failures due to database connection issues when REANA is deployed with non-default namespace or prefix.
  - Fixes `ingress.enabled` option to correctly enable or disable the creation of Ingresses.
  - Fixes graceful shutdown for reana-server and reana-workflow-controller.
  - Fixes the workflow priority calculation to avoid workflows stuck in the `queued` status when the number of allowed concurrent workflow is set to zero.
  - Fixes GitLab integration to automatically redirect the user to the correct URL when the access request is accepted.
  - Fixes authentication flow to correctly deny access to past revoked tokens in case the same user has also other new active tokens.
  - Fixes email templates to show the correct `kubectl` commands when REANA is deployed inside a non-default namespace or with a custom component name prefix.
  - Fixes email sender for system emails to `notifications.email_config.sender` Helm value.
  - Fixes email receiver for token request emails to use `notifications.email_config.receiver` Helm value.
  - Fixes `quota-set-default-limits` command to propagate default quota limits to all users without custom quota limit values.
  - Fixes job status consumer to correctly rollback the database transaction when an error occurs.
  - Fixes intermittent Slurm connection issues by DNS-resolving the Slurm head node IPv4 address before establishing connections.
  - Fixes Slurm command generation issues when using fully-qualified image names.
  - Fixes high memory usage of RabbitMQ by limiting the maximum number of open file descriptors.
  - Removes support for Kubernetes version prior to 1.21.

- Developers:

  - Adds new `prune_workspace` endpoint to allow users to delete all the files of a workflow, specifying whether to also delete the inputs and/or the outputs.
  - Adds the timestamp of when the workflow was stopped (`run_stopped_at`) to the workflow list and the workflow status endpoints.
  - Adds unique error messages to Kubernetes job monitor to more easily identify source of problems.
  - Adds new `--parallel` option to `docker-build`, `cluster-build` and `run-ci` to build multiple docker images in parallel.
  - Changes `launch` endpoint to also include the warnings of the validation of the workflow specification.
  - Changes OpenAPI specification of the `info` endpoint to return the maximum inactivity time before automatic closure of interactive sessions.
  - Changes `apispec` dependency version in order to be compatible with `PyYAML` v6.
  - Changes Paramiko to version 3.0.0.
  - Changes remote storage file support for Snakemake workflows to use XRootD 5.6.0.
  - Fixes `cluster-deploy`, `cluster-undeploy` and `client-setup-environment` commands when using custom instance name or kubernetes namespace.
  - Fixes the `git-tag` command to display the component name.
  - Fixes container image names to be Podman-compatible.
  - Fixes location of HTCondor build dependencies.

## 0.9.0 (2023-01-26)

- Users:

  - Adds support for Rucio authentication for workflow jobs.
  - Adds support for Kerberos authentication for workflow orchestration.
  - Adds support for specifying `slurm_partition` and `slurm_time` for Slurm compute backend jobs.
  - Adds support for XRootD remote file locations in Snakemake workflow specification definitions.
  - Adds support for Python 3.11.
  - Adds Launch on REANA page allowing the submission of workflows via badge-clicking.
  - Adds notifications to inform users when critical levels of quota usage is reached.
  - Adds 404 Not Found error page.
  - Adds tab titles to all the pages.
  - Adds the `REANA_WORKSPACE` environment variable to jupyter notebooks and terminals.
  - Adds option to sort workflows by most disk and cpu quota usage to the workflow list endpoint.
  - Adds support for specifying and listing workspace file retention rules.
  - Adds support for `.gitignore` and `.reanaignore` to specify files that should not be uploaded to REANA.
  - Adds `retention-rules-list` command to list the retention rules of a workflow.
  - Changes REANA specification to allow specifying `retention_days` for the workflow.
  - Changes default Slurm partition to `inf-short`.
  - Changes GitLab integration to also retrieve user's projects that are in groups and subgroups.
  - Changes the workflow-details page to show the logs of the workflow engine.
  - Changes the workflow-details page to show file sizes in a human-readable format.
  - Changes the workflow-details page to show the workspace's retention rules.
  - Changes the workflow-details page to show the duration of the workflow's jobs.
  - Changes the workflow-details page to display a label of the workflow launcher URL remote origin.
  - Changes the workflow-details page to periodically refresh the content of the page.
  - Changes the workflow-details page to refresh after the deletion of a workflow.
  - Changes the workflow-list page to add a way to hide deleted workflows.
  - Changes the workflow-list page to add new workflows sorting options by most used disk and cpu quota.
  - Changes the deletion of a workflow to always clean up the workspace and to update the user disk quota usage.
  - Changes the CWD of jupyter's terminals to the directory of the workflow's workspace.
  - Changes percentage ranges used to calculate the health status of user resource quota usage.
  - Changes `create` and `restart` commands to always upload the REANA specification file.
  - Changes `delete` command to always delete the workflow's workspace.
  - Changes `delete_workflow` Python API function to always delete the workflow's workspace.
  - Changes `download` command to add the possibility to write files to the standard output via `-o -` option.
  - Changes `list` command to hide deleted workflows by default.
  - Changes `list` command to allow displaying deleted workflows via `--all` and `--show-deleted-runs` options.
  - Changes `list` and `status` commands to allow displaying the duration of workflows with the `--include-duration` option.
  - Changes `mv` command to allow moving files while a workflow is running.
  - Changes `upload` command to prevent uploading symlinks.
  - Changes `validation --environment` command to use Docker registry v2 APIs to check that a Docker image exists in DockerHub.
  - Fixes `list` command to highlight the workflow specified in `REANA_WORKON` correctly.
  - Fixes `secrets-delete` command error message when deleting non existing secrets.
  - Fixes `start` command to report failed workflows as errors.
  - Fixes `start` and `run` commands to correctly follow the execution of the workflow until termination.
  - Fixes `status` command to respect output format provided by the `--format` option.
  - Fixes `upload` command to report when input directories are listed under the `files` section in the REANA specification file and vice versa.
  - Fixes `validate --environment` command to detect illegal whitespace characters in Docker image names.
  - Fixes Kerberos authentication for long-running workflows by renewing the Kerberos ticket periodically.
  - Fixes status reporting for failed CWL and Snakemake jobs that were incorrectly considered successful.
  - Fixes redirection chain for non-signed-in CERN SSO users to access the desired target page after sign-in.
  - Fixes the ordering by size of the files showed in the `Workspace` tab of the workflow-details page.
  - Fixes CERN OIDC authentication to possibly allow eduGAIN and social login users.
  - Fixes wrong numbering of restarted workflows by limiting the number of times a workflow can be restarted to nine.

- Administrators:

  - Adds new configuration environment variable `reana_server.environment.REANA_SCHEDULER_REQUEUE_COUNT` to set workflow requeue count in case of scheduling errors or busy cluster situations.
  - Adds "infinity" option to `REANA_SCHEDULER_REQUEUE_COUNT` to disable requeue count.
  - Adds support for Kubernetes clusters 1.22, 1.23, 1.24, 1.25.
  - Adds new configuration option `workspaces.retention_rules.maximum_period` to set a default period for workspace retention rules.
  - Adds new configuration option `workspaces.retention_rules.cronjob_schedule` to set how often pending retention rules should be applied.
  - Adds configuration environment variable `reana_server.environment.REANA_RATELIMIT_SLOW` to limit API requests to some protected endpoints e.g launch workflow.
  - Adds configuration environment variable `reana_server.environment.REANA_WORKFLOW_SCHEDULING_READINESS_CHECK_LEVEL` to define checks that are performed to assess whether the cluster is ready to start new workflows.
  - Adds new configuration option `ingress.tls.self_signed_cert` to enable the generation of a self-signed TLS certificate.
  - Adds new configuration option `ingress.tls.secret_name` to specify the name of the Kubernetes secret containing the TLS certificate to be used.
  - Adds support for configuring an additional volume to be used by the database and the message broker.
  - Adds new configuration option `maintenance.enabled` to scale down the cluster for maintenance.
  - Adds support for Unicode characters inside email body.
  - Adds `queue-consume` command that can be used by REANA administrators to remove specific messages from the queue.
  - Adds `retention-rules-apply` command that can be used by REANA administrators to apply pending retention rules.
  - Adds `retention-rules-extend` command that can be used by REANA administrators to extend the duration of active retentions rules.
  - Adds `check-workflows` command that can be used by REANA administrators to check for out-of-sync workflows and interactive sessions.
  - Changes configuration option `quota.workflow_termination_update_policy` to deactivate workflow termination accounting by default.
  - Changes Helm template to use PostgreSQL 12.13 version.
  - Changes the base image for most of the components to Ubuntu 20.04 LTS and reduces final Docker image size by removing build-time dependencies.
  - Changes `reana-auth-vomsproxy` sidecar to the latest stable version to support client-side proxy file generation technique and ESCAPE VOMS.
  - Changes OAuth configuration to enable the new CERN SSO.
  - Changes job status consumer to improve logging for not-alive workflows.
  - Changes the deployment of interactive sessions to improve security by not automounting the Kubernetes service account token.
  - Changes the deployment of job-controller to avoid unnecessarily mounting the database's directory.
  - Changes the announcements to support limited HTML markup.
  - Changes REANA specification loading functionality to allow specifying different working directories.
  - Changes global setting of maximum number of parallel jobs to 300 for Snakemake workflow engine.
  - Fixes job status consumer by discarding invalid job IDs.
  - Fixes GitLab integration error reporting in case user exceeds CPU or Disk quota usage limits.
  - Fixes issue when irregular number formats are passed to `REANA_SCHEDULER_REQUEUE_COUNT` configuration environment variable.
  - Fixes quota updater to reduce memory usage.
  - Fixes conversion of possibly-negative resource usage values to human-readable formats.
  - Fixes disk quota updater to prevent setting negative disk quota usage values.
  - Removes support for Kubernetes version prior to 1.19.

- Developers:

  - Adds OpenAPI specification support for `launch` endpoint that allows running workflows from remote sources.
  - Adds OpenAPI specification support for `get_workflow_retention_rules` endpoint that allows to retrieve the workspace file retention rules of a workflow.
  - Adds the remote origin of workflows submitted via Launch-on-REANA (`launcher_url`) to the workflow list endpoint.
  - Adds common utility functions for managing workspace files to `reana-commons`.
  - Changes default consumer prefetch count to handle 10 messages instead of 200 in order to reduce the probability of 406 PRECONDITION errors on message acknowledgement.
  - Changes `git-upgrade-shared-modules` to generate the correct upper-bound in `setup.py`.
  - Changes REANA specification loading and validation functionalities by porting some of the logic to `reana-commons`.
  - Changes OpenAPI specification to include missing response schema elements.
  - Changes the Kubernetes Python client to use the `networking/v1` API.
  - Changes the deployment of interactive sessions to use `networking/v1` Kubernetes API.
  - Changes to Flask v2.
  - Changes `/api/info` endpoint to also include the kubernetes maximum memory limit, the kubernetes default memory limit and the maximum workspace retention period.
  - Changes `start_workflow` endpoint to validate the REANA specification of the workflow.
  - Changes `create_workflow` endpoint to populate workspace retention rules for the workflow.
  - Changes `start_workflow` endpoint to disallow restarting a workflow when retention rules are pending.
  - Changes API rate limiter error messages to be more verbose.
  - Changes workflow scheduler to allow defining the checks needed to assess whether the cluster can start new workflows.
  - Changes workflow list endpoint to add the possibility to filter by workflow ID.
  - Changes the `move_files` endpoint to allow moving files while a workflow is running.
  - Changes the k8s specification of interactive sessions' pods to remove the environment variables used for service discovery.
  - Changes GitLab integration to use `reana` as pipeline name instead of `default` when setting status of a commit.
  - Changes the loading of Snakemake specifications to preserve the current working directory.
  - Changes the Invenio dependencies to the latest versions.
  - Fixes the submission of jobs by stripping potential leading and trailing whitespaces in Docker image names.
  - Fixes `fetchWorkflow` action to fetch a specific workflow instead of the entire user workflow list. (reana-ui)
  - Fixes the download of files by changing the default MIME type to `application/octet-stream`.
  - Fixes the workflow list endpoint to correctly parse the boolean parameters `include_progress`, `include_workspace_size` and `include_retention_rules`.

## 0.8.1 (2022-02-15)

- Users:

  - Adds support for specifying `kubernetes_job_timeout` for Kubernetes compute backend jobs.
  - Adds Kubernetes job memory limits validation before accepting workflows for execution.
  - Adds support for HTML preview of workspace files in the web user interface.
  - Adds an option to search for concrete file names in the workflow's workspace web user interface page.
  - Changes the Cluster Health web interface page to display the cluster status information based on resource availability rather than only usage.
  - Changes `info` command to include the list of supported compute backends.
  - Fixes workflow stuck in pending status due to early Yadage failures.
  - Fixes formatting of error messages and sets appropriate exit status codes.

- Administrators:

  - Adds new configuration option to set default job timeout value for the Kubernetes compute backend jobs (`kubernetes_jobs_timeout_limit`).
  - Adds new configuration option to set maximum job timeout that users can assign to their jobs for the Kubernetes compute backend (`kubernetes_jobs_max_user_timeout_limit`).
  - Adds new configuration option `compute_backends` to specify the supported list of compute backends for validation purposes.
  - Adds new configuration option `reana_server.uwsgi.log_all` to toggle the logging of all the HTTP requests.
  - Adds new configuration options `reana_server.uwsgi.log_4xx` and `reana_server.uwsgi.log_5xx` to only log HTTP error requests, i.e. HTTP requests with status code 4XX and 5XX. To make this configuration effective `reana_server.uwsgi.log_all` must be `false`.
  - Adds new configuration options `node_label_infrastructuremq` and `node_label_infrastructuredb` to have the possibility to run the Message Broker and the Database pods in specific nodes.
  - Changes uWSGI configuration to log all HTTP requests in REANA-Server by default.
  - Changes `quota.disk_update` to `quota.periodic_update_policy` to also update the CPU quota. Keeps `quota.disk_update` for backward compatibility.
  - Changes the name of configuration option `quota.termination_update_policy` to `quota.workflow_termination_update_policy`. Keeps `quota.termination_update_policy` for backward compatibility.

- Developers:

  - Adds workflow name validation to the `create_workflow` endpoint, restricting special characters like dots.
  - Changes `/api/info` endpoint to return a list of supported compute backends.
  - Changes `/api/status` endpoint to calculate the cluster health status based on the availability instead of the usage.
  - Changes the way of determining Snakemake job statuses, polling the Job Controller API instead of checking local files.

## 0.8.0 (2021-11-30)

- Users:

  - Adds support for running and validating Snakemake workflows.
  - Adds support for `outputs.directories` in `reana.yaml` allowing to easily download output directories.
  - Adds new command `quota-show` to retrieve information about total CPU and Disk usage and quota limits.
  - Adds new command `info` that retrieves general information about the cluster, such as available workspace path settings.
  - Changes `validate` command to add the possibility to check the workflow against server capabilities such as desired workspace path via `--server-capabilities` option.
  - Changes `list` command to add the possibility to filter by workflow status and search by workflow name via `--filter` option.
  - Changes `list` command to add the possibility to filter and display all the runs of a given workflow via `-w` option.
  - Changes `list` command to stop including workflow progress and workspace size by default. Please use new options `--include-progress` and `--include-workspace-size` to show this information.
  - Changes `list --sessions` command to display the status of interactive sessions.
  - Changes `logs` command to display also the start and finish times of individual jobs.
  - Changes `ls` command to add the possibility to filter by file name, size and last-modified values via `--filter` option.
  - Changes `du` command to add the possibility filter by file name and size via `--filter` option.
  - Changes `delete` command to prevent hard-deletion of workflows.
  - Changes Yadage workflow specification loading to be done in `reana-commons`.
  - Changes CWL workflow engine to `cwltool` version `3.1.20210628163208`.
  - Removes support for Python 2.7. Please use Python 3.6 or higher from now on.

- Administrators:

  - Adds new configuration options `node_label_runtimebatch`, `node_label_runtimejobs`, `node_label_runtimesessions` allowing to set cluster node labels for splitting runtime workload into dedicated workflow batch nodes, workflow job nodes and interactive session nodes.
  - Adds new configuration option `workspaces.paths` allowing to set a dictionary of available workspace paths to pairs of `cluster_node_path:cluster_pod_mountpath` for mounting directories from cluster nodes.
  - Adds new configuration option `quota.enabled` to enable or disable CPU and Disk quota accounting for users.
  - Adds new configuration option `quota.termination_update_policy` to select the quota resources such as CPU and Disk for which the quota usage will be calculated immediately at the workflow termination time.
  - Adds new periodic cron job to update Disk quotas nightly. Useful if the `quota.termination_update_policy` does not include Disk quota resource.
  - Adds configuration environment variable `reana_server.environment.REANA_WORKFLOW_SCHEDULING_POLICY` allowing to set workflow scheduling policy (first-in first-out, user-balanced and workflow-complexity balanced).
  - Adds configuration environment variables `reana_server.environment.REANA_RATELIMIT_GUEST_USER`, `reana_server.environment.REANA_RATELIMIT_AUTHENTICATED_USER` allowing to set REST API rate limit values.
  - Adds configuration environment variable `reana_server.environment.REANA_SCHEDULER_REQUEUE_SLEEP` to set a time to wait between processing queued workflows.
  - Adds configuration environment variable `reana_workflow_controller.environment.REANA_JOB_STATUS_CONSUMER_PREFETCH_COUNT` allowing to set a prefetch count for the job status consumer.
  - Adds support for Kubernetes 1.21 version clusters.
  - Adds default `kubernetes_memory_limit` value (4 GiB) that will be used for all user jobs unless they specify otherwise.
  - Changes Helm template to use PostgreSQL 12.8 version.
  - Changes Helm template for `reana-db` component to allow 300 maximum number of database connections by default.
  - Fixes email validation procedure during `create-admin-user` command to recognize more permissive email address formats.

- Developers:

  - Changes `git-*` commands to add the possibility of excluding certain components via the `--exclude-components` option.
  - Changes `git-create-release-commit` command to bump all version files in a component.
  - Changes `git-log` command to show diff patch or to pass any wanted argument.
  - Changes `helm-upgrade-components` command to also upgrade the image tags in `prefetch-images.sh` script.

## 0.7.4 (2021-07-07)

- Users:

  - Adds support for file listing wildcard matching patterns to `ls` command.
  - Adds support for directory download and wildcard matching patterns to `download` command.
  - Adds support for specifying `kubernetes_memory_limit` for Kubernetes compute backend jobs for CWL, Serial and Yadage workflows.
  - Changes `list` command to include deleted workflows by default.
  - Changes `validate` command to warn about incorrectly used workflow parameters for each step.
  - Changes `validate` command to display more granular workflow validation output.
  - Fixes workflow step job command formatting bug for CWL workflows on HTCondor compute backend.
  - Fixes `validate` command output for verifying environment image UID values.
  - Fixes `upload_to_server()` Python API function to silently skip uploading in case of none-like inputs.
  - Fixes `validate` command for environment image validation to not test repetitively the same image found in different steps.

- Administrators:

  - Adds support for Kubernetes 1.21.
  - Adds configuration environment variable to set default job memory limits for the Kubernetes compute backend (`REANA_KUBERNETES_JOBS_MEMORY_LIMIT`).
  - Adds configuration environment variable to set maximum custom memory limits that users can assign to their jobs for the Kubernetes compute backend (`REANA_KUBERNETES_JOBS_MAX_USER_MEMORY_LIMIT`).
  - Changes HTCondor compute backend to 8.9.11 and `myschedd` package and configuration to latest versions.
  - Fixes Kubernetes job log capture to include information about failures caused by external factors such as out-of-memory situations (`OOMKilled`).

- Developers:

  - Adds new functions to serialise/deserialise job commands between REANA components.
  - Changes client dependencies to unpin six so that client may be installed in more contexts.
  - Changes cluster dependencies to remove click and pins several dependencies.
  - Changes `reana_ready()` function location to REANA-Server.

## 0.7.3 (2021-03-24)

- Users:

  - Adds `reana-client validate` options to detect possible issues with workflow input parameters and environment images.
  - Fixes problem with failed jobs being reported as still running in case of network problems.
  - Fixes job command encoding issues when dispatching jobs to HTCondor and Slurm backends.

- Administrators:

  - Adds new configuration to toggle Kubernetes user jobs clean up.
    : (`REANA_RUNTIME_KUBERNETES_KEEP_ALIVE_JOBS_WITH_STATUSES` in `components.reana_workflow_controller.environment`)
  - Improves platform resilience.

- Developers:

  - Adds new command-line options to `reana-dev run-example` command allowing full parallel asynchronous execution of demo examples.
  - Adds default configuration for developer deployment mode to keep failed workflow and job pods for easier debugging.
  - Changes job status consumer communications to improve overall platform resilience.

## 0.7.2 (2021-02-04)

- Administrators:

  - Adds support for deployments on Kubernetes 1.20 clusters.
  - Adds deployment option to disable user email confirmation step after sign-up. (`REANA_USER_EMAIL_CONFIRMATION` in `components.reana_server.environment`)
  - Adds deployment option to disable user sign-up feature completely. (`components.reana_ui.hide_signup`)
  - Adds deployment option to display CERN Privacy Notice for CERN deployments. (`components.reana_ui.cern_ropo`)

- Developers:

  - Adds support for Python 3.9.
  - Fixes minor code warnings.
  - Changes CI system to include Python flake8 and Dockerfile hadolint checkers.

## 0.7.1 (2020-11-10)

- Users:

  - Adds support for specifying `htcondor_max_runtime` and `htcondor_accounting_group` for HTCondor compute backend jobs.
  - Fixes restarting of Yadage and CWL workflows.
  - Fixes REANA \<-> GitLab synchronisation for projects having additional external webhooks.
  - Changes `ping` command output to include REANA client and server version information.

- Developers:

  - Fixes conflicting `kombu` installation requirements by requiring Celery version 4.
  - Changes `/api/you` endpoint to include REANA server version information.
  - Changes continuous integration platform from Travis CI to GitHub Actions.

## 0.7.0 (2020-10-21)

- Users:

  - Adds new `restart` command to restart previously run or failed workflows.
  - Adds option to `logs` command to filter job logs according to compute backend, docker image, job status and step name.
  - Adds option to specify operational options in the `reana.yaml` of the workflow.
  - Adds option to specify unpacked Docker images as workflow step requirement.
  - Adds option to specify Kubernetes UID for jobs.
  - Adds support for VOMS proxy as a new authentication method.
  - Adds support for pulling private Docker images.
  - Adds pagination on the workflow list and workflow detailed web interface pages.
  - Adds user profile page to the web interface.
  - Adds page refresh button to workflow detailed page.
  - Adds local user web forms for sign-in and sign-up functionalities for local deployments.
  - Fixes user experience by preventing dots as part of the workflow name to avoid confusion with restart runs.
  - Fixes workflow specification display to show runtime parameters.
  - Fixes file preview functionality experience to allow/disallow certain file formats.
  - Changes Yadage workflow engine to version 0.20.1.
  - Changes CERN HTCondor compute backend to use the new `myschedd` connection library.
  - Changes CERN Slurm compute backend to improve job status detection.
  - Changes documentation to move large parts to [docs.reana.io](http://docs.reana.io).
  - Changes `du` command output format.
  - Changes `logs` command to enhance formatting using marks and colours.
  - Changes `ping` command to perform user access token validation.
  - Changes `diff` command to improve output formatting.
  - Changes defaults to accept both `reana.yaml` and `reana.yml` filenames.
  - Changes from Bravado to requests to improve download performance.
  - Changes file loading to optimise CLI performance.

- Administrators:

  - Adds Helm chart and switches to Helm-based deployment technique instead of using now-deprecated `reana-cluster`.
  - Adds email notification service to inform administrators about system health.
  - Adds announcement configuration option to display any desired text on the web UI.
  - Adds pinning of all Python dependencies allowing to easily rebuild component images at later times.
  - Adds support for local user management and web forms for sign-in and sign-up functionalities.
  - Adds support for database upgrades using Alembic.
  - Changes installation procedures to move database initialisation and admin creation after Helm installation.
  - Changes service exposure to stop exposing unused Invenio-Accounts views.
  - Changes runtime job instantiation into the configured runtime namespace.
  - Changes CVMFS to be read-only mount.

- Developers:

  - Adds several new `reana-dev` commands to help with merging, releasing, unit testing.
  - Changes base image to use Python 3.8 for all REANA cluster components.
  - Changes pre-requisites to node version 12 and latest npm dependencies.
  - Changes back-end code formatting to respect `black` coding style.
  - Changes front-end code formatting to respect updated `prettier` version coding style.
  - Changes test strategy to start PostgreSQL DB container to run tests locally.
  - Changes auto-generated component documentation to single-page layout.

## 0.6.1 (2020-06-09)

- Administrators:

  - Fixes installation troubles for REANA 0.6.x release series by pinning several dependencies.
  - Upgrades REANA-Commons package to latest Kubernetes Python client version.
  - Amends documentation for `minikube start` to include VirtualBox hypervisor explicitly.

## 0.6.0 (2019-12-27)

- Users:

  - Adds support for HTCondor compute backend for all workflow engines (CWL, Serial, Yadage).
  - Adds support for Slurm compute backend for all workflow engines (CWL, Serial, Yadage).
  - Allows to run hybrid analysis pipelines where different parts of the workflow can run on different compute backends (HTCondor, Kubernetes, Slurm).
  - Adds support for Kerberos authentication mechanism for user workflows.
  - Introduces user secrets management commands `secrets-add`, `secrets-list` and `secrets-delete`.
  - Fixes `upload` command behaviour for uploading very large files.
  - Upgrades CWL workflow engine to 1.0.20191022103248.
  - Upgrades Yadage workflow engine to 0.20.0 with Packtivity 0.14.21.
  - Adds support for Python 3.8.
  - See additional changes in [reana-client 0.6.0 release notes](https://reana-client.readthedocs.io/en/latest/changes.html#version-0-6-0-2019-12-27).

- Administrators:

  - Upgrades to Kubernetes 1.16 and moves Traefik installation to Helm 3.0.0.
  - Creates a new Kubernetes service account for REANA with appropriate permissions.
  - Makes database connection details configurable so that REANA can connect to databases external to the cluster.
  - Autogenerates deployment secrets if not provided by administrator at cluster creation time.
  - Adds an interactive mode on cluster initialisation to allow providing deployment secrets.
  - Adds CERN specific Kerberos configuration files and CERN EOS storage support.
  - See additional changes in [reana-cluster 0.6.0 release notes](https://reana-cluster.readthedocs.io/en/latest/changes.html#version-0-6-0-2019-12-27).

- Developers:

  - Modifies the batch workflow runtime pod creation including an instance of job controller running alongside workflow engine using the sidecar pattern.
  - Adds generic job manager class and provides example classes for CERN HTCondor and CERN Slurm clusters.
  - Provides user secrets to the job container runtime tasks.
  - Adds sidecar container to the Kubernetes job pod if Kerberos authentication is required.
  - Refactors job monitoring using the singleton pattern.
  - Enriches `make` behaviour for developer-oriented installations with live code reload changes and debugging.
  - Enriches `git-status` component status reporting for developers.
  - See additional changes in [individual REANA 0.6.0 platform components](https://reana.readthedocs.io/en/latest/administratorguide.html#components).

## 0.5.0 (2019-04-24)

- Users:

  - Allows to explore workflow results by running interactive Jupyter notebook sessions on the workspace files.
  - Allows to declare computing resources needed for workflow runs, such as access to CVMFS repositories.
  - Improves `reana-client` command-line client with new options to stop workflows, diff workflows, move and remove files.
  - Upgrades CWL engine to 1.0.20181118133959.
  - See additional changes in [reana-client 0.5.0 release notes](https://reana-client.readthedocs.io/en/latest/changes.html#version-0-5-0-2019-04-24).

- Administrators:

  - Upgrades to Kubernetes 1.14, Helm 2.13 and Minikube 1.0.
  - Separates cluster infrastructure pods from runtime workflow engine pods that will be created by workflow controller.
  - Introduces configurable CVMFS and CephFS shared volume mounts.
  - Adds support for optional HTTPS protocol termination.
  - Introduces incoming workflow queue for additional safety in case of user storms.
  - Makes infrastructure pods container image slimmer to reduce the memory footprint.
  - See additional changes in [reana-cluster 0.5.0 release notes](https://reana-cluster.readthedocs.io/en/latest/changes.html#version-0-5-0-2019-04-24).

- Developers:

  - Enhances development process by using git-submodule-like behaviour for shared components.
  - Introduces simple Makefile for (fast) local testing and (slow) nightly building purposes.
  - Centralises logging level and common Celery tasks.
  - Adds helpers for test suite fixtures and improves code coverage.
  - See additional changes in [individual REANA 0.5.0 platform components](https://reana.readthedocs.io/en/latest/administratorguide.html#components).

## 0.4.0 (2018-11-07)

- Uses common OpenAPI client in communications between workflow engines and job
  controller.
- Improves AMQP re-connection handling.
- Enhances test suite and increases code coverage.
- Changes license to MIT.

## 0.3.0 (2018-09-27)

- Introduces new Serial workflow engine for simple sequential workflow needs.
- Enhances progress reporting for CWL, Serial and Yadage workflow engines.
- Simplifies `reana-client` command set and usage scenarios.
- Introduces multi-user capabilities with mandatory access tokens.
- Adds support for multi-node clusters using shared CephFS volumes.
- Adds support for Kubernetes 1.11, Minikube 0.28.2.
- Upgrades CWL workflow engine to use latest `cwltool` version.
- Fixes several bugs such as binary file download with Python 3.

## 0.2.0 (2018-04-23)

- Adds support for Common Workflow Language workflows.
- Adds support for persistent user-selected workflow names.
- Enables file and directory input uploading using absolute paths.
- Enriches `reana-client` and `reana-cluster` command set.
- Reduces verbosity level for commands and improves error messages.

## 0.1.0 (2018-01-30)

- Initial public release.
