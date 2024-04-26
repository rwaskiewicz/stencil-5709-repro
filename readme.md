Repro for https://github.com/ionic-team/stencil/issues/5709

Steps to Repro:
1. Clone this repo, install deps (`npm i`)
2. Run `npm start`
3. Change `src/components/my-component/my-component.stories.ts` in some way to be still valid TS.
4. See the package recompile
