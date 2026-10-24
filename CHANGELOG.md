## [0.4.0] - 2026-10-24

This release is published on
[koen-mulder/retrodate](https://github.com/koen-mulder/retrodate/releases),
not on the upstream OrangeTux repository. It includes changes from open pull
requests against [OrangeTux/retrodate](https://github.com/OrangeTux/retrodate).

### Features

- Update metadata search API for Immich v3.2+ compatibility ([#32](https://github.com/OrangeTux/retrodate/pull/32))
- [**breaking**] Make dry-run the default and introduce `--apply-changes` ([#33](https://github.com/OrangeTux/retrodate/pull/33))
- Expand filename date/time parsing; make single-digit months/days opt-in via `--allow-single-digit-date` ([#34](https://github.com/OrangeTux/retrodate/pull/34))
- Skip UUID filenames by default; opt in with `--include-uuid-filenames` ([#35](https://github.com/OrangeTux/retrodate/pull/35))
- Add `--album` to limit processing to a single Immich album ([#36](https://github.com/OrangeTux/retrodate/pull/36))

## [0.3.0] - 2026-05-11


### Features

- [**breaking**] Add flags --overwrite and --threshold. Rename --apply to --if-unset  ([#22](https://github.com/orangetux/retrodate/issues/22))

### Other

- Use `git cliff` to generate CHANGELOG.md ([#24](https://github.com/orangetux/retrodate/issues/24))

## [0.2.2] - 2026-05-06

### Features

- Support more formats, among others DD-MM-YYYY ([#20](https://github.com/orangetux/retrodate/issues/20))
## [0.2.1] - 2026-05-05

### Bug Fixes

- Retrieving search results ([#18](https://github.com/orangetux/retrodate/issues/18))

### Other

- Add note about the current limitations ([#12](https://github.com/orangetux/retrodate/issues/12))
## [0.2.0] - 2026-05-04

### Other

- Allow users to configure years to include in search ([#6](https://github.com/orangetux/retrodate/issues/6))
- Allow users to set timeout for HTTP requests ([#7](https://github.com/orangetux/retrodate/issues/7))
- Extract datetime from wider range of formats ([#9](https://github.com/orangetux/retrodate/issues/9))
- Ignore assets that already have an original date time ([#11](https://github.com/orangetux/retrodate/issues/11))
## [0.1.1] - 2026-05-01

### Other

- Remove release for aarch64-pc-windows-mvc
## [0.1.0] - 2026-05-01

### Other

- Initial commit
- Replace `unwrap()` with proper error reporting
- Colorize fatal errors
- Add -v switch to increase verbosity
- Add validation of host option
- Add integration test ([#1](https://github.com/orangetux/retrodate/issues/1))
- Rebrand to retrodate and add MIT License ([#4](https://github.com/orangetux/retrodate/issues/4))
- Lint, test and release retrodate in CI ([#5](https://github.com/orangetux/retrodate/issues/5))
- Add usage instructions
