# Cover Crop Extension Specification

- **Title:** Cover Crop
- **Identifier:** <https://fiboa.github.io/management-practices/v0.1.0/schema.yaml>
- **Property Name Prefix:** cover_crop
- **Extension Maturity Classification:** Proposal
- **Owner**: TBD

This extension describes cover crop management practices.

It started as a general extension for all types of management practices,
but evolved to just be focused on cover crops.

- Examples:
  - [GeoJSON](examples/geojson/)
  - [GeoParquet](examples/geoparquet/)
- [Schema](schema/schema.yaml)
- [Changelog](./CHANGELOG.md)

## Properties

The properties in the table below can be used in these parts of fiboa documents:

- [ ] Collection
- [x] Feature Properties

| Property Name      | Type    | Description |
| ------------------ | ------- | ----------- |
| cover_crop:present | boolean | Whether there is cover crop on this field. |
| cover_crop:type    | string  | What type of cover crop. |

## Contributing

See the [contributing guideline](CONTRIBUTING.md) for more details.
