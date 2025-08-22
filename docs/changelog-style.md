# CHANGELOG Style Guide

This guide ensures consistent and professional CHANGELOG entries.

------------------------------------------------------------------------

## General Guidelines

-   Use **Markdown** formatting.
-   Follow [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
    conventions.
-   Group entries under clear sections (Added, Changed, Deprecated,
    Removed, Fixed, Security).
-   Keep entries concise, but descriptive enough for users and
    developers.

------------------------------------------------------------------------

## Formatting Rules

-   Use **present tense** ("Add feature X"), not past tense ("Added
    feature X").
-   Start each entry with a verb.
-   Use bullet points, not paragraphs.
-   Avoid internal-only jargon (write for end-users, not just
    developers).

------------------------------------------------------------------------

## Section Examples

### Added

-   Add user profile page with bio and avatar
-   Add API endpoint for exporting reports

### Changed

-   Change authentication flow to use Devise instead of custom solution
-   Update dependencies to latest Rails 8.x

### Deprecated

-   Deprecate support for Ruby 2.7

### Removed

-   Remove legacy Sprockets pipeline
-   Remove unused Admin dashboard

### Fixed

-   Fix login redirect issue for Google OAuth
-   Fix broken pagination on user list

### Security

-   Update Nokogiri to address CVE-2025-1234

------------------------------------------------------------------------

## Example Entry

``` markdown
## [2.0.0] - 2025-08-21

### Added
- Add Rails 8 migration support
- Add Puma as default web server

### Changed
- Change autoloading to Zeitwerk
- Update Ruby version management to use `.ruby-version` file

### Fixed
- Fix Google OAuth login error

### Known Issues
- No test suite present (to be added in future)
```
