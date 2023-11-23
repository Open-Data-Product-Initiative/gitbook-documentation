# Versioning practices

### Semver is used

ODPI uses [SemVer](https://semver.org/)—semantic versioning—on our components. The three types of versions are:

* **Major** versions contain [breaking changes.](breaking-changes.md)
* **Minor** versions add new features or deprecate existing features without [breaking changes.](breaking-changes.md)
* **Patch** versions fix defects or optimize existing features without breaking changes.

Version numbers are presented `Major.Minor.Patch`, for example, `3.2.1`.



Once a versioned package has been released, the contents of that version must not be modified. Any modifications must be released as a new version.

The major version must be incremented for all breaking changes.

The minor version must be incremented if:

* New, backward-compatible functionality is introduced to the public specification.
* Any public specification functionality is marked as deprecated

The patch version must be reset to `0` when minor version is incremented

