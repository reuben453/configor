# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2017-08-19

### Added
- New boolean config key (ErrorOnUnmatchedKeys) to modify the behavior of Configor.

### Changed
- Use yaml.v2 library instead of yaml.v1 for unmarshalling yaml files. This is a breaking change if, for example, you defined a SetYAML function for decoding custom types. Here is a [list of changes in yaml.v2](https://blog.labix.org/2014/09/22/announcing-yaml-v2-for-go).

## [1.1.0] - 2017-07-04

[Xzya/configor](https://github.com/Xzya/configor) was forked from [jinzhu/configor](https://github.com/jinzhu/configor) and contains the following changes. This library ([reuben453/configor](https://github.com/reuben453/configor)) was forked from [Xzya/configor](https://github.com/Xzya/configor).

### Changed
- Ignore unexported fields. Configor no longer panics when it encounters unexported fields in the config struct it is populating.
This closes https://github.com/jinzhu/configor/issues/23.

## [1.0.0]

Library created by jinzhu [jinzhu/configor](https://github.com/jinzhu/configor)