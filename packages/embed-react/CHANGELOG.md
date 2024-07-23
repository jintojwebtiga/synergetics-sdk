# [@synergetics/embed-react-v4.0.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.20.0...@synergetics/embed-react-v4.0.0) (2024-07-17)


### Bug Fixes

* **TU-15133:** Rename `ref` prop to `embedRef` for proper typing ([#657](https://github.com/synergetics/embed/issues/657)) ([7860e94](https://github.com/synergetics/embed/commit/7860e943a99ab35f7a59d537862c547a305766ac))


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([b2ada39](https://github.com/synergetics/embed/commit/b2ada392e534ee4b6cb9a64f7ff678ef6a12f6b4))


### BREAKING CHANGES

* **TU-15133:** Components are unable to access `ref` prop directly.
Using  `forwardRef` breaks the typings. Since we do not accept any
`ForwardedRef` but rather only `MutableRefObject`, we will rename the
prop to type it correctly.

* chore(TU-15133): Update NextJS demos to run on latest version

Add examples for the App Router available from NextJS version >= 13.

* feat(TU-15133): Update CI to run on Node version 22
* **TU-15133:** The library no longer supports node version 16 (end of
life 2023-09-11). React version is bumped and requires node >= 18.

# [@synergetics/embed-react-v3.20.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.19.0...@synergetics/embed-react-v3.20.0) (2024-07-17)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([0f29638](https://github.com/synergetics/embed/commit/0f296383c33c4e5ccda4c2979bc28d78300c9e0b))

# [@synergetics/embed-react-v3.19.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.18.0...@synergetics/embed-react-v3.19.0) (2024-07-10)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([bd0698c](https://github.com/synergetics/embed/commit/bd0698c1a53c0dc5345549b6e3008eabdeda23ee))

# [@synergetics/embed-react-v3.18.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.17.0...@synergetics/embed-react-v3.18.0) (2024-07-08)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([41b0104](https://github.com/synergetics/embed/commit/41b0104304df4cc7c3cc9ee55f77345fcd6e8b85))

# [@synergetics/embed-react-v3.17.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.16.0...@synergetics/embed-react-v3.17.0) (2024-04-16)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([29b1dc5](https://github.com/synergetics/embed/commit/29b1dc5bf5409b72a5b0a073542cf62ace29af9a))
* **TU-9582:** Export correct prop types for react components ([#646](https://github.com/synergetics/embed/issues/646)) ([02030ab](https://github.com/synergetics/embed/commit/02030abadfc74a324826fb66372a8fe61b6dfe6f)), closes [#643](https://github.com/synergetics/embed/issues/643)

# [@synergetics/embed-react-v3.16.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.15.0...@synergetics/embed-react-v3.16.0) (2024-03-18)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([e9e1ba6](https://github.com/synergetics/embed/commit/e9e1ba6592583625063eb31cebfa6372b677748b))

# [@synergetics/embed-react-v3.15.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.14.0...@synergetics/embed-react-v3.15.0) (2024-02-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([d552fd2](https://github.com/synergetics/embed/commit/d552fd20912a5fb2cb43007deddd4eb006054903))

# [@synergetics/embed-react-v3.14.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.13.0...@synergetics/embed-react-v3.14.0) (2024-02-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([87810ed](https://github.com/synergetics/embed/commit/87810eddfbcc42c66a3a02191782e97eb07d4706))

# [@synergetics/embed-react-v3.13.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.12.0...@synergetics/embed-react-v3.13.0) (2024-02-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([50bb52e](https://github.com/synergetics/embed/commit/50bb52e94c149e116e4df912dcb6e9141a507f3b))

# [@synergetics/embed-react-v3.12.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.11.0...@synergetics/embed-react-v3.12.0) (2024-02-22)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([22cb027](https://github.com/synergetics/embed/commit/22cb027701b6a88fbeb9f22d62a99b040746f493))

# [@synergetics/embed-react-v3.11.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.10.0...@synergetics/embed-react-v3.11.0) (2024-01-30)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([6bb5127](https://github.com/synergetics/embed/commit/6bb5127ac7b63059ea716f513d8801647e95fdcd))

# [@synergetics/embed-react-v3.10.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.9.0...@synergetics/embed-react-v3.10.0) (2024-01-03)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([9a03e96](https://github.com/synergetics/embed/commit/9a03e965f86e02016f23d4b8f147ed82211245da))

# [@synergetics/embed-react-v3.9.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.8.0...@synergetics/embed-react-v3.9.0) (2023-11-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([72e3a2f](https://github.com/synergetics/embed/commit/72e3a2fce54ef08fb1bd7776631c30e5bed80fd8))

# [@synergetics/embed-react-v3.8.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.7.0...@synergetics/embed-react-v3.8.0) (2023-10-31)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([467867a](https://github.com/synergetics/embed/commit/467867ac63abd5ace252d938918799c34a1f0b6e))

# [@synergetics/embed-react-v3.7.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.6.0...@synergetics/embed-react-v3.7.0) (2023-10-30)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([b40658e](https://github.com/synergetics/embed/commit/b40658e93034875c9e30d7b2d9c0e2a896bb093c))

# [@synergetics/embed-react-v3.6.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.5.0...@synergetics/embed-react-v3.6.0) (2023-10-24)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([6cd4c28](https://github.com/synergetics/embed/commit/6cd4c2827496df8cb766e56835b5e34d7966da77))

# [@synergetics/embed-react-v3.5.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.4.0...@synergetics/embed-react-v3.5.0) (2023-10-24)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([751ed7c](https://github.com/synergetics/embed/commit/751ed7cff98550f63904eb2a35bc641a988599c4))

# [@synergetics/embed-react-v3.4.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.3.0...@synergetics/embed-react-v3.4.0) (2023-10-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([4d899d4](https://github.com/synergetics/embed/commit/4d899d40009d899cd3baab55cc04891919f40744))

# [@synergetics/embed-react-v3.3.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.2.0...@synergetics/embed-react-v3.3.0) (2023-10-20)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([7bf83a7](https://github.com/synergetics/embed/commit/7bf83a775f2e28b6d2edb49f3e4014f06f82f065))

# [@synergetics/embed-react-v3.2.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.1.0...@synergetics/embed-react-v3.2.0) (2023-10-03)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([eaf04f5](https://github.com/synergetics/embed/commit/eaf04f52d6f621cdfad5aa2ac42ba3559f8b9455))

# [@synergetics/embed-react-v3.1.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.0.0...@synergetics/embed-react-v3.1.0) (2023-10-02)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c724799](https://github.com/synergetics/embed/commit/c724799fd51cb1eaf3fdc4b691024d90850c6376))

# [@synergetics/embed-react-v3.1.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v3.0.0...@synergetics/embed-react-v3.1.0) (2023-10-02)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c724799](https://github.com/synergetics/embed/commit/c724799fd51cb1eaf3fdc4b691024d90850c6376))

# [@synergetics/embed-react-v3.0.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.31.0...@synergetics/embed-react-v3.0.0) (2023-09-14)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([cbbf53a](https://github.com/synergetics/embed/commit/cbbf53ac780a5caa6fb263ea38de3c3b049ee69d))
* **RESP-1781:** Remove support for CUI ([#613](https://github.com/synergetics/embed/issues/613)) ([00f3a89](https://github.com/synergetics/embed/commit/00f3a892972cd5d2e77411236724a63b4ac804c9))


### BREAKING CHANGES

* **RESP-1781:** CUI is not supported anymore

* chore(RESP-1781): Update tsconfig to match standards

* chore(RESP-1781): Update synergetics eslint config to latest

# [@synergetics/embed-react-v2.31.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.30.0...@synergetics/embed-react-v2.31.0) (2023-08-31)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([9848597](https://github.com/synergetics/embed/commit/98485974165bd00ca2be7270da510b9a154d6d05))

# [@synergetics/embed-react-v2.30.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.29.0...@synergetics/embed-react-v2.30.0) (2023-07-26)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([79d5fea](https://github.com/synergetics/embed/commit/79d5fea380f10b0361d296032ffc5ee759f7675c))

# [@synergetics/embed-react-v2.29.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.28.0...@synergetics/embed-react-v2.29.0) (2023-07-21)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([54a0259](https://github.com/synergetics/embed/commit/54a02598acaaba7e9a2c15540b452c8abdc6a93a))

# [@synergetics/embed-react-v2.28.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.27.0...@synergetics/embed-react-v2.28.0) (2023-07-20)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([ac38a90](https://github.com/synergetics/embed/commit/ac38a90dc671660368a6d29a9be856fcc898eb53))

# [@synergetics/embed-react-v2.27.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.26.0...@synergetics/embed-react-v2.27.0) (2023-07-12)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([74f81a0](https://github.com/synergetics/embed/commit/74f81a0d98feaa3b0dd7120686b9db4055aa5576))

# [@synergetics/embed-react-v2.26.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.25.0...@synergetics/embed-react-v2.26.0) (2023-07-10)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([9989623](https://github.com/synergetics/embed/commit/998962385362d50fd3393ff8576cbd1685866b8f))

# [@synergetics/embed-react-v2.25.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.24.0...@synergetics/embed-react-v2.25.0) (2023-07-10)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([706b891](https://github.com/synergetics/embed/commit/706b891054aa26350299741ce0997082d5d114a5))

# [@synergetics/embed-react-v2.24.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.23.0...@synergetics/embed-react-v2.24.0) (2023-06-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([9a4a19c](https://github.com/synergetics/embed/commit/9a4a19c8109b634f1173cd600f49e6d91258b808))
* **REACH-458:** Bump [@synergetics](https://github.com/synergetics) dependencies ([#591](https://github.com/synergetics/embed/issues/591)) ([000a8a3](https://github.com/synergetics/embed/commit/000a8a3b04e02bd2db5eab8e25040a74f93b84b1))

# [@synergetics/embed-react-v2.23.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.22.0...@synergetics/embed-react-v2.23.0) (2023-06-22)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([4d770af](https://github.com/synergetics/embed/commit/4d770af64a631935603e7dd68a557fa93370a226))

# [@synergetics/embed-react-v2.22.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.21.0...@synergetics/embed-react-v2.22.0) (2023-06-07)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c32b6db](https://github.com/synergetics/embed/commit/c32b6dba0f950627097cd2e0e42479a208a41f4a))

# [@synergetics/embed-react-v2.21.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.20.0...@synergetics/embed-react-v2.21.0) (2023-05-05)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([d91b170](https://github.com/synergetics/embed/commit/d91b170d3b36acf58e433fff91e37c62da20317f))

# [@synergetics/embed-react-v2.20.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.19.0...@synergetics/embed-react-v2.20.0) (2023-04-11)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([4a555ae](https://github.com/synergetics/embed/commit/4a555ae56394ccb51b2415dfe2a50e36f85eb9e0))

# [@synergetics/embed-react-v2.19.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.18.0...@synergetics/embed-react-v2.19.0) (2023-03-15)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c6f5d29](https://github.com/synergetics/embed/commit/c6f5d2995044383a5d5ab260291e5e16eee1aeba))

# [@synergetics/embed-react-v2.18.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.17.0...@synergetics/embed-react-v2.18.0) (2023-03-07)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([741d950](https://github.com/synergetics/embed/commit/741d950002cb682f0c1a82de782419b1709700ad))

# [@synergetics/embed-react-v2.17.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.16.0...@synergetics/embed-react-v2.17.0) (2023-03-03)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c4b84e9](https://github.com/synergetics/embed/commit/c4b84e93c6b7a8bdca32079aced6e0bfa0d7f69e))

# [@synergetics/embed-react-v2.16.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.15.0...@synergetics/embed-react-v2.16.0) (2023-02-27)


### Features

* **DIST-2006:** Custom ref for popover and sidetab ([#562](https://github.com/synergetics/embed/issues/562)) ([abb0232](https://github.com/synergetics/embed/commit/abb02329e56e7a8f071113de78ebc2ce6ec1e5db))

# [@synergetics/embed-react-v2.15.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.14.1...@synergetics/embed-react-v2.15.0) (2023-01-30)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([bc24fba](https://github.com/synergetics/embed/commit/bc24fba55b98aa47988c7a1965e78d9c9ec9a93e))

# [@synergetics/embed-react-v2.14.1](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.14.0...@synergetics/embed-react-v2.14.1) (2023-01-25)


### Bug Fixes

* **DIST-2005:** Use React.forwardRef to pass ref ([#560](https://github.com/synergetics/embed/issues/560)) ([302ea2d](https://github.com/synergetics/embed/commit/302ea2d7cfe6d3bc0905d5e4db44e4d37f2d2280))

# [@synergetics/embed-react-v2.14.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.13.0...@synergetics/embed-react-v2.14.0) (2023-01-25)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([a9af68f](https://github.com/synergetics/embed/commit/a9af68f85166cf5582270edc4e73bb2c58576a58))

# [@synergetics/embed-react-v2.13.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.12.0...@synergetics/embed-react-v2.13.0) (2023-01-23)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([af00f71](https://github.com/synergetics/embed/commit/af00f71780b237aab099392c7574991bd0a646e1))

# [@synergetics/embed-react-v2.12.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.11.0...@synergetics/embed-react-v2.12.0) (2023-01-18)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([2f16631](https://github.com/synergetics/embed/commit/2f1663180c3841bc8c51d64f7e9f0e9f8a5d2a51))

# [@synergetics/embed-react-v2.11.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.10.0...@synergetics/embed-react-v2.11.0) (2023-01-11)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([bf6cdb6](https://github.com/synergetics/embed/commit/bf6cdb6cf164db51002675cb2af1b1ab54065680))

# [@synergetics/embed-react-v2.10.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.9.0...@synergetics/embed-react-v2.10.0) (2022-12-21)


### Features

* **DIST-2005:** @synergetics/embed-react add the ability to pass custom ref to PopupButton ([#546](https://github.com/synergetics/embed/issues/546)) ([389d196](https://github.com/synergetics/embed/commit/389d196075c679e9f31b1c046ae9fa4ff1abdde5))

# [@synergetics/embed-react-v2.9.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.8.0...@synergetics/embed-react-v2.9.0) (2022-12-20)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c20a93b](https://github.com/synergetics/embed/commit/c20a93b538ae79989aa92cebdab2d7b8e7f47656))

# [@synergetics/embed-react-v2.8.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.7.0...@synergetics/embed-react-v2.8.0) (2022-12-19)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([24079b4](https://github.com/synergetics/embed/commit/24079b4cb06b085a4df940a9bfbac54008944a19))

# [@synergetics/embed-react-v2.7.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.6.0...@synergetics/embed-react-v2.7.0) (2022-12-06)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([0651e89](https://github.com/synergetics/embed/commit/0651e89ae91ff06789f22d8effa3e90ebb749878))

# [@synergetics/embed-react-v2.6.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.5.0...@synergetics/embed-react-v2.6.0) (2022-12-02)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([b889233](https://github.com/synergetics/embed/commit/b88923313327362cfc298d8c0155ce70bc61f099))

# [@synergetics/embed-react-v2.5.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.4.0...@synergetics/embed-react-v2.5.0) (2022-11-28)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([f855d8a](https://github.com/synergetics/embed/commit/f855d8a3531b08f389121644bd07f522fa9cdabd))

# [@synergetics/embed-react-v2.4.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.3.0...@synergetics/embed-react-v2.4.0) (2022-11-17)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([bd1eaf7](https://github.com/synergetics/embed/commit/bd1eaf7ae3e746cea7fd0075f31f384244d4492d))
* **DIST-1752:** Updated demos on readme ([#534](https://github.com/synergetics/embed/issues/534)) ([385eef2](https://github.com/synergetics/embed/commit/385eef2b472d3036649973f0c7430e435eeb9fb7))

# [@synergetics/embed-react-v2.3.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.2.0...@synergetics/embed-react-v2.3.0) (2022-11-14)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([79c0ade](https://github.com/synergetics/embed/commit/79c0adecf7c88173d7c560897675e38e28177d0d))

# [@synergetics/embed-react-v2.2.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.1.0...@synergetics/embed-react-v2.2.0) (2022-11-10)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([cf7acd6](https://github.com/synergetics/embed/commit/cf7acd647873c162bb844e9ee8daf604f3eab4c0))

# [@synergetics/embed-react-v2.1.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v2.0.0...@synergetics/embed-react-v2.1.0) (2022-10-10)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([9c57ca6](https://github.com/synergetics/embed/commit/9c57ca60eccf663ea1ccd574464f5ccc927a8de1))

# [@synergetics/embed-react-v2.0.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.21.0...@synergetics/embed-react-v2.0.0) (2022-10-04)


### Bug Fixes

* **DIST-1614:** Add support for node 18, break node 12 support ([7b1e540](https://github.com/synergetics/embed/commit/7b1e540477d275852b37cf0cba3591a5d8061bd6))


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([1023299](https://github.com/synergetics/embed/commit/1023299a6dc7dde31ef17cf3cc2e8dfbd02746d3))


### BREAKING CHANGES

* **DIST-1614:** Node 12 is no longer supported by OpenJS Foundation.
We will no longer support it in embed libs as well. Node 18 moves to Active LTS on 2022-10-25.
https://github.com/nodejs/release#release-schedule

# [@synergetics/embed-react-v1.21.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.20.0...@synergetics/embed-react-v1.21.0) (2022-09-16)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([592ca45](https://github.com/synergetics/embed/commit/592ca4571e2c3c87f7167b935a4954592450b62f))

# [@synergetics/embed-react-v1.20.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.19.0...@synergetics/embed-react-v1.20.0) (2022-09-12)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([95ab41d](https://github.com/synergetics/embed/commit/95ab41d9fd4b658a334828114625624bffaaf78c))

# [@synergetics/embed-react-v1.19.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.18.0...@synergetics/embed-react-v1.19.0) (2022-08-04)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([18c9ce0](https://github.com/synergetics/embed/commit/18c9ce02a04a8e954ff0717f38421bf7feb79486))

# [@synergetics/embed-react-v1.18.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.17.0...@synergetics/embed-react-v1.18.0) (2022-07-19)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([7704180](https://github.com/synergetics/embed/commit/7704180120b1f23c1ed53d67d27a189ed089c4c5))

# [@synergetics/embed-react-v1.17.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.16.0...@synergetics/embed-react-v1.17.0) (2022-06-08)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([0ef1036](https://github.com/synergetics/embed/commit/0ef103689ba19d121cb2a55d0010ab2471a7c6c4))

# [@synergetics/embed-react-v1.16.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.15.0...@synergetics/embed-react-v1.16.0) (2022-04-21)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([da0285b](https://github.com/synergetics/embed/commit/da0285bb89038b8bf167d5ff17ac630fc2b6d1b6))

# [@synergetics/embed-react-v1.15.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.14.0...@synergetics/embed-react-v1.15.0) (2022-04-13)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([ce4481c](https://github.com/synergetics/embed/commit/ce4481c40a4f77e20f56160343b27dc718415710))

# [@synergetics/embed-react-v1.14.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.13.0...@synergetics/embed-react-v1.14.0) (2022-04-06)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([e972568](https://github.com/synergetics/embed/commit/e972568903062c2c76cd719be60ac509a2610aa6))

# [@synergetics/embed-react-v1.13.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.12.0...@synergetics/embed-react-v1.13.0) (2022-03-15)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([d21c2c4](https://github.com/synergetics/embed/commit/d21c2c40961ca53a5ba46d9fbb8cc87552a9f546))

# [@synergetics/embed-react-v1.12.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.11.0...@synergetics/embed-react-v1.12.0) (2022-03-11)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([734d450](https://github.com/synergetics/embed/commit/734d450b015041ab89b366ca2abe83a8f72777d7))
* **DIST-965:** button test id ([ce00878](https://github.com/synergetics/embed/commit/ce00878c2c5d442d8ebed0e5c1bef565d87153e4))

# [@synergetics/embed-react-v1.11.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.10.0...@synergetics/embed-react-v1.11.0) (2022-03-11)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([c757e8c](https://github.com/synergetics/embed/commit/c757e8c8996f2a3568bcc9a444dd342921b9ac51))

# [@synergetics/embed-react-v1.10.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.9.0...@synergetics/embed-react-v1.10.0) (2022-03-09)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([3b126bb](https://github.com/synergetics/embed/commit/3b126bbeb0e1e9652dd0a6b9bf4195828a2c0ba7))

# [@synergetics/embed-react-v1.9.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.8.0...@synergetics/embed-react-v1.9.0) (2022-02-24)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([9d6568e](https://github.com/synergetics/embed/commit/9d6568ea2bc6dff79d2c23926eb70289beb59a62))

# [@synergetics/embed-react-v1.8.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.7.0...@synergetics/embed-react-v1.8.0) (2022-02-24)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([a7c26c3](https://github.com/synergetics/embed/commit/a7c26c3653c2bbd532c53fb9411d8fd6aab478ae))

# [@synergetics/embed-react-v1.7.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.6.1...@synergetics/embed-react-v1.7.0) (2022-02-21)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([4a4d251](https://github.com/synergetics/embed/commit/4a4d2514b3f4e0713916d4a34ca9ed5bdca47234))

# [@synergetics/embed-react-v1.6.1](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.6.0...@synergetics/embed-react-v1.6.1) (2022-02-18)


### Bug Fixes

* **DIST-1525:** read the nonce from a bundler-safe location ([02b898c](https://github.com/synergetics/embed/commit/02b898c4ac0d0f3d7b514962e65b2a65210f3500))

# [@synergetics/embed-react-v1.6.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.5.0...@synergetics/embed-react-v1.6.0) (2022-02-17)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([2eccba2](https://github.com/synergetics/embed/commit/2eccba2b55f2ef3e76116ccab521bede3e9ded91))

# [@synergetics/embed-react-v1.5.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.4.0...@synergetics/embed-react-v1.5.0) (2022-02-16)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([a863183](https://github.com/synergetics/embed/commit/a8631831a825d6da5930694f52e403691a1bcaaf))

# [@synergetics/embed-react-v1.4.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.3.0...@synergetics/embed-react-v1.4.0) (2022-02-16)


### Features

* Bump @synergetics/embed in @synergetics/embed-react package ([be5fb83](https://github.com/synergetics/embed/commit/be5fb8374873e7961b7af98f23c33dd23dee9fa3))
* Bump @synergetics/embed in @synergetics/embed-react package [skip ci] ([792edc2](https://github.com/synergetics/embed/commit/792edc28010b611f6b6ed4b6c22e8722b773f62d))

# [@synergetics/embed-react-v1.3.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.6...@synergetics/embed-react-v1.3.0) (2022-02-15)


### Features

* attach __webpack_nonce__ to inline <style> if set ([b63f37b](https://github.com/synergetics/embed/commit/b63f37b83f2cf7ea308777e5f5fab74520a2d866))

# [@synergetics/embed-react-v1.2.6](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.5...@synergetics/embed-react-v1.2.6) (2022-02-07)


### Bug Fixes

* **DIST-1443:** Custom release script ([cbb3cbe](https://github.com/synergetics/embed/commit/cbb3cbe0d36f9e2156420e093325e0e4037c6aef))

# [@synergetics/embed-react-v1.2.5](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.4...@synergetics/embed-react-v1.2.5) (2022-02-07)


### Bug Fixes

* **DIST-1443:** Custom release script ([8eea136](https://github.com/synergetics/embed/commit/8eea136d1e34ec0b97f454c651ae721bf4eede1e))

# [@synergetics/embed-react-v1.2.4](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.3...@synergetics/embed-react-v1.2.4) (2021-12-13)


### Bug Fixes

* **TYP-6098:** Update embed dependency ([ec091ad](https://github.com/synergetics/embed/commit/ec091ad32e6f3656c32c5e5d2a379ef012b0afc2))

# [@synergetics/embed-react-v1.2.3](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.2...@synergetics/embed-react-v1.2.3) (2021-12-10)


### Bug Fixes

* **DIST-1150:** Update embed dependency ([1b4dccc](https://github.com/synergetics/embed/commit/1b4dccca8d3db2faf040ce3fe7a7a2441410f240))

# [@synergetics/embed-react-v1.2.2](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.1...@synergetics/embed-react-v1.2.2) (2021-12-08)


### Bug Fixes

* Update license metadata ([#430](https://github.com/synergetics/embed/issues/430)) ([c5ebbfa](https://github.com/synergetics/embed/commit/c5ebbfad26a55efdb6911c0f9269529fd008dbb1))

# [@synergetics/embed-react-v1.2.1](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.2.0...@synergetics/embed-react-v1.2.1) (2021-11-29)


### Bug Fixes

* **TYP-6029:** Update embed dependency ([138dde5](https://github.com/synergetics/embed/commit/138dde5ef1d473b8567c114af37907801460a3be))

# [@synergetics/embed-react-v1.2.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.1.5...@synergetics/embed-react-v1.2.0) (2021-11-29)


### Features

* **TYP-6029:** Change CSS classnames prefixes ([#423](https://github.com/synergetics/embed/issues/423)) ([ee652e4](https://github.com/synergetics/embed/commit/ee652e474d72586be72f72e7fc9ea316fd146fc7))

# [@synergetics/embed-react-v1.1.5](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.1.4...@synergetics/embed-react-v1.1.5) (2021-11-25)


### Bug Fixes

* **DIST-1425:** Update embed dependencies ([97d4876](https://github.com/synergetics/embed/commit/97d4876ea58dc3fefc3399e027b36c077da19809))

# [@synergetics/embed-react-v1.1.4](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.1.3...@synergetics/embed-react-v1.1.4) (2021-11-25)


### Bug Fixes

* Update embed dependency ([7384691](https://github.com/synergetics/embed/commit/7384691aa8e5efeb0ee02ce0f4b01df3b150ac1f))

# [@synergetics/embed-react-v1.1.3](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.1.2...@synergetics/embed-react-v1.1.3) (2021-10-19)


### Bug Fixes

* **DIST-1337:** Use React.memo to prevent unwanted re-renders ([#408](https://github.com/synergetics/embed/issues/408)) ([f6c37d2](https://github.com/synergetics/embed/commit/f6c37d25a1f774b01b3870263bfca1167b271004))

# [@synergetics/embed-react-v1.1.2](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.1.1...@synergetics/embed-react-v1.1.2) (2021-09-20)


### Bug Fixes

* **DIST-1269:** Pass props to button component ([#383](https://github.com/synergetics/embed/issues/383)) ([9d87f78](https://github.com/synergetics/embed/commit/9d87f78180b5c4e282ea97d98667879b1dcab991))

# [@synergetics/embed-react-v1.1.1](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.1.0...@synergetics/embed-react-v1.1.1) (2021-09-01)


### Bug Fixes

* **DIST-1237:** Add information about the repository ([#377](https://github.com/synergetics/embed/issues/377)) ([a02cbbb](https://github.com/synergetics/embed/commit/a02cbbb8d85c89a8caba9bd3868f5e66e9dfcdc1))

# [@synergetics/embed-react-v1.1.0](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.7...@synergetics/embed-react-v1.1.0) (2021-08-31)


### Features

* **DIST-1234:** Customizable html for PopupButton ([#373](https://github.com/synergetics/embed/issues/373)) ([7057fd5](https://github.com/synergetics/embed/commit/7057fd5248ec922e97cd793a534e77a04cbbf836))

# [@synergetics/embed-react-v1.0.7](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.6...@synergetics/embed-react-v1.0.7) (2021-07-05)


### Bug Fixes

* **DIST-1066:** Github deploy ([#283](https://github.com/synergetics/embed/issues/283)) ([1f1c223](https://github.com/synergetics/embed/commit/1f1c2239b33da7e318578578dbaef40639a5f29c))

# [@synergetics/embed-react-v1.0.6](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.5...@synergetics/embed-react-v1.0.6) (2021-07-02)


### Bug Fixes

* **DIST-1066:** Update contributing part of README ([5b2b03e](https://github.com/synergetics/embed/commit/5b2b03ee7fa90f8412f9884d039c470f7c4d9bff))

# [@synergetics/embed-react-v1.0.5](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.4...@synergetics/embed-react-v1.0.5) (2021-06-16)

### Bug Fixes

- **DIST-779:** Update dependencies ([#266](https://github.com/synergetics/embed/issues/266)) ([247c019](https://github.com/synergetics/embed/commit/247c0192e87fbe42fd97df64639a789bc17f2a8d))

# [@synergetics/embed-react-v1.0.4](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.3...@synergetics/embed-react-v1.0.4) (2021-06-16)

### Bug Fixes

- **DIST-779:** Update embed-react post-release script ([8dd9c12](https://github.com/synergetics/embed/commit/8dd9c124a19b5049a72fd931f21bebd8fbea84b2))

# [@synergetics/embed-react-v1.0.3](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.2...@synergetics/embed-react-v1.0.3) (2021-06-16)

### Bug Fixes

- **DIST-779:** Do not release embed-react to github ([d45f5ca](https://github.com/synergetics/embed/commit/d45f5ca9b1be78a7b9c2c1cc839fa983526878d9))

# [@synergetics/embed-react-v1.0.2](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.1...@synergetics/embed-react-v1.0.2) (2021-06-16)

### Bug Fixes

- **DIST-779:** Release embed-react also to github ([68fa6a1](https://github.com/synergetics/embed/commit/68fa6a1c335637d52806b78fd8ecd11ade9f6266))

# [@synergetics/embed-react-v1.0.1](https://github.com/synergetics/embed/compare/@synergetics/embed-react-v1.0.0...@synergetics/embed-react-v1.0.1) (2021-06-16)

### Bug Fixes

- **DIST-779:** Update embed-react release script ([f879a4b](https://github.com/synergetics/embed/commit/f879a4b41971a0a882efff6483bfe8119511258e))

# @synergetics/embed-react-v1.0.0 (2021-06-16)

### Features

- **DIST-779:** React lib ([#242](https://github.com/synergetics/embed/issues/242)) ([976eaa9](https://github.com/synergetics/embed/commit/976eaa9d693dac9e6c2b1171d89024b49a62f78f))