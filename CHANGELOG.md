## 0.3.4

- Merge pull request #7 from tripledoublev/feat/build-pipeline

Update build script to include TypeScript compilation in the build pr…

## 0.3.3

- Merge pull request #6 from tripledoublev/feat/build-pipeline

Fix import path for @electron/notarize in notarize.ts

## 0.3.2

- Merge pull request #5 from tripledoublev/feat/build-pipeline

Update dependencies and migrate to @electron/notarize

## 0.3.1

- regen lockfile (#95)

Co-authored-by: Vinay Raghu <vinay.raghu@whoop.com>

## 0.3.0

- Merge branch 'main' into feat/tagging

## 0.2.0

- fix todos

## Changes prior to changelog introduction

- Change build system & folder structure to build entire app & html together (not have a separate web server)
- Add model layer, for efficient in-memory storage, and separate from persistence services
- Make Kernel truly modular & without dependence on the main app code
