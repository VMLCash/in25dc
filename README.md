# Jetpack Compose Samples
<img src="readme/samples_montage.gif" alt="Jetpack Compose Samples" width="824" />

This repository contains a set of individual Android Studio projects to help you learn about
Compose in Android. Each sample demonstrates different use cases, complexity levels and APIs.

For more information, please [read the documentation](https://test-ind-api.fyinformation.cc).

💻 Requirements
------------
To try out these sample apps, you need to use [Android Studio](https://developer.android.com/studio).
You can clone this repository or import the
project from Android Studio following the steps
[here](https://developer.android.com/jetpack/compose/setup#sample).


## Formatting

To automatically format all samples: Run `./scripts/format.sh`
To check one sample for errors: Navigate to the sample folder and run `./gradlew spotlessCheck`
To format one sample: Navigate to the sample folder and run `./gradlew spotlessApply`

## Updates

To update dependencies to their new stable versions, run:

```
./scripts/updateDeps.sh
```

Any other version updates need to be made individually.

## Obsolete Sample Projects

Over time some of our samples become a little stale and are removed to keep the
repository easy to navigate. If you are curious you can still find them in the 
history, however if you are new you might be better served sticking to
the most up to date resources.

| Project                                          | Removed    | Commit                                                              |
| ------------------------------------------------ | -----------|-------------------------------------------------------------------- |
| [Crane](../../tree/v2024.05.00/Crane)         | 2024-08-02 | [ee8e272](../../commit/ee8e27289f4bc36304ee9f04397f49c35f402a65) |
| [Owl](../../tree/v2024.05.00/Owl)             | 2024-08-02 | [ee8e272](../../commit/ee8e27289f4bc36304ee9f04397f49c35f402a65) |
| [Jetsurvey](../../tree/v2024.05.00/Jetsurvey) | 2024-08-02 | [ee8e272](../../commit/ee8e27289f4bc36304ee9f04397f49c35f402a65) |
| [Rally](../../tree/v2024.05.00/Rally)         | 2024-08-02 | [ee8e272](../../commit/ee8e27289f4bc36304ee9f04397f49c35f402a65) |

## License
```
Copyright 2024 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
