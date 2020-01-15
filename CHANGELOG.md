# Changelog

This file lists the meaningful changes between released versions.

## Format

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

Entries should have the imperative form, just like commit messages. Start each entry with words like
add, fix, increase, force, etc.. Not added, fixed, increased, forced, etc..

Line wrap the file at 100 characters. That is over here: ------------------------------------------|

### Categories each change falls into

- **Added**: for new features.
- **Changed**: for changes in existing functionality.
- **Deprecated**: for soon-to-be removed features.
- **Removed**: for now removed features.
- **Fixed**: for any bug fixes.
- **Security**: in case of vulnerabilities.

## [Unreleased]

## [0.1.1] - 2020-01-15
### Fixed
- Fix skipping fields in tuple structs and tuple enum variants when deriving `IntoJava`.
- Fix local reference leak when calling `.into_java(env)` on an `IpAddr`, `Ipv4Addr` or `Ipv6Addr`.