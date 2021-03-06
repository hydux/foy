#### 0.1.16 (2019-01-31)

##### New Features

* **task:**  Async deps support priority ([782c5695](https://github.com/zaaack/foy/commit/782c5695359db4feec89040c9ddab88550d591dc))

##### Bug Fixes

* **task:**  Fix skipped in parallel ([9a574767](https://github.com/zaaack/foy/commit/9a5747672f8be35cfbff0f051f35ecf4db537e2e))

#### 0.1.15 (2019-01-30)

##### Bug Fixes

* **fs:**  Fix mkdirp parallel conflicts ([6de5e98c](https://github.com/zaaack/foy/commit/6de5e98c18508905f12f7ccaffbde317025a718c))

#### 0.1.14 (2019-01-30)

##### Bug Fixes

* **fs:**  Fix mkdirp parallel conflicts ([f54ef525](https://github.com/zaaack/foy/commit/f54ef5258b23c59fe55c3243526e513c3b8a00cd))

#### 0.1.13 (2019-01-30)

##### Documentation Changes

* **readme:**  Add Using in CI servers ([00e01792](https://github.com/zaaack/foy/commit/00e017925886bc8f7120223dfbf8be5bf0c55218))

##### New Features

* **util:**  Add namespace function ([c7acd50e](https://github.com/zaaack/foy/commit/c7acd50e24af944737e6d310b97c56473cf661ea))
* **exec:**  Add pushd/popd, ctx.cwd() => cwd.cwd ([a61273df](https://github.com/zaaack/foy/commit/a61273df5327131546a18d897ba5d24c9a63322c))

##### Bug Fixes

* **exec:**  Fix redirectStream is null ([dbfb65c4](https://github.com/zaaack/foy/commit/dbfb65c4d731cdd0bc92bcef795dfb9b122d9f81))
* **fs:**  fix rmrf directory ([46cfd8b4](https://github.com/zaaack/foy/commit/46cfd8b4303a0649742f2f565403ebcbe26664bc))

#### 0.1.12 (2019-01-21)

##### Bug Fixes

* **fs:**  copy should override existed files by default ([e510d0d9](https://github.com/zaaack/foy/commit/e510d0d9d0beb918969daa0b62050c698f17653e))

#### 0.1.11 (2019-01-15)

##### New Features

* **exec:**  Add redirectLog option to redirect external command executaion's log to file or stream ([4433d252](https://github.com/zaaack/foy/commit/4433d2525ec5582d362855ae8869e57d5c0b143a))
* **utils:**  Add namespacify ([9c752f02](https://github.com/zaaack/foy/commit/9c752f0295ad6e22748472ff4faf77223c3bd8b0))

##### Bug Fixes

* **cli:**  Fix loading ([debf8379](https://github.com/zaaack/foy/commit/debf8379090b163b10d041dcd2e5f3ee4f197a52))

#### 0.1.10 (2019-01-14)

##### Bug Fixes

* **cli:**
  *  Fix loading when resize terminal (fix: [#7](https://github.com/zaaack/foy/pull/7)) ([09a0d505](https://github.com/zaaack/foy/commit/09a0d505473f87b66c284d4ebb0b84b6bd4c3832))
  *  Output help when no argv ([1019fb35](https://github.com/zaaack/foy/commit/1019fb354b18b8590e8668f7182284e8db0259ad))
  *  Fix indent option ([0e9b8db5](https://github.com/zaaack/foy/commit/0e9b8db5afae446e30d50a55e7af883afa085d21))
  *  Less break line ([1855aa0d](https://github.com/zaaack/foy/commit/1855aa0dcf1e7d45bfbc3c33c0f09d2655523903))

#### 0.1.9 (2019-01-12)

##### New Features

* **cli:**
  *  Try load global installed foy if cannot find in local ([216510d2](https://github.com/zaaack/foy/commit/216510d278019d595f772f6b40c3e4b9c5aa6aff))
  *  Search Foyfiles in parent directories ([0bdfc802](https://github.com/zaaack/foy/commit/0bdfc8029931fd03db31f990708574ed5e0f40f4))
* **fs:**
  *  Naming, filter => skip ([cb01de60](https://github.com/zaaack/foy/commit/cb01de609fe04e8d4f51c944358904e68850dcd7))
  *  Add json options for fs.outputJson ([0c60df36](https://github.com/zaaack/foy/commit/0c60df36ea451c044756f91f9b2f763df7ccfc97))
* **exec & task:**  Add log command options ([2f7a782b](https://github.com/zaaack/foy/commit/2f7a782b5ddd2c5e64fbb114a318199855a38aac))

##### Bug Fixes

* **task:**
  *  Add dependency graph loading & dependency sugar ([f98c2d39](https://github.com/zaaack/foy/commit/f98c2d390c2dab9ad125ee1fb5370491b7cc3518))
  *  Make taskManager singleton ([f797af2a](https://github.com/zaaack/foy/commit/f797af2ab8037b6b66baaf600bf66856ead8c38a))
* **exec:**  Fix .env() only return env value when passing one parameter ([52af9510](https://github.com/zaaack/foy/commit/52af9510abb883cd6b457ea787439cc089f2a7a8))
* **util:**  Fix sleep ms ([6511cc11](https://github.com/zaaack/foy/commit/6511cc11bd8f436fd565873ba636e44586ecfdac))

##### Refactors

* **utils:**  Refactor defaults ([71841674](https://github.com/zaaack/foy/commit/718416742f3ac8e2286c250528d51ba6c786f5b5))

#### 0.1.8 (2019-01-10)

##### New Features

* **fs:**
  *  Naming, filter => skip ([cb01de60](https://github.com/zaaack/foy/commit/cb01de609fe04e8d4f51c944358904e68850dcd7))
  *  Add json options for fs.outputJson ([0c60df36](https://github.com/zaaack/foy/commit/0c60df36ea451c044756f91f9b2f763df7ccfc97))
* **exec & task:**  Add log command options ([2f7a782b](https://github.com/zaaack/foy/commit/2f7a782b5ddd2c5e64fbb114a318199855a38aac))
* **cli:**  Search Foyfiles in parent directories ([0bdfc802](https://github.com/zaaack/foy/commit/0bdfc8029931fd03db31f990708574ed5e0f40f4))

#### 0.1.7 (2019-01-09)

##### New Features

* **task:**  Add loading option for each task ([ac5a4222](https://github.com/zaaack/foy/commit/ac5a4222a1a22c14930a9b72761eb8aed9aea8cb))
* **cli:**  add --init ([d2b27fcb](https://github.com/zaaack/foy/commit/d2b27fcb9fb6ce5ac0a3d0e3930131f770ed60a9))

##### Bug Fixes

* **exec:**  Fix .env() only return env value when passing one parameter ([52af9510](https://github.com/zaaack/foy/commit/52af9510abb883cd6b457ea787439cc089f2a7a8))
* **util:**  Fix sleep ms ([6511cc11](https://github.com/zaaack/foy/commit/6511cc11bd8f436fd565873ba636e44586ecfdac))

#### 0.1.6 (2018-12-29)

##### Chores

* **build:**  Update Foyfile ([d52ea2f7](https://github.com/zaaack/foy/commit/d52ea2f760597ee5bc50a7f555f0f58cfdbe03ed))

##### New Features

* **task:**  Add loading option for each task ([ac5a4222](https://github.com/zaaack/foy/commit/ac5a4222a1a22c14930a9b72761eb8aed9aea8cb))
* **cli:**  add --init ([d2b27fcb](https://github.com/zaaack/foy/commit/d2b27fcb9fb6ce5ac0a3d0e3930131f770ed60a9))
