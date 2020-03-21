# Ansible Galaxy Role Import

A GitHub Action to import a role into [Ansible Galaxy][galaxy].

## Inputs

### `galaxy_api_key`

Ansible Galaxy API Key.

## Usage

```yaml
uses: 0x022b/galaxy-role-import-action@v1
with:
  galaxy_api_key: ${{ secrets.galaxy_api_key }}
```

## License

This project is licensed under the MIT License.

[galaxy]: https://galaxy.ansible.com/
