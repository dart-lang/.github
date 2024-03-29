# How to Contribute

We'd love to accept your patches and contributions to this project. There are
just a few small guidelines you need to follow.

## Contributor License Agreement

Contributions to this project must be accompanied by a Contributor License
Agreement (CLA). You (or your employer) retain the copyright to your
contribution; this simply gives us permission to use and redistribute your
contributions as part of the project. Head over to
<https://cla.developers.google.com/> to see your current agreements on file or
to sign a new one.

You generally only need to submit a CLA once, so if you've already submitted one
(even if it was for a different project), you probably don't need to do it
again.

## Code Reviews

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

## Coding style

The Dart source code in this repo follows the:

  * [Dart style guide](https://dart.dev/guides/language/effective-dart/style)

You should familiarize yourself with those guidelines.

## Pubspec versioning

The first change to a package after a publish needs to increment the package's
pubspec version. Additional changes may also require pubspec version updates;
see our
[package maintenance wiki](https://github.com/dart-lang/sdk/wiki/External-Package-Maintenance#making-a-change)
for a description of the process.

## Changelog entries

Most changes should be accompanied by a new entry in the CHANGELOG.md file. A
good rule of thumb is that if the change is user-facing, it should have a
changelog entry. This includes changes to documentation, like changes to the
README.md file or to dartdoc documentation.

And as a rule-of-thumb, the pubspec version and the changelog version should
always agree.

## Testing

Changes to dart-lang repos must have tests, except for PRs that:

- only affect comments (including documentation)
- only affect code inside the `.github` directory
- only affect `.md` files
- are generated by automated bots (rollers)
- have an explicit exemption from a repository contributor

Repository contributors may indicate that a PR should have a test, even for the
general exemptions above.

## File headers

All files in the Dart project must start with the following header; if you add a
new file please also add this. The year should be a single number stating the
year the file was created (don't use a range like "2011-2012"). Additionally, if
you edit an existing file, you shouldn't update the year.

    // Copyright (c) 2023, the Dart project authors.  Please see the AUTHORS file
    // for details. All rights reserved. Use of this source code is governed by a
    // BSD-style license that can be found in the LICENSE file.

## Community Guidelines

This project follows
[Google's Open Source Community Guidelines](https://opensource.google/conduct/).

We pledge to maintain an open and welcoming environment. For details, see our
[code of conduct](https://dart.dev/code-of-conduct).
