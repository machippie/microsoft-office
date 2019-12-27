
## Default Variables

### microsoft_office_apps

List of applications to use

#### Default value

```yaml
microsoft_office_apps:
  - Microsoft\ Excel
  - Microsoft\ PowerPoint
  - Microsoft\ Word
```

### microsoft_office_packages

List of packages to install

#### Default value

```yaml
microsoft_office_packages:
  - microsoft-excel
  - microsoft-powerpoint
  - microsoft-word
```

### microsoft_office_user

User to run user-specific commands

#### Default value

```yaml
microsoft_office_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
