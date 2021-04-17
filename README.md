# QuiltMC/Intermediary mappings

This repository contains the match information between different versions of Minecraft published by the Quilt project, as well as the "intermediary" mappings we use, that is an intermediary naming form which tries to keep names
the same across versions and mapping changes.

## Files included in this repo

* __mappings/<mcversion>.tiny__: Intermediary mappings in the Tiny mapping format.
* __matches/*.matches__: Matches between Minecraft versions, created with the aid of Matcher, published by the Quilt project.

## Generating / updating mappings

In general, you're going to want to use the following tools:

* [Matcher](https://github.com/QuiltMC/matcher) is a tool to create a match file between two JARs. In addition, it can load Enigma-format mappings, which can be used as an aid in figuring out changes.
* [Stitch](https://github.com/QuiltMC/stitch) is a toolset for generating mappings based on match files. "generateIntermediary" is used to start a fresh chain of intermediary mappings, while "updateIntermediary" is used to add a new entry to the chain based on the previous entry and a matches file.

## License

As with the named mappings, we provide the intermediary mappings under the Creative Commons Zero license, so all can benefit.
