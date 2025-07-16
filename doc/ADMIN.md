Use default administrator account to log in:

- login: admin
- password: admin

You can go to Administration menu and choose Settings to modify most of the application settings.

### Custom Turkish translation

During installation and upgrades, the package replaces the following entries in
`config/locales/tr.yml` with `Prosedür`:

```
field_fixed_version
label_attribute_of_fixed_version
label_issue_fixed_version_updated
```
This ensures that the Turkish interface uses the desired terminology and that
changes persist after upgrading.
