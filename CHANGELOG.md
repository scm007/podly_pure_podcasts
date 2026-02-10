# [2.3.0](https://github.com/scm007/podly_pure_podcasts/compare/v2.2.2...v2.3.0) (2026-02-10)


### Bug Fixes

* ci.sh automated fix ([a30373b](https://github.com/scm007/podly_pure_podcasts/commit/a30373b58bc0a884cd918bf829c660b3be9df904))
* feed urls were not being properly generated with reverse proxy settings ([78bcd36](https://github.com/scm007/podly_pure_podcasts/commit/78bcd36d87c0001047b9d9c3cab91bc2ac46a2a9))
* reformat completed by ci.sh ([0575141](https://github.com/scm007/podly_pure_podcasts/commit/0575141be98c69d7ac07816d25319cbb254021c2))
* remove unnecessary type ignore for flask import ([b7e20d6](https://github.com/scm007/podly_pure_podcasts/commit/b7e20d6148ed4c88b1e2c96d4526e9e38fcf394d))
* update container name and network name to podly-pure-podcasts across all compose files ([06c3953](https://github.com/scm007/podly_pure_podcasts/commit/06c39536654a4e088171df46a65d4761f6c33d8a))


### Features

* add support for local LLMs ([786aaef](https://github.com/scm007/podly_pure_podcasts/commit/786aaeffa5540c5113755ecdb012e2fd2e94fceb))
* **processing:** add JobManager; refactor processor/API/UI; remove legacy jobs ([b91210e](https://github.com/scm007/podly_pure_podcasts/commit/b91210ea9155f3306505c7ac1cc3f5920df5e295))


### Reverts

* Revert "debug build to test headers" ([e33852e](https://github.com/scm007/podly_pure_podcasts/commit/e33852efe2cbd2b8aa11a7eb91d5313ed37251d7))
* Revert "Fix Docker build failures in GitHub Actions" ([c97ab89](https://github.com/scm007/podly_pure_podcasts/commit/c97ab89c3abdbc03ce74898c0899154b8d1bb75b))
* Revert "fix: ci.sh automated fix" ([6774669](https://github.com/scm007/podly_pure_podcasts/commit/6774669790828dda396fe8418264a49b3d8e2b7a))
* Revert "fix: remove unnecessary type ignore for flask import" ([6e67f02](https://github.com/scm007/podly_pure_podcasts/commit/6e67f0277093a495d767b6fb3632b09b96fa80ad))
* Revert "refactor: remove debug_headers.py and enhance logging in _get_base_url for better reverse proxy support" ([b4fcc39](https://github.com/scm007/podly_pure_podcasts/commit/b4fcc39d970e4a930c0b747e8b616467620a7c62))
* Revert "refactor: reorganize catch_all route for improved static file handling" ([6273aeb](https://github.com/scm007/podly_pure_podcasts/commit/6273aebb1522c4a48c335a59232dab4fd035ecc5))
* Revert "refactor: simplify reverse proxy handling to use relative paths instead of config settings" ([dcb955d](https://github.com/scm007/podly_pure_podcasts/commit/dcb955d3d90b8386c6859c24b17ecdd089649b9b))
* Revert "refactor: update server and port configuration for improved reverse proxy handling and backwards compatibility" ([51c3bfd](https://github.com/scm007/podly_pure_podcasts/commit/51c3bfd94168782ccffdb98c653f034289d11be7))
* test_process_audio.py ([f1a9e0d](https://github.com/scm007/podly_pure_podcasts/commit/f1a9e0d87430864e1df99f1beb8d035e77069762))
