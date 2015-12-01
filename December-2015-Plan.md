**WORK IN PROGRESS**

- Issue # , contribute a PR node-onigurum 45.

## Dates
- `stable` channel update Dec 18th
- `insider` channel update Dec 14th

Most of the VS Code team is on vacation from Dec 20th until January 4th.

## Themes
- Establish our OSS development workflows (issue tracking, continuous integration)
- Listen to feedback, address critical issues
- Contribute to upstream components to address critical issues

## Items
- [Bugs](https://github.com/Microsoft/vscode/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Abug+milestone%3A%22Dec+2015%22+-label%3Aupstream+)

TODO: add bugs from other vscode components

**Development**
- [ ] Electron version 0.34.5 [#826](../issues/826)
- [ ] Run VSCode unit tests headless in a CI setup
- [ ] Proposal to separate vscode tools form the vscode API of the existing vscode module
- [ ] Automated Mac signing
- [ ] Increase test coverage
- [ ] Move old valuable bugs to github (Done: Ben, Joao, Andre, Isi)

**Upstream Contributions**
- [ ] Investigate into a PR for [Slow tokenization when using multibyte characters](https://github.com/atom/node-oniguruma/issues/45)
- [ ] Investigate into a PR [Keyboard aware key labels](https://github.com/atom/electron/issues/3631)

**Extensions**
- [ ] Expose more Commands as API
- [ ] Investigate deactivate() call for an extension
- [ ] Example of using TS 1.7 and async and await inside an extension
- [ ] Investigate into providing better support for VIM integration (intercept all keyevents for VIM command mode implementation)


**Gallery**
- [ ] Improve experience when user wants to read the README.md before installing an extension, provide option to install in an info box
- [ ] Support a command line switch to launch Code without any extensions #???

**Debug**

**Language service servers**
- [ ] Expose more language features in the language service protocol
- [ ] Document the language services protocol

**JS**
- [ ] Connect with TS team on Salsa (feature gaps?)
- [ ] Support to make ES6 the default without having to add a jsconfig.json (depends on Salsa) (#337)
- [ ] Enable ES6 coloring by using the TypeScript textmate grammar (align with Salsa)
- [ ] jsconfig.json sometime not taken into account #703
- [ ] Investigate into emmet support in JSX and TSX files

**C#**
- [ ] Adopt OmniSharp [#837](../issues/837)
- [ ] Move C# into a separate extension 

**TS**
- [ ] Adopt TypeScript 1.7 [#836](../issues/836)
- [ ] Explore an incremental build project extension (based on gulp-tsb)

**Git**
- [x] Support git integration when git folder is in a parent folder
- [ ] Create pull request (publish branch?)
- [ ] Add pull with rebase action

**UI**
- [ ] Explore: Intellisense improve support to show documentation for a  completion item
- [ ] Preserve zoom state 

**JSON**
- [ ] Support to contribute a JSON schema for a file pattern from an extension (Issue #)