# Continuous Integration for Android & iOS with GitHub Actions in Flutter

This repository demonstrates how to set up continuous integration (CI) for Android and iOS using GitHub Actions runners on a default new Flutter project.

## Overview
In this project, we use GitHub Actions to set up CI workflows that build and test a default new Flutter project for Android and iOS platforms.

**Flutter Project Setup**: The default new Flutter project is created using the `flutter create` command.

## Workflow Setup

The workflow setup includes the following steps:

1. **Testing**: After building, automated tests are run to ensure that the Flutter project functions correctly on both Android and iOS platforms.

2. **Android Build**: A workflow is triggered on every push or pull request to the repository. This workflow builds the Flutter project for the Android platform using linux vm.

3. **iOS Build**: Another workflow builds the Flutter project for the iOS platform using Xcode on M1 MacOs vm.

