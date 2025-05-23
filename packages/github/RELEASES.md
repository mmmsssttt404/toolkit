# @actions/github Releases

### 6.0.1

- Dependency updates [#2043](https://github.com/actions/toolkit/pull/2043/)

### 6.0.0 
- Support the latest Octokit in @actions/github [#1553](https://github.com/actions/toolkit/pull/1553)
  - Drop support of NodeJS v14, v16

### 5.1.1
- Export default octokit options [#1188](https://github.com/actions/toolkit/pull/1188)

### 5.1.0
- Add additionalPlugins parameter to getOctokit method [#1181](https://github.com/actions/toolkit/pull/1181)
- Dependency updates [#1180](https://github.com/actions/toolkit/pull/1180)


### 5.0.3
- - Update to v2.0.1 of `@actions/http-client` [#1087](https://github.com/actions/toolkit/pull/1087)

### 5.0.2
- Update to v2.0.0 of `@actions/http-client`

### 5.0.1
- [Update Octokit Dependencies](https://github.com/actions/toolkit/pull/1037)
### 5.0.0
- [Update @actions/github to include latest octokit definitions](https://github.com/actions/toolkit/pull/783)
- [Add urls to context](https://github.com/actions/toolkit/pull/794)

### 4.0.0
- [Add execution state information to context](https://github.com/actions/toolkit/pull/499)
- [Update Octokit Dependencies with some api breaking changes](https://github.com/actions/toolkit/pull/498) 
  - The full list of api changes are [here](https://github.com/octokit/plugin-rest-endpoint-methods.js/releases/tag/v4.0.0)
  - `GitHub.plugin()` no longer supports an array as first argument. Multiple args must be passed in instead.

### 3.0.0
- [Swap to @octokit/core and use plugins to leverage lastest octokit apis](https://github.com/actions/toolkit/pull/453)
- [Add comment field to payload context](https://github.com/actions/toolkit/pull/375) 

### 2.2.0

- [Support GHES: Use GITHUB_API_URL and GITHUB_GRAPHQL_URL to determine baseUrl](https://github.com/actions/toolkit/pull/449)

### 2.1.1

- [Use import {Octokit}](https://github.com/actions/toolkit/pull/332)
- [Check proxy bypass before setting proxy agent](https://github.com/actions/toolkit/pull/320)

### 2.1.0

- [Octokit client follows proxy settings](https://github.com/actions/toolkit/pull/314)
- [Fix issue number for pull request comment events](https://github.com/actions/toolkit/pull/311)

### 2.0.1

- [Add \"types\" to package.json](https://github.com/actions/toolkit/pull/221)

### 2.0.0

- Upgrade Octokit version to 4.x to include typescript types [#228](https://github.com/actions/toolkit/pull/228)

### 1.1.0

- Accept Octokit.Options in the GitHub constructor [#113](https://github.com/actions/toolkit/pull/113)

### 1.0.1

- Simplify WebPack configs by removing dynamic require - [#101](https://github.com/actions/toolkit/pull/101)

### 1.0.0

- Initial release
