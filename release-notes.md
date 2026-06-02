:robot: I have created a release *beep* *boop*
---


<details><summary>bigquery-magics: 0.15.1</summary>

## [0.15.1](https://github.com/codyoss/google-cloud-python/compare/bigquery-magics-v0.15.0...bigquery-magics-v0.15.1) (2026-06-02)


### Features

* **bigquery-magics:** deprecate `--engine=bigframes`, run `%load_ext bigframes` and use `%%bqsql` magics instead ([#16573](https://github.com/codyoss/google-cloud-python/issues/16573)) ([dbaf8f5](https://github.com/codyoss/google-cloud-python/commit/dbaf8f54db13d66bc0a2311bff6085615ee38958))
* **bigquery-magics:** drop support for Python 3.9 ([#16587](https://github.com/codyoss/google-cloud-python/issues/16587)) ([961eacd](https://github.com/codyoss/google-cloud-python/commit/961eacd039a2583bc019e0502bc4c1c1d88ab410))
* update minimum google-cloud-bigquery ([#16174](https://github.com/codyoss/google-cloud-python/issues/16174)) ([70e7a09](https://github.com/codyoss/google-cloud-python/commit/70e7a09be15564f9098fc328a5b69b6770800129))


### Bug Fixes

* **bigquery-magics:** Drop support for Python 3.9 ([#16949](https://github.com/codyoss/google-cloud-python/issues/16949)) ([fab4e71](https://github.com/codyoss/google-cloud-python/commit/fab4e7123cd7f7b5d5fef3e8eb923a37d8999388))
</details>

<details><summary>db-dtypes: 1.8.0</summary>

## [1.8.0](https://github.com/codyoss/google-cloud-python/compare/db-dtypes-v1.7.0...db-dtypes-v1.8.0) (2026-06-02)


### Features

* **db-dtypes:** support pandas 3.0 ([#17177](https://github.com/codyoss/google-cloud-python/issues/17177)) ([2086b34](https://github.com/codyoss/google-cloud-python/commit/2086b34d8b3418462c9bc89b96eac779a25a3afd))
* enable mypy session for db-dtypes ([#16689](https://github.com/codyoss/google-cloud-python/issues/16689)) ([856731e](https://github.com/codyoss/google-cloud-python/commit/856731e10a7e8b7531a08f8f799d0321e2fc167d))


### Bug Fixes

* bump pyarrow from 13.0.0 to 14.0.1 in /packages/db-dtypes ([#17182](https://github.com/codyoss/google-cloud-python/issues/17182)) ([49252da](https://github.com/codyoss/google-cloud-python/commit/49252da0f81c63ff7bc384dc3ddd92608e15f459))
* **db-dtypes:** Drop support for Python &lt;= 3.9 ([#16966](https://github.com/codyoss/google-cloud-python/issues/16966)) ([6698861](https://github.com/codyoss/google-cloud-python/commit/66988617e67e9c923d8bcbd4034505ec9a20968f))
</details>

<details><summary>django-google-spanner: 6.0.0</summary>

## [6.0.0](https://github.com/codyoss/google-cloud-python/compare/django-google-spanner-v5.0.0...django-google-spanner-v6.0.0) (2026-06-02)


###   BREAKING CHANGES

* **django-spanner:** support Django 5.2 and deprecate Django 3.2/4.2 ([#16624](https://github.com/codyoss/google-cloud-python/issues/16624))

### Features

* **django-spanner:** support Django 5.2 and deprecate Django 3.2/4.2 ([#16624](https://github.com/codyoss/google-cloud-python/issues/16624)) ([4086982](https://github.com/codyoss/google-cloud-python/commit/4086982861b0214632d53c47ba21d7c83cac8965))
</details>

<details><summary>gapic-generator: 1.35.0</summary>

## [1.35.0](https://github.com/codyoss/google-cloud-python/compare/gapic-generator-v1.34.1...gapic-generator-v1.35.0) (2026-06-02)


### Features

* add `--resource-name-alias` flag to resolve namespace collisions ([#16769](https://github.com/codyoss/google-cloud-python/issues/16769)) ([6fc78e5](https://github.com/codyoss/google-cloud-python/commit/6fc78e58e08c9d5a277d8432f3f9740515b44dee))


### Bug Fixes

* bump idna from 3.14 to 3.15 in /packages/gapic-generator ([#17179](https://github.com/codyoss/google-cloud-python/issues/17179)) ([0f7c68b](https://github.com/codyoss/google-cloud-python/commit/0f7c68bfd437e7f366dacd4080f31e219d7c7090))
* **gapic-generator:** add pragma to `constants.py` to resolve coverage failure and correct `if` block ([#17268](https://github.com/codyoss/google-cloud-python/issues/17268)) ([1436a23](https://github.com/codyoss/google-cloud-python/commit/1436a23c923e799f9909d039e1f418435845565d))
* pass resource aliases to file-level CommonResources ([#16945](https://github.com/codyoss/google-cloud-python/issues/16945)) ([9652a08](https://github.com/codyoss/google-cloud-python/commit/9652a08cb89441fac779eb4fa4d6f48f33b55d3b))
* **project urls:** update incorrect urls in setup.py to point at monorepo vs splitrepo ([#17237](https://github.com/codyoss/google-cloud-python/issues/17237)) ([eaed04b](https://github.com/codyoss/google-cloud-python/commit/eaed04baf3cd356c3811c66e64c277c8841c7563))
* restore messages not attached to rpc in selective_gapic_generation ([#16951](https://github.com/codyoss/google-cloud-python/issues/16951)) ([3ef95d6](https://github.com/codyoss/google-cloud-python/commit/3ef95d61995869318097e414e439da1d6c214d1f))
* **templates:** resolve core dependencies locally and batch pip installs ([5ca8803](https://github.com/codyoss/google-cloud-python/commit/5ca88030476fd6be7a2eceef9c94c4fc76820f40))
* **templates:** resolve core dependencies locally and batch pip installs ([#17032](https://github.com/codyoss/google-cloud-python/issues/17032)) ([5ca8803](https://github.com/codyoss/google-cloud-python/commit/5ca88030476fd6be7a2eceef9c94c4fc76820f40))
</details>

<details><summary>gcp-sphinx-docfx-yaml: 3.3.1</summary>

## [3.3.1](https://github.com/codyoss/google-cloud-python/compare/gcp-sphinx-docfx-yaml-v3.3.0...gcp-sphinx-docfx-yaml-v3.3.1) (2026-06-02)


### Bug Fixes

* replace deprecated `utcfromtimestamp` in google-auth-oauthlib ([#16732](https://github.com/codyoss/google-cloud-python/issues/16732)) ([e1c5af7](https://github.com/codyoss/google-cloud-python/commit/e1c5af76593e8710870393f422715d8387051f4e))
</details>

<details><summary>google-ads-admanager: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-ads-admanager-v0.10.0...google-ads-admanager-v0.10.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
* update API sources and regenerate ([#16998](https://github.com/codyoss/google-cloud-python/issues/16998)) ([cef659d](https://github.com/codyoss/google-cloud-python/commit/cef659d8207939aab3834a32c99a3a2738cb3015))
</details>

<details><summary>google-ads-datamanager: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-ads-datamanager-v0.9.0...google-ads-datamanager-v0.9.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-ads-marketingplatform-admin: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-ads-marketingplatform-admin-v0.6.0...google-ads-marketingplatform-admin-v0.6.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-ai-generativelanguage: 0.12.1</summary>

## [0.12.1](https://github.com/codyoss/google-cloud-python/compare/google-ai-generativelanguage-v0.12.0...google-ai-generativelanguage-v0.12.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-analytics-admin: 0.30.1</summary>

## [0.30.1](https://github.com/codyoss/google-cloud-python/compare/google-analytics-admin-v0.30.0...google-analytics-admin-v0.30.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-analytics-data: 0.23.1</summary>

## [0.23.1](https://github.com/codyoss/google-cloud-python/compare/google-analytics-data-v0.23.0...google-analytics-data-v0.23.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-api-core: 2.31.1</summary>

## [2.31.1](https://github.com/codyoss/google-cloud-python/compare/google-api-core-v2.31.0...google-api-core-v2.31.1) (2026-06-02)


### Bug Fixes

* allow Protobuf 7.x ([#16532](https://github.com/codyoss/google-cloud-python/issues/16532)) ([ffb4b71](https://github.com/codyoss/google-cloud-python/commit/ffb4b712121d04a38399e0bd3dc9773e96798564))
* **api-core:** drop support for Python 3.9 ([#16980](https://github.com/codyoss/google-cloud-python/issues/16980)) ([e5ed472](https://github.com/codyoss/google-cloud-python/commit/e5ed47205cb478a4b6ba8f602b7c7198911d086e))
* bump protobuf from 4.25.8 to 5.29.6 ([#17021](https://github.com/codyoss/google-cloud-python/issues/17021)) ([8f52e9a](https://github.com/codyoss/google-cloud-python/commit/8f52e9ad30b58436480e35d462e9367172bd6656))
* **perf:** avoid repeated scan of entire venv via packages_distributions() at import time ([#16579](https://github.com/codyoss/google-cloud-python/issues/16579)) ([c5728b2](https://github.com/codyoss/google-cloud-python/commit/c5728b24fac3363c10a8cfb315b96d3e6459cf06))
</details>

<details><summary>google-apps-card: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-apps-card-v0.7.0...google-apps-card-v0.7.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-apps-chat: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-apps-chat-v0.10.0...google-apps-chat-v0.10.1) (2026-06-02)


### Features

* A new field `mime_type` is added to message ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* added support for detecting key-value pairs in client provided ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Addition of Section and SectionItem APIs ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* populate the `persisted_data_checksums` field with object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
* Support app authentication with admin-consent scopes for Chat API ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))


### Documentation

* Fix documentation URL AIInference MessageTransform ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* improve wording around `object_checksums` in bidi write object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Update reference documentation for Chat API ListMessages, ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
</details>

<details><summary>google-apps-events-subscriptions: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-apps-events-subscriptions-v0.6.0...google-apps-events-subscriptions-v0.6.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-apps-meet: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-apps-meet-v0.5.0...google-apps-meet-v0.5.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-apps-script-type: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-apps-script-type-v0.8.0...google-apps-script-type-v0.8.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-area120-tables: 0.15.1</summary>

## [0.15.1](https://github.com/codyoss/google-cloud-python/compare/google-area120-tables-v0.15.0...google-area120-tables-v0.15.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-auth-httplib2: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-auth-httplib2-v0.4.0...google-auth-httplib2-v0.4.1) (2026-06-02)


### Bug Fixes

* **google-auth-httplib2:** Drop support for Python 3.7, 3.8, and 3.9 ([#16937](https://github.com/codyoss/google-cloud-python/issues/16937)) ([b4fa220](https://github.com/codyoss/google-cloud-python/commit/b4fa220048f78a76da9d07c4c367e4cbc79360e6))
</details>

<details><summary>google-auth-oauthlib: 1.4.1</summary>

## [1.4.1](https://github.com/codyoss/google-cloud-python/compare/google-auth-oauthlib-v1.4.0...google-auth-oauthlib-v1.4.1) (2026-06-02)


### Bug Fixes

* **google-auth-oauthlib:** Drop support for Python 3.9 ([#16939](https://github.com/codyoss/google-cloud-python/issues/16939)) ([25e2a2d](https://github.com/codyoss/google-cloud-python/commit/25e2a2dcade4bdbac91b6a501604809d8efbba82))
* replace deprecated `utcfromtimestamp` in google-auth-oauthlib ([#16732](https://github.com/codyoss/google-cloud-python/issues/16732)) ([e1c5af7](https://github.com/codyoss/google-cloud-python/commit/e1c5af76593e8710870393f422715d8387051f4e))
</details>

<details><summary>google-cloud-access-approval: 1.21.0</summary>

## [1.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-access-approval-v1.20.0...google-cloud-access-approval-v1.21.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-access-context-manager: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-access-context-manager-v0.6.0...google-cloud-access-context-manager-v0.6.1) (2026-06-02)


### Bug Fixes

* **project urls:** update incorrect urls in setup.py to point at monorepo vs splitrepo ([#17237](https://github.com/codyoss/google-cloud-python/issues/17237)) ([eaed04b](https://github.com/codyoss/google-cloud-python/commit/eaed04baf3cd356c3811c66e64c277c8841c7563))
</details>

<details><summary>google-cloud-advisorynotifications: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-advisorynotifications-v0.7.0...google-cloud-advisorynotifications-v0.7.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-alloydb: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-alloydb-v0.10.0...google-cloud-alloydb-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-alloydb-connectors: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-alloydb-connectors-v0.5.0...google-cloud-alloydb-connectors-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-api-gateway: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-api-gateway-v1.16.0...google-cloud-api-gateway-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-api-keys: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-api-keys-v0.9.0...google-cloud-api-keys-v0.9.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-apigee-connect: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-apigee-connect-v1.16.0...google-cloud-apigee-connect-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-apigee-registry: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-apigee-registry-v0.10.0...google-cloud-apigee-registry-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-apihub: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-apihub-v0.7.0...google-cloud-apihub-v0.7.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-apiregistry: 0.3.1</summary>

## [0.3.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-apiregistry-v0.3.0...google-cloud-apiregistry-v0.3.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-appengine-admin: 1.19.0</summary>

## [1.19.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-appengine-admin-v1.18.0...google-cloud-appengine-admin-v1.19.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-appengine-logging: 1.11.0</summary>

## [1.11.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-appengine-logging-v1.10.0...google-cloud-appengine-logging-v1.11.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-apphub: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-apphub-v0.5.0...google-cloud-apphub-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-appoptimize: 0.2.1</summary>

## [0.2.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-appoptimize-v0.2.0...google-cloud-appoptimize-v0.2.1) (2026-06-02)


### Features

* onboard a new library ([8e92bae](https://github.com/codyoss/google-cloud-python/commit/8e92bae853cc02cd28dd6d98a6ac66723fef1021))
* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-artifact-registry: 1.23.0</summary>

## [1.23.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-artifact-registry-v1.22.0...google-cloud-artifact-registry-v1.23.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-asset: 4.5.0</summary>

## [4.5.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-asset-v4.4.0...google-cloud-asset-v4.5.0) (2026-06-02)


### Features

* regenerate asset w/ dependencies using generator v1.32.0 ([#17153](https://github.com/codyoss/google-cloud-python/issues/17153)) ([ac594a0](https://github.com/codyoss/google-cloud-python/commit/ac594a0d31bcdef08c341a57badce462efcd7684))
</details>

<details><summary>google-cloud-assured-workloads: 2.5.0</summary>

## [2.5.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-assured-workloads-v2.4.0...google-cloud-assured-workloads-v2.5.0) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-audit-log: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-audit-log-v0.6.0...google-cloud-audit-log-v0.6.1) (2026-06-02)


### Bug Fixes

* **project urls:** update incorrect urls in setup.py to point at monorepo vs splitrepo ([#17237](https://github.com/codyoss/google-cloud-python/issues/17237)) ([eaed04b](https://github.com/codyoss/google-cloud-python/commit/eaed04baf3cd356c3811c66e64c277c8841c7563))
</details>

<details><summary>google-cloud-auditmanager: 0.3.1</summary>

## [0.3.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-auditmanager-v0.3.0...google-cloud-auditmanager-v0.3.1) (2026-06-02)


### Features

* regenerate google-cloud-a packages ([#17089](https://github.com/codyoss/google-cloud-python/issues/17089)) ([39c9882](https://github.com/codyoss/google-cloud-python/commit/39c988267529419b03f808d7662ec521258571b4))
</details>

<details><summary>google-cloud-automl: 2.21.0</summary>

## [2.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-automl-v2.20.0...google-cloud-automl-v2.21.0) (2026-06-02)


### Features

* regenerate automl using generator v1.32.0 ([#17143](https://github.com/codyoss/google-cloud-python/issues/17143)) ([5084ef0](https://github.com/codyoss/google-cloud-python/commit/5084ef0071e1763c03db60c80b9ff4f99d688fc7))
</details>

<details><summary>google-cloud-backupdr: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-backupdr-v0.10.0...google-cloud-backupdr-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bare-metal-solution: 1.15.0</summary>

## [1.15.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bare-metal-solution-v1.14.0...google-cloud-bare-metal-solution-v1.15.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-batch: 0.22.1</summary>

## [0.22.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-batch-v0.22.0...google-cloud-batch-v0.22.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-beyondcorp-appconnections: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-beyondcorp-appconnections-v0.8.0...google-cloud-beyondcorp-appconnections-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-beyondcorp-appconnectors: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-beyondcorp-appconnectors-v0.8.0...google-cloud-beyondcorp-appconnectors-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-beyondcorp-appgateways: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-beyondcorp-appgateways-v0.8.0...google-cloud-beyondcorp-appgateways-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-beyondcorp-clientconnectorservices: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-beyondcorp-clientconnectorservices-v0.8.0...google-cloud-beyondcorp-clientconnectorservices-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-beyondcorp-clientgateways: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-beyondcorp-clientgateways-v0.8.0...google-cloud-beyondcorp-clientgateways-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-biglake: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-biglake-v0.4.0...google-cloud-biglake-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-biglake-hive: 0.3.1</summary>

## [0.3.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-biglake-hive-v0.3.0...google-cloud-biglake-hive-v0.3.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-analyticshub: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-analyticshub-v0.9.0...google-cloud-bigquery-analyticshub-v0.9.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-biglake: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-biglake-v0.8.0...google-cloud-bigquery-biglake-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-connection: 1.23.0</summary>

## [1.23.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-connection-v1.22.0...google-cloud-bigquery-connection-v1.23.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-data-exchange: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-data-exchange-v0.9.0...google-cloud-bigquery-data-exchange-v0.9.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-datapolicies: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-datapolicies-v0.10.0...google-cloud-bigquery-datapolicies-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-datatransfer: 3.24.0</summary>

## [3.24.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-datatransfer-v3.23.0...google-cloud-bigquery-datatransfer-v3.24.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-logging: 1.11.0</summary>

## [1.11.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-logging-v1.10.0...google-cloud-bigquery-logging-v1.11.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-migration: 0.15.1</summary>

## [0.15.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-migration-v0.15.0...google-cloud-bigquery-migration-v0.15.1) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-reservation: 1.26.0</summary>

## [1.26.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-reservation-v1.25.0...google-cloud-bigquery-reservation-v1.26.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-bigquery-storage: 2.40.0</summary>

## [2.40.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-bigquery-storage-v2.39.0...google-cloud-bigquery-storage-v2.40.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-billing: 1.21.0</summary>

## [1.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-billing-v1.20.0...google-cloud-billing-v1.21.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-billing-budgets: 1.22.0</summary>

## [1.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-billing-budgets-v1.21.0...google-cloud-billing-budgets-v1.22.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-binary-authorization: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-binary-authorization-v1.17.0...google-cloud-binary-authorization-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-build: 3.38.0</summary>

## [3.38.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-build-v3.37.0...google-cloud-build-v3.38.0) (2026-06-02)


### Features

* regenerate google-cloud-b packages ([#17090](https://github.com/codyoss/google-cloud-python/issues/17090)) ([77d4fcc](https://github.com/codyoss/google-cloud-python/commit/77d4fcc15d1a6d96adb5f2765ecd0fcc47e478bd))
</details>

<details><summary>google-cloud-capacityplanner: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-capacityplanner-v0.5.0...google-cloud-capacityplanner-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-certificate-manager: 1.15.0</summary>

## [1.15.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-certificate-manager-v1.14.0...google-cloud-certificate-manager-v1.15.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-ces: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-ces-v0.6.0...google-cloud-ces-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-channel: 1.29.0</summary>

## [1.29.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-channel-v1.28.0...google-cloud-channel-v1.29.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-chronicle: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-chronicle-v0.6.0...google-cloud-chronicle-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
* update API sources and regenerate ([#16998](https://github.com/codyoss/google-cloud-python/issues/16998)) ([cef659d](https://github.com/codyoss/google-cloud-python/commit/cef659d8207939aab3834a32c99a3a2738cb3015))
</details>

<details><summary>google-cloud-cloudcontrolspartner: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-cloudcontrolspartner-v0.6.0...google-cloud-cloudcontrolspartner-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-cloudsecuritycompliance: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-cloudsecuritycompliance-v0.8.0...google-cloud-cloudsecuritycompliance-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-commerce-consumer-procurement: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-commerce-consumer-procurement-v0.6.0...google-cloud-commerce-consumer-procurement-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-common: 1.11.0</summary>

## [1.11.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-common-v1.10.0...google-cloud-common-v1.11.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-compute: 1.49.0</summary>

## [1.49.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-compute-v1.48.0...google-cloud-compute-v1.49.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-compute-v1beta: 0.12.1</summary>

## [0.12.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-compute-v1beta-v0.12.0...google-cloud-compute-v1beta-v0.12.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-confidentialcomputing: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-confidentialcomputing-v0.10.0...google-cloud-confidentialcomputing-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-config: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-config-v0.7.0...google-cloud-config-v0.7.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-configdelivery: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-configdelivery-v0.5.0...google-cloud-configdelivery-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-contact-center-insights: 1.28.0</summary>

## [1.28.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-contact-center-insights-v1.27.0...google-cloud-contact-center-insights-v1.28.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-container: 2.66.0</summary>

## [2.66.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-container-v2.65.0...google-cloud-container-v2.66.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-containeranalysis: 2.23.0</summary>

## [2.23.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-containeranalysis-v2.22.0...google-cloud-containeranalysis-v2.23.0) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-contentwarehouse: 0.11.1</summary>

## [0.11.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-contentwarehouse-v0.11.0...google-cloud-contentwarehouse-v0.11.1) (2026-06-02)


### Features

* regenerate google-cloud-c packages ([#17091](https://github.com/codyoss/google-cloud-python/issues/17091)) ([1658393](https://github.com/codyoss/google-cloud-python/commit/165839343695fc74d09fc7900d4c55ddcb31a4d8))
</details>

<details><summary>google-cloud-core: 2.6.1</summary>

## [2.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-core-v2.6.0...google-cloud-core-v2.6.1) (2026-06-02)


### Bug Fixes

* **google-cloud-core:** Drop support for Python 3.9 ([#16953](https://github.com/codyoss/google-cloud-python/issues/16953)) ([78a48b0](https://github.com/codyoss/google-cloud-python/commit/78a48b040a2abc0bf19ebe267aba0a1f410df2e6))
</details>

<details><summary>google-cloud-data-fusion: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-data-fusion-v1.17.0...google-cloud-data-fusion-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-data-qna: 0.14.1</summary>

## [0.14.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-data-qna-v0.14.0...google-cloud-data-qna-v0.14.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-databasecenter: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-databasecenter-v0.9.0...google-cloud-databasecenter-v0.9.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-datacatalog: 3.32.0</summary>

## [3.32.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-datacatalog-v3.31.0...google-cloud-datacatalog-v3.32.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-datacatalog-lineage: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-datacatalog-lineage-v0.7.0...google-cloud-datacatalog-lineage-v0.7.1) (2026-06-02)


### Features

* regenerate google-cloud-datacatalog-lineage ([#17148](https://github.com/codyoss/google-cloud-python/issues/17148)) ([e77dc55](https://github.com/codyoss/google-cloud-python/commit/e77dc55f6702d7d7878db8b270a3b6c74a304532))
</details>

<details><summary>google-cloud-datacatalog-lineage-configmanagement: 0.3.1</summary>

## [0.3.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-datacatalog-lineage-configmanagement-v0.3.0...google-cloud-datacatalog-lineage-configmanagement-v0.3.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dataflow-client: 0.14.1</summary>

## [0.14.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dataflow-client-v0.14.0...google-cloud-dataflow-client-v0.14.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dataform: 0.11.1</summary>

## [0.11.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dataform-v0.11.0...google-cloud-dataform-v0.11.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-datalabeling: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-datalabeling-v1.17.0...google-cloud-datalabeling-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dataplex: 2.21.0</summary>

## [2.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dataplex-v2.20.0...google-cloud-dataplex-v2.21.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dataproc: 5.29.0</summary>

## [5.29.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dataproc-v5.28.0...google-cloud-dataproc-v5.29.0) (2026-06-02)


### Features

* Add `Engine` field to support LightningEngine in clusters and add ([919fd4c](https://github.com/codyoss/google-cloud-python/commit/919fd4c2304c0fb732148175f27d5b3b6d7e4212))
* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
* update API sources and regenerate ([#16998](https://github.com/codyoss/google-cloud-python/issues/16998)) ([cef659d](https://github.com/codyoss/google-cloud-python/commit/cef659d8207939aab3834a32c99a3a2738cb3015))
</details>

<details><summary>google-cloud-dataproc-metastore: 1.24.0</summary>

## [1.24.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dataproc-metastore-v1.23.0...google-cloud-dataproc-metastore-v1.24.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-datastore: 2.26.0</summary>

## [2.26.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-datastore-v2.25.0...google-cloud-datastore-v2.26.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-datastream: 1.20.0</summary>

## [1.20.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-datastream-v1.19.0...google-cloud-datastream-v1.20.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-deploy: 2.12.0</summary>

## [2.12.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-deploy-v2.11.0...google-cloud-deploy-v2.12.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-developerconnect: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-developerconnect-v0.6.0...google-cloud-developerconnect-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-devicestreaming: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-devicestreaming-v0.5.0...google-cloud-devicestreaming-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dialogflow: 2.49.0</summary>

## [2.49.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dialogflow-v2.48.0...google-cloud-dialogflow-v2.49.0) (2026-06-02)


### Features

* regenerate google-cloud-dialogflow ([#17129](https://github.com/codyoss/google-cloud-python/issues/17129)) ([b6bb63e](https://github.com/codyoss/google-cloud-python/commit/b6bb63ea353c3828548ab89d742d4b991b98ca9b))
</details>

<details><summary>google-cloud-dialogflow-cx: 2.7.0</summary>

## [2.7.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dialogflow-cx-v2.6.0...google-cloud-dialogflow-cx-v2.7.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-discoveryengine: 0.20.1</summary>

## [0.20.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-discoveryengine-v0.20.0...google-cloud-discoveryengine-v0.20.1) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dlp: 3.38.0</summary>

## [3.38.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dlp-v3.37.0...google-cloud-dlp-v3.38.0) (2026-06-02)


### Features

* A new field `mime_type` is added to message ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* added support for detecting key-value pairs in client provided ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Addition of Section and SectionItem APIs ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* populate the `persisted_data_checksums` field with object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
* Support app authentication with admin-consent scopes for Chat API ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))


### Documentation

* Fix documentation URL AIInference MessageTransform ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* improve wording around `object_checksums` in bidi write object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Update reference documentation for Chat API ListMessages, ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
</details>

<details><summary>google-cloud-dms: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dms-v1.16.0...google-cloud-dms-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-dns: 0.37.1</summary>

## [0.37.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-dns-v0.37.0...google-cloud-dns-v0.37.1) (2026-06-02)


### Bug Fixes

* **dns:** Drop support for Python 3.9 ([#16954](https://github.com/codyoss/google-cloud-python/issues/16954)) ([5975c48](https://github.com/codyoss/google-cloud-python/commit/5975c48186dd8798b172ac442fd55bc7fece1612))
</details>

<details><summary>google-cloud-documentai: 3.16.0</summary>

## [3.16.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-documentai-v3.15.0...google-cloud-documentai-v3.16.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-documentai-toolbox: 0.17.1</summary>

## [0.17.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-documentai-toolbox-v0.17.0...google-cloud-documentai-toolbox-v0.17.1) (2026-06-02)


### Bug Fixes

* **documentai-toolbox:** Drop support for Python &lt;= 3.9 ([#16967](https://github.com/codyoss/google-cloud-python/issues/16967)) ([8fa321e](https://github.com/codyoss/google-cloud-python/commit/8fa321e77e7ce48d23dc565f35a99c7b1432c012))
</details>

<details><summary>google-cloud-domains: 1.15.0</summary>

## [1.15.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-domains-v1.14.0...google-cloud-domains-v1.15.0) (2026-06-02)


### Features

* regenerate google-cloud-d packages ([#17092](https://github.com/codyoss/google-cloud-python/issues/17092)) ([d49a2b9](https://github.com/codyoss/google-cloud-python/commit/d49a2b9412b4ee9105125db36104a3e18344e0ad))
</details>

<details><summary>google-cloud-edgecontainer: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-edgecontainer-v0.8.0...google-cloud-edgecontainer-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-edgenetwork: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-edgenetwork-v0.5.0...google-cloud-edgenetwork-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-enterpriseknowledgegraph: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-enterpriseknowledgegraph-v0.6.0...google-cloud-enterpriseknowledgegraph-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-error-reporting: 1.16.0</summary>

## [1.16.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-error-reporting-v1.15.0...google-cloud-error-reporting-v1.16.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-essential-contacts: 1.14.0</summary>

## [1.14.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-essential-contacts-v1.13.0...google-cloud-essential-contacts-v1.14.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-eventarc: 1.21.0</summary>

## [1.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-eventarc-v1.20.0...google-cloud-eventarc-v1.21.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-eventarc-publishing: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-eventarc-publishing-v0.10.0...google-cloud-eventarc-publishing-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-filestore: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-filestore-v1.16.0...google-cloud-filestore-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-financialservices: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-financialservices-v0.4.0...google-cloud-financialservices-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-functions: 1.24.0</summary>

## [1.24.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-functions-v1.23.0...google-cloud-functions-v1.24.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-gdchardwaremanagement: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gdchardwaremanagement-v0.5.0...google-cloud-gdchardwaremanagement-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-geminidataanalytics: 0.14.0</summary>

## [0.14.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-geminidataanalytics-v0.13.0...google-cloud-geminidataanalytics-v0.14.0) (2026-06-02)


###   BREAKING CHANGES

* **geminidataanalytics:** generate and default to v1 ([#17007](https://github.com/codyoss/google-cloud-python/issues/17007))

### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))


### Bug Fixes

* **geminidataanalytics:** generate and default to v1 ([#17007](https://github.com/codyoss/google-cloud-python/issues/17007)) ([3820d9d](https://github.com/codyoss/google-cloud-python/commit/3820d9d3b5c201ea9ba6ce129fd7064cba02e23c))
</details>

<details><summary>google-cloud-gke-backup: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gke-backup-v0.8.0...google-cloud-gke-backup-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-gke-connect-gateway: 0.13.1</summary>

## [0.13.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gke-connect-gateway-v0.13.0...google-cloud-gke-connect-gateway-v0.13.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-gke-hub: 1.25.0</summary>

## [1.25.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gke-hub-v1.24.0...google-cloud-gke-hub-v1.25.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-gke-multicloud: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gke-multicloud-v0.9.0...google-cloud-gke-multicloud-v0.9.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-gkerecommender: 0.3.1</summary>

## [0.3.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gkerecommender-v0.3.0...google-cloud-gkerecommender-v0.3.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-gsuiteaddons: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-gsuiteaddons-v0.5.0...google-cloud-gsuiteaddons-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-hypercomputecluster: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-hypercomputecluster-v0.4.0...google-cloud-hypercomputecluster-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-iam: 2.24.0</summary>

## [2.24.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-iam-v2.23.0...google-cloud-iam-v2.24.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-iam-logging: 1.8.0</summary>

## [1.8.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-iam-logging-v1.7.0...google-cloud-iam-logging-v1.8.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-iamconnectorcredentials: 0.1.1</summary>

## [0.1.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-iamconnectorcredentials-v0.1.0...google-cloud-iamconnectorcredentials-v0.1.1) (2026-06-02)


### Features

* onboard a new library ([2a3458c](https://github.com/codyoss/google-cloud-python/commit/2a3458c8d0d6bb85236cd744baecbe559fb1daf5))
* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-iap: 1.22.0</summary>

## [1.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-iap-v1.21.0...google-cloud-iap-v1.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-ids: 1.14.0</summary>

## [1.14.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-ids-v1.13.0...google-cloud-ids-v1.14.0) (2026-06-02)


### Features

* regenerate google-cloud-[e-i] packages ([#17079](https://github.com/codyoss/google-cloud-python/issues/17079)) ([5239b18](https://github.com/codyoss/google-cloud-python/commit/5239b1814f216676bf02dea08726313ad355439d))
</details>

<details><summary>google-cloud-kms: 3.14.0</summary>

## [3.14.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-kms-v3.13.0...google-cloud-kms-v3.14.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-kms-inventory: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-kms-inventory-v0.6.0...google-cloud-kms-inventory-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-language: 2.21.0</summary>

## [2.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-language-v2.20.0...google-cloud-language-v2.21.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-licensemanager: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-licensemanager-v0.4.0...google-cloud-licensemanager-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-life-sciences: 0.12.1</summary>

## [0.12.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-life-sciences-v0.12.0...google-cloud-life-sciences-v0.12.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-locationfinder: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-locationfinder-v0.4.0...google-cloud-locationfinder-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-logging: 3.17.0</summary>

## [3.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-logging-v3.16.0...google-cloud-logging-v3.17.0) (2026-06-02)


### Features

* **logging:** drop support for Python 3.7, 3.8, and 3.9 runtimes ([#17276](https://github.com/codyoss/google-cloud-python/issues/17276)) ([014e951](https://github.com/codyoss/google-cloud-python/commit/014e951b6a1a07cb25baf4286e433a0c28783314))
* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-lustre: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-lustre-v0.4.0...google-cloud-lustre-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-maintenance-api: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-maintenance-api-v0.4.0...google-cloud-maintenance-api-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-managed-identities: 1.16.0</summary>

## [1.16.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-managed-identities-v1.15.0...google-cloud-managed-identities-v1.16.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-managedkafka: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-managedkafka-v0.4.0...google-cloud-managedkafka-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-managedkafka-schemaregistry: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-managedkafka-schemaregistry-v0.4.0...google-cloud-managedkafka-schemaregistry-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-media-translation: 0.14.1</summary>

## [0.14.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-media-translation-v0.14.0...google-cloud-media-translation-v0.14.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-memcache: 1.16.0</summary>

## [1.16.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-memcache-v1.15.0...google-cloud-memcache-v1.16.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-memorystore: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-memorystore-v0.5.0...google-cloud-memorystore-v0.5.1) (2026-06-02)


### Features

* A new field `mime_type` is added to message ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* added support for detecting key-value pairs in client provided ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Addition of Section and SectionItem APIs ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* **memorystore:** enable gRPC transport ([#16927](https://github.com/codyoss/google-cloud-python/issues/16927)) ([71b73e5](https://github.com/codyoss/google-cloud-python/commit/71b73e5407e5a5d1d3f57a80d478b345d128ee1d))
* populate the `persisted_data_checksums` field with object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
* Support app authentication with admin-consent scopes for Chat API ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))


### Documentation

* Fix documentation URL AIInference MessageTransform ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* improve wording around `object_checksums` in bidi write object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Update reference documentation for Chat API ListMessages, ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
</details>

<details><summary>google-cloud-migrationcenter: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-migrationcenter-v0.4.0...google-cloud-migrationcenter-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-modelarmor: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-modelarmor-v0.6.0...google-cloud-modelarmor-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-monitoring: 2.32.0</summary>

## [2.32.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-monitoring-v2.31.0...google-cloud-monitoring-v2.32.0) (2026-06-02)


### Features

* regenerate monitoring using generator v1.32.0 ([#17165](https://github.com/codyoss/google-cloud-python/issues/17165)) ([042dc5c](https://github.com/codyoss/google-cloud-python/commit/042dc5c369138ca0d3c957c3234561aafa6bde78))
</details>

<details><summary>google-cloud-monitoring-dashboards: 2.22.0</summary>

## [2.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-monitoring-dashboards-v2.21.0...google-cloud-monitoring-dashboards-v2.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-monitoring-metrics-scopes: 1.13.0</summary>

## [1.13.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-monitoring-metrics-scopes-v1.12.0...google-cloud-monitoring-metrics-scopes-v1.13.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-ndb: 2.6.0</summary>

## [2.6.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-ndb-v2.5.0...google-cloud-ndb-v2.6.0) (2026-06-02)


### Features

* enable mypy session for ndb ([#16691](https://github.com/codyoss/google-cloud-python/issues/16691)) ([192ccc5](https://github.com/codyoss/google-cloud-python/commit/192ccc52a030a59f7e2c49ed9701130156d73d6f))


### Bug Fixes

* allow redis 7.x ([#16533](https://github.com/codyoss/google-cloud-python/issues/16533)) ([4c541cf](https://github.com/codyoss/google-cloud-python/commit/4c541cf2a364ef7ba39bc48c0a6a063a9334d31a))
* **ndb:** Drop support for Python 3.9 ([#16950](https://github.com/codyoss/google-cloud-python/issues/16950)) ([d37a953](https://github.com/codyoss/google-cloud-python/commit/d37a95301da1db1ee1be273d2ac9af320c91809f))
</details>

<details><summary>google-cloud-netapp: 0.10.1</summary>

## [0.10.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-netapp-v0.10.0...google-cloud-netapp-v0.10.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-network-connectivity: 2.16.0</summary>

## [2.16.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-network-connectivity-v2.15.0...google-cloud-network-connectivity-v2.16.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-network-management: 1.36.0</summary>

## [1.36.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-network-management-v1.35.0...google-cloud-network-management-v1.36.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-network-security: 0.13.1</summary>

## [0.13.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-network-security-v0.13.0...google-cloud-network-security-v0.13.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-network-services: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-network-services-v0.9.0...google-cloud-network-services-v0.9.1) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-notebooks: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-notebooks-v1.16.0...google-cloud-notebooks-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-[k-n] packages ([#17074](https://github.com/codyoss/google-cloud-python/issues/17074)) ([ec54f78](https://github.com/codyoss/google-cloud-python/commit/ec54f78e37bb3b48e0794d544784b99fa13d6f85))
</details>

<details><summary>google-cloud-optimization: 1.15.0</summary>

## [1.15.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-optimization-v1.14.0...google-cloud-optimization-v1.15.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-oracledatabase: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-oracledatabase-v0.5.0...google-cloud-oracledatabase-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-orchestration-airflow: 1.22.0</summary>

## [1.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-orchestration-airflow-v1.21.0...google-cloud-orchestration-airflow-v1.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-org-policy: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-org-policy-v1.17.0...google-cloud-org-policy-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-os-config: 1.25.0</summary>

## [1.25.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-os-config-v1.24.0...google-cloud-os-config-v1.25.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-os-login: 2.22.0</summary>

## [2.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-os-login-v2.21.0...google-cloud-os-login-v2.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-parallelstore: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-parallelstore-v0.6.0...google-cloud-parallelstore-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-parametermanager: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-parametermanager-v0.4.0...google-cloud-parametermanager-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-phishing-protection: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-phishing-protection-v1.17.0...google-cloud-phishing-protection-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-policy-troubleshooter: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-policy-troubleshooter-v1.16.0...google-cloud-policy-troubleshooter-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-policysimulator: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-policysimulator-v0.4.0...google-cloud-policysimulator-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-policytroubleshooter-iam: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-policytroubleshooter-iam-v0.5.0...google-cloud-policytroubleshooter-iam-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-private-ca: 1.19.0</summary>

## [1.19.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-private-ca-v1.18.0...google-cloud-private-ca-v1.19.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-private-catalog: 0.12.1</summary>

## [0.12.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-private-catalog-v0.12.0...google-cloud-private-catalog-v0.12.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-privilegedaccessmanager: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-privilegedaccessmanager-v0.4.0...google-cloud-privilegedaccessmanager-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-pubsub: 2.40.0</summary>

## [2.40.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-pubsub-v2.39.0...google-cloud-pubsub-v2.40.0) (2026-06-02)


### Features

* A new field `mime_type` is added to message ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* added support for detecting key-value pairs in client provided ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Addition of Section and SectionItem APIs ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* populate the `persisted_data_checksums` field with object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* **pubsub:** regenerate pubsub library using gapic-generator v1.32.0 ([#17167](https://github.com/codyoss/google-cloud-python/issues/17167)) ([01d3127](https://github.com/codyoss/google-cloud-python/commit/01d3127d6c96cf87f52e1304eeb9f788226bf066))
* Support app authentication with admin-consent scopes for Chat API ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))


### Bug Fixes

* resolve issue with pubsub generation ([#17219](https://github.com/codyoss/google-cloud-python/issues/17219)) ([b21c1d4](https://github.com/codyoss/google-cloud-python/commit/b21c1d447e41d1be93da313e01e75646a942e607))


### Documentation

* Fix documentation URL AIInference MessageTransform ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* improve wording around `object_checksums` in bidi write object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Update reference documentation for Chat API ListMessages, ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
</details>

<details><summary>google-cloud-quotas: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-quotas-v0.6.0...google-cloud-quotas-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-rapidmigrationassessment: 0.4.1</summary>

## [0.4.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-rapidmigrationassessment-v0.4.0...google-cloud-rapidmigrationassessment-v0.4.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-recaptcha-enterprise: 1.32.0</summary>

## [1.32.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-recaptcha-enterprise-v1.31.0...google-cloud-recaptcha-enterprise-v1.32.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-recommendations-ai: 0.13.1</summary>

## [0.13.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-recommendations-ai-v0.13.0...google-cloud-recommendations-ai-v0.13.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-recommender: 2.22.0</summary>

## [2.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-recommender-v2.21.0...google-cloud-recommender-v2.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-redis: 2.22.0</summary>

## [2.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-redis-v2.21.0...google-cloud-redis-v2.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-redis-cluster: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-redis-cluster-v0.5.0...google-cloud-redis-cluster-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-resource-manager: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-resource-manager-v1.17.0...google-cloud-resource-manager-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-retail: 2.11.0</summary>

## [2.11.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-retail-v2.10.0...google-cloud-retail-v2.11.0) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-run: 0.16.1</summary>

## [0.16.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-run-v0.16.0...google-cloud-run-v0.16.1) (2026-06-02)


### Features

* regenerate google-cloud-[o-r] packages ([#17075](https://github.com/codyoss/google-cloud-python/issues/17075)) ([f4bd018](https://github.com/codyoss/google-cloud-python/commit/f4bd0182d808ae73c3c6981e6ce3d565f78a6051))
</details>

<details><summary>google-cloud-runtimeconfig: 0.37.1</summary>

## [0.37.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-runtimeconfig-v0.37.0...google-cloud-runtimeconfig-v0.37.1) (2026-06-02)


### Bug Fixes

* **runtimeconfig:** Drop support for Python 3.9 ([#16947](https://github.com/codyoss/google-cloud-python/issues/16947)) ([e7efd90](https://github.com/codyoss/google-cloud-python/commit/e7efd90d816eb5a6f7db653f1b60e1e14e918dfe))
</details>

<details><summary>google-cloud-saasplatform-saasservicemgmt: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-saasplatform-saasservicemgmt-v0.7.0...google-cloud-saasplatform-saasservicemgmt-v0.7.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-scheduler: 2.21.0</summary>

## [2.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-scheduler-v2.20.0...google-cloud-scheduler-v2.21.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-secret-manager: 2.30.0</summary>

## [2.30.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-secret-manager-v2.29.0...google-cloud-secret-manager-v2.30.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))


### Bug Fixes

* add some cool docs ([4b418fd](https://github.com/codyoss/google-cloud-python/commit/4b418fda3fdf317760840ece7c51c552ab64ab13))
</details>

<details><summary>google-cloud-securesourcemanager: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-securesourcemanager-v0.6.0...google-cloud-securesourcemanager-v0.6.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-security-publicca: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-security-publicca-v0.7.0...google-cloud-security-publicca-v0.7.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-securitycenter: 1.46.0</summary>

## [1.46.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-securitycenter-v1.45.0...google-cloud-securitycenter-v1.46.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-securitycentermanagement: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-securitycentermanagement-v0.5.0...google-cloud-securitycentermanagement-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-service-control: 1.21.0</summary>

## [1.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-service-control-v1.20.0...google-cloud-service-control-v1.21.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-service-directory: 1.19.0</summary>

## [1.19.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-service-directory-v1.18.0...google-cloud-service-directory-v1.19.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-service-management: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-service-management-v1.17.0...google-cloud-service-management-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-service-usage: 1.18.0</summary>

## [1.18.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-service-usage-v1.17.0...google-cloud-service-usage-v1.18.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-servicehealth: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-servicehealth-v0.5.0...google-cloud-servicehealth-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-shell: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-shell-v1.16.0...google-cloud-shell-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-source-context: 1.12.0</summary>

## [1.12.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-source-context-v1.11.0...google-cloud-source-context-v1.12.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-spanner: 3.68.0</summary>

## [3.68.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-spanner-v3.67.0...google-cloud-spanner-v3.68.0) (2026-06-02)


### Features

* Add last statement option samples ([#16499](https://github.com/codyoss/google-cloud-python/issues/16499)) ([ee09805](https://github.com/codyoss/google-cloud-python/commit/ee098051f562dd2f26743a622b52605e6cef19f1))
* **spanner:** add asynchronous code snippets and minor cleanup changes ([#17337](https://github.com/codyoss/google-cloud-python/issues/17337)) ([d6aaf61](https://github.com/codyoss/google-cloud-python/commit/d6aaf610fa97b76077cacade2fca306dbe1e8c80))
* **spanner:** drop Python 3.7-3.9 support and regenerate ([#17169](https://github.com/codyoss/google-cloud-python/issues/17169)) ([2408166](https://github.com/codyoss/google-cloud-python/commit/2408166fec2fac7fc19f15d89f1b7bbb329c5ace))
* **spanner:** drop python runtime 3.9  ([#17070](https://github.com/codyoss/google-cloud-python/issues/17070)) ([cddabc0](https://github.com/codyoss/google-cloud-python/commit/cddabc0f48c198f7866756fc1f8e45b5b208731d))
* **spanner:** log client configuration at startup ([#17040](https://github.com/codyoss/google-cloud-python/issues/17040)) ([a830a78](https://github.com/codyoss/google-cloud-python/commit/a830a78547c4fba545f8789fecfac97107ca799f))
* update API sources and regenerate ([#16998](https://github.com/codyoss/google-cloud-python/issues/16998)) ([cef659d](https://github.com/codyoss/google-cloud-python/commit/cef659d8207939aab3834a32c99a3a2738cb3015))


### Bug Fixes

* **google-cloud-spanner:** address compatibility issues with spanner experimental ([#16593](https://github.com/codyoss/google-cloud-python/issues/16593)) ([aec1073](https://github.com/codyoss/google-cloud-python/commit/aec10730a871566b5a4a4c418e35f1ea50a40ccd))
* **spanner_dbapi:** replace insecure pickle with json for partition deserialization ([#17014](https://github.com/codyoss/google-cloud-python/issues/17014)) ([86e57cb](https://github.com/codyoss/google-cloud-python/commit/86e57cb9b6ec4266773e99e8a5f60eda78cd1e11))
* **spanner:** catch recursion and decode errors in proto parsing to p& ([#16561](https://github.com/codyoss/google-cloud-python/issues/16561)) ([70dc6bf](https://github.com/codyoss/google-cloud-python/commit/70dc6bfc328de37abe96afbf5555e484fdc80058))
</details>

<details><summary>google-cloud-speech: 2.41.0</summary>

## [2.41.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-speech-v2.40.0...google-cloud-speech-v2.41.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-storage: 3.12.0</summary>

## [3.12.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-storage-v3.11.0...google-cloud-storage-v3.12.0) (2026-06-02)


### Features

* A new field `mime_type` is added to message ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* add fixed-key metadata support in AAOW ([#16817](https://github.com/codyoss/google-cloud-python/issues/16817)) ([28487f5](https://github.com/codyoss/google-cloud-python/commit/28487f5cff2893a71a42a25a7939c9f9917b3a2b))
* added support for detecting key-value pairs in client provided ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Addition of Section and SectionItem APIs ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* implement AsyncMultiRangeDownloader with multiplexed bidi-gRPC stream support ([#16528](https://github.com/codyoss/google-cloud-python/issues/16528)) ([493df65](https://github.com/codyoss/google-cloud-python/commit/493df65bcdb028c1f10ccfeb529f4cc1a9c14c16))
* populate the `persisted_data_checksums` field with object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* **storage:** Add delete_source_objects optional parameter to compose API ([#17163](https://github.com/codyoss/google-cloud-python/issues/17163)) ([16ab4c2](https://github.com/codyoss/google-cloud-python/commit/16ab4c269be673dd9d7ebefe804f5ed99789e0a0))
* **storage:** add object contexts in Python GCS SDK ([#17039](https://github.com/codyoss/google-cloud-python/issues/17039)) ([15ec8bd](https://github.com/codyoss/google-cloud-python/commit/15ec8bd7d8568e8981f8056374c49e758c51f6e2))
* **storage:** Add support for blob object in AAOW ([#16577](https://github.com/codyoss/google-cloud-python/issues/16577)) ([3271831](https://github.com/codyoss/google-cloud-python/commit/32718318615a002f074ebd92208043b3d6ccbee9))
* **storage:** drop Python 3.7-3.9 support and regenerate ([#17178](https://github.com/codyoss/google-cloud-python/issues/17178)) ([c804a93](https://github.com/codyoss/google-cloud-python/commit/c804a93570c5f85f1a957df0e1f32b28d5752dbe))
* **storage:** Enhance Otel Span Attributes with BucketId and Location details for every Bucket/Blob operation ([a0da993](https://github.com/codyoss/google-cloud-python/commit/a0da993d87eb7691e78690c0ca4316805a497749))
* Support app authentication with admin-consent scopes for Chat API ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))


### Bug Fixes

* propagate quota_project_id and api_endpoint in AsyncGrpcClient ([#16731](https://github.com/codyoss/google-cloud-python/issues/16731)) ([b8b457a](https://github.com/codyoss/google-cloud-python/commit/b8b457aaad0c2593dae8762f70316729133ac1a8))
* **storage:** fix test_mrd_concurrent_download_cancellation ([#17151](https://github.com/codyoss/google-cloud-python/issues/17151)) ([9ba049a](https://github.com/codyoss/google-cloud-python/commit/9ba049aaef9b7be67ee2443247f59212823da977))
* **storage:** test_transfer_manager counts unwanted deprecated warnings ([#16744](https://github.com/codyoss/google-cloud-python/issues/16744)) ([955a91b](https://github.com/codyoss/google-cloud-python/commit/955a91b975d49d2598391c1f7edd8cbdbd2e4d7a))


### Performance Improvements

* add multiplexing performance tests for AsyncMultiRangeDownloader ([#16501](https://github.com/codyoss/google-cloud-python/issues/16501)) ([2096991](https://github.com/codyoss/google-cloud-python/commit/20969910b4820dbe7d29ce28c5f9e50464fd2dde))
* improve microbenchmark throughput calculation accuracy ([#16838](https://github.com/codyoss/google-cloud-python/issues/16838)) ([2bfa5d6](https://github.com/codyoss/google-cloud-python/commit/2bfa5d6634a065d50cf3b7887ab929085078d9d5))
* **storage:** implement fast-path for queue delivery in _StreamMultiplexer ([#16718](https://github.com/codyoss/google-cloud-python/issues/16718)) ([7073be1](https://github.com/codyoss/google-cloud-python/commit/7073be16dd4a6eb65209478f6bee142c19472e37))
* **storage:** use google_crc32c.value for checksums ([#16719](https://github.com/codyoss/google-cloud-python/issues/16719)) ([c6461a4](https://github.com/codyoss/google-cloud-python/commit/c6461a42850fa6e86976954e894b6a3d2da6c78c))
* **storage:** use google_crc32c.value() for simpler crc32c calculation ([#16761](https://github.com/codyoss/google-cloud-python/issues/16761)) ([c9846c9](https://github.com/codyoss/google-cloud-python/commit/c9846c927e9221a815417263f641fabae99209ce))


### Documentation

* Fix documentation URL AIInference MessageTransform ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* improve wording around `object_checksums` in bidi write object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Update reference documentation for Chat API ListMessages, ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
</details>

<details><summary>google-cloud-storage-control: 1.13.0</summary>

## [1.13.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-storage-control-v1.12.0...google-cloud-storage-control-v1.13.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-storage-transfer: 1.22.0</summary>

## [1.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-storage-transfer-v1.21.0...google-cloud-storage-transfer-v1.22.0) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-storagebatchoperations: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-storagebatchoperations-v0.8.0...google-cloud-storagebatchoperations-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-storageinsights: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-storageinsights-v0.5.0...google-cloud-storageinsights-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-support: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-support-v0.5.0...google-cloud-support-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-s packages ([#17086](https://github.com/codyoss/google-cloud-python/issues/17086)) ([40b522a](https://github.com/codyoss/google-cloud-python/commit/40b522a8473dec7ade45113ddd44ccd960803c45))
</details>

<details><summary>google-cloud-talent: 2.21.0</summary>

## [2.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-talent-v2.20.0...google-cloud-talent-v2.21.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-tasks: 2.23.0</summary>

## [2.23.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-tasks-v2.22.0...google-cloud-tasks-v2.23.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-telcoautomation: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-telcoautomation-v0.5.0...google-cloud-telcoautomation-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-testutils: 1.9.1</summary>

## [1.9.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-testutils-v1.9.0...google-cloud-testutils-v1.9.1) (2026-06-02)


### Bug Fixes

* **testutils:** Drop support for Python 3.9 ([#16948](https://github.com/codyoss/google-cloud-python/issues/16948)) ([cdc5dd5](https://github.com/codyoss/google-cloud-python/commit/cdc5dd5da9afc73fd7f9d0466a72b469d439aa78))
* **testutils:** support != exclusion constraints in lower-bound-checker ([#17269](https://github.com/codyoss/google-cloud-python/issues/17269)) ([65da316](https://github.com/codyoss/google-cloud-python/commit/65da31654ad41065132fecbcf7646e0f2b336256))
</details>

<details><summary>google-cloud-texttospeech: 2.37.0</summary>

## [2.37.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-texttospeech-v2.36.0...google-cloud-texttospeech-v2.37.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-tpu: 1.27.0</summary>

## [1.27.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-tpu-v1.26.0...google-cloud-tpu-v1.27.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-trace: 1.20.0</summary>

## [1.20.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-trace-v1.19.0...google-cloud-trace-v1.20.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-translate: 3.27.0</summary>

## [3.27.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-translate-v3.26.0...google-cloud-translate-v3.27.0) (2026-06-02)


### Features

* A new field `mime_type` is added to message ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* added support for detecting key-value pairs in client provided ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Addition of Section and SectionItem APIs ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* populate the `persisted_data_checksums` field with object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
* Support app authentication with admin-consent scopes for Chat API ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))


### Documentation

* Fix documentation URL AIInference MessageTransform ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* improve wording around `object_checksums` in bidi write object ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
* Update reference documentation for Chat API ListMessages, ([56ccbd8](https://github.com/codyoss/google-cloud-python/commit/56ccbd8612b6790b0477bf8d777080061072e745))
</details>

<details><summary>google-cloud-vectorsearch: 0.11.1</summary>

## [0.11.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-vectorsearch-v0.11.0...google-cloud-vectorsearch-v0.11.1) (2026-06-02)


### Features

* **google-cloud-vectorsearch:** regenerate library ([#16626](https://github.com/codyoss/google-cloud-python/issues/16626)) ([d80f278](https://github.com/codyoss/google-cloud-python/commit/d80f278ed08501f6a9533e7e1a2a922ce8a21d08))
* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
* update API sources and regenerate ([#16998](https://github.com/codyoss/google-cloud-python/issues/16998)) ([cef659d](https://github.com/codyoss/google-cloud-python/commit/cef659d8207939aab3834a32c99a3a2738cb3015))
</details>

<details><summary>google-cloud-video-live-stream: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-video-live-stream-v1.16.0...google-cloud-video-live-stream-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-video-stitcher: 0.11.1</summary>

## [0.11.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-video-stitcher-v0.11.0...google-cloud-video-stitcher-v0.11.1) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-video-transcoder: 1.21.0</summary>

## [1.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-video-transcoder-v1.20.0...google-cloud-video-transcoder-v1.21.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-videointelligence: 2.20.0</summary>

## [2.20.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-videointelligence-v2.19.0...google-cloud-videointelligence-v2.20.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-vision: 3.15.0</summary>

## [3.15.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-vision-v3.14.0...google-cloud-vision-v3.15.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-visionai: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-visionai-v0.5.0...google-cloud-visionai-v0.5.1) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-vm-migration: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-vm-migration-v1.16.0...google-cloud-vm-migration-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-vmwareengine: 1.12.0</summary>

## [1.12.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-vmwareengine-v1.11.0...google-cloud-vmwareengine-v1.12.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-vpc-access: 1.17.0</summary>

## [1.17.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-vpc-access-v1.16.0...google-cloud-vpc-access-v1.17.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-webrisk: 1.22.0</summary>

## [1.22.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-webrisk-v1.21.0...google-cloud-webrisk-v1.22.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-websecurityscanner: 1.21.0</summary>

## [1.21.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-websecurityscanner-v1.20.0...google-cloud-websecurityscanner-v1.21.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-workflows: 1.23.0</summary>

## [1.23.0](https://github.com/codyoss/google-cloud-python/compare/google-cloud-workflows-v1.22.0...google-cloud-workflows-v1.23.0) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-workloadmanager: 0.2.1</summary>

## [0.2.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-workloadmanager-v0.2.0...google-cloud-workloadmanager-v0.2.1) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-cloud-workstations: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-cloud-workstations-v0.8.0...google-cloud-workstations-v0.8.1) (2026-06-02)


### Features

* regenerate google-cloud-[t-w] packages ([#17076](https://github.com/codyoss/google-cloud-python/issues/17076)) ([928a03c](https://github.com/codyoss/google-cloud-python/commit/928a03ce41fbcb82398636e89f840c00c7749cf8))
</details>

<details><summary>google-geo-type: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-geo-type-v0.7.0...google-geo-type-v0.7.1) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>google-maps-addressvalidation: 0.7.1</summary>

## [0.7.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-addressvalidation-v0.7.0...google-maps-addressvalidation-v0.7.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-areainsights: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-areainsights-v0.5.0...google-maps-areainsights-v0.5.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-fleetengine: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-fleetengine-v0.6.0...google-maps-fleetengine-v0.6.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-fleetengine-delivery: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-fleetengine-delivery-v0.6.0...google-maps-fleetengine-delivery-v0.6.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-geocode: 0.3.1</summary>

## [0.3.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-geocode-v0.3.0...google-maps-geocode-v0.3.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-mapmanagement: 0.1.1</summary>

## [0.1.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-mapmanagement-v0.1.0...google-maps-mapmanagement-v0.1.1) (2026-06-02)


### Features

* **mapmanagement:** add google-maps-mapmanagement ([#16930](https://github.com/codyoss/google-cloud-python/issues/16930)) ([19331c9](https://github.com/codyoss/google-cloud-python/commit/19331c96e486286ae0d23976559ff62bd1458ed3))
* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-mapsplatformdatasets: 0.8.1</summary>

## [0.8.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-mapsplatformdatasets-v0.8.0...google-maps-mapsplatformdatasets-v0.8.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-navconnect: 0.2.1</summary>

## [0.2.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-navconnect-v0.2.0...google-maps-navconnect-v0.2.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-places: 0.9.1</summary>

## [0.9.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-places-v0.9.0...google-maps-places-v0.9.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-routeoptimization: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-routeoptimization-v0.5.0...google-maps-routeoptimization-v0.5.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-routing: 0.11.1</summary>

## [0.11.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-routing-v0.11.0...google-maps-routing-v0.11.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-maps-solar: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-maps-solar-v0.6.0...google-maps-solar-v0.6.1) (2026-06-02)


### Features

* regenerate google-maps packages ([#17073](https://github.com/codyoss/google-cloud-python/issues/17073)) ([bd31a8c](https://github.com/codyoss/google-cloud-python/commit/bd31a8c7fd338723ac201ad1b5d0f2a1861f8925))
</details>

<details><summary>google-resumable-media: 2.10.1</summary>

## [2.10.1](https://github.com/codyoss/google-cloud-python/compare/google-resumable-media-v2.10.0...google-resumable-media-v2.10.1) (2026-06-02)


### Bug Fixes

* **google-resumable-media:** Drop support for Python 3.9 ([#16938](https://github.com/codyoss/google-cloud-python/issues/16938)) ([33b5505](https://github.com/codyoss/google-cloud-python/commit/33b55050e75d956efb4c3c4438f339e46e8e9782))
* **project urls:** update incorrect urls in setup.py to point at monorepo vs splitrepo ([#17237](https://github.com/codyoss/google-cloud-python/issues/17237)) ([eaed04b](https://github.com/codyoss/google-cloud-python/commit/eaed04baf3cd356c3811c66e64c277c8841c7563))
</details>

<details><summary>google-shopping-css: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-shopping-css-v0.6.0...google-shopping-css-v0.6.1) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-accounts: 1.7.0</summary>

## [1.7.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-accounts-v1.6.0...google-shopping-merchant-accounts-v1.7.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-conversions: 1.5.0</summary>

## [1.5.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-conversions-v1.4.0...google-shopping-merchant-conversions-v1.5.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-datasources: 1.6.0</summary>

## [1.6.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-datasources-v1.5.0...google-shopping-merchant-datasources-v1.6.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-inventories: 1.6.0</summary>

## [1.6.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-inventories-v1.5.0...google-shopping-merchant-inventories-v1.6.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-issueresolution: 1.5.0</summary>

## [1.5.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-issueresolution-v1.4.0...google-shopping-merchant-issueresolution-v1.5.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-lfp: 1.5.0</summary>

## [1.5.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-lfp-v1.4.0...google-shopping-merchant-lfp-v1.5.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-notifications: 1.5.0</summary>

## [1.5.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-notifications-v1.4.0...google-shopping-merchant-notifications-v1.5.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-ordertracking: 1.5.0</summary>

## [1.5.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-ordertracking-v1.4.0...google-shopping-merchant-ordertracking-v1.5.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-products: 1.8.0</summary>

## [1.8.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-products-v1.7.0...google-shopping-merchant-products-v1.8.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-productstudio: 0.5.1</summary>

## [0.5.1](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-productstudio-v0.5.0...google-shopping-merchant-productstudio-v0.5.1) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-promotions: 1.5.0</summary>

## [1.5.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-promotions-v1.4.0...google-shopping-merchant-promotions-v1.5.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-quota: 1.6.0</summary>

## [1.6.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-quota-v1.5.0...google-shopping-merchant-quota-v1.6.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-reports: 1.6.0</summary>

## [1.6.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-reports-v1.5.0...google-shopping-merchant-reports-v1.6.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-merchant-reviews: 0.6.1</summary>

## [0.6.1](https://github.com/codyoss/google-cloud-python/compare/google-shopping-merchant-reviews-v0.6.0...google-shopping-merchant-reviews-v0.6.1) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>google-shopping-type: 1.6.0</summary>

## [1.6.0](https://github.com/codyoss/google-cloud-python/compare/google-shopping-type-v1.5.0...google-shopping-type-v1.6.0) (2026-06-02)


### Features

* regenerate google-shopping packages ([#17072](https://github.com/codyoss/google-cloud-python/issues/17072)) ([2904f05](https://github.com/codyoss/google-cloud-python/commit/2904f059a0eb610180ccd7f3d169c130a1696333))
</details>

<details><summary>grafeas: 1.24.0</summary>

## [1.24.0](https://github.com/codyoss/google-cloud-python/compare/grafeas-v1.23.0...grafeas-v1.24.0) (2026-06-02)


### Features

* regenerate remaining packages ([#17078](https://github.com/codyoss/google-cloud-python/issues/17078)) ([cc4f36f](https://github.com/codyoss/google-cloud-python/commit/cc4f36f65e8b29d28f636e082435801b899cbca0))
</details>

<details><summary>sqlalchemy-spanner: 1.19.1</summary>

## [1.19.1](https://github.com/codyoss/google-cloud-python/compare/sqlalchemy-spanner-v1.19.0...sqlalchemy-spanner-v1.19.1) (2026-06-02)


### Bug Fixes

* **sqlalchemy-spanner:** Drop support for Python 3.8 and 3.9 ([#16913](https://github.com/codyoss/google-cloud-python/issues/16913)) ([f5b392e](https://github.com/codyoss/google-cloud-python/commit/f5b392e57d07295d66f0ad2974e1b2b8040d49c2))
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).