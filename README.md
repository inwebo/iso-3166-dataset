# ISO 3166 Dataset

This project provides a comprehensive dataset of countries and territories according to the ISO 3166 standard.

## Available Languages

The dataset is available in English and French:

- [English Version (iso-3166-dataset-EN.csv)](iso-3166-dataset-EN.csv)
- [French Version (iso-3166-dataset-FR.csv)](iso-3166-dataset-FR.csv)

## File Content

The CSV files contain the following columns:

- **Flag**: The country's flag (in emoji format).
- **Short Name**: Common short name of the country.
- **Short Name Lowercase**: Short name in lowercase for easier searching.
- **Full Name**: Official full name.
- **Alpha-2**: Two-letter country code.
- **Alpha-3**: Three-letter country code.
- **Numeric**: Numeric country code.
- **Independent**: Indicates if the country is independent (true/false).
- **Remarks**: Additional remarks on the territory's status.

## References

For more information about the ISO 3166 standard, you can consult the following resources:

- [ISO 3166 on Wikipedia](https://en.wikipedia.org/wiki/ISO_3166)
- [ISO 3166-1 on Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-1)
- [Official ISO 3166 Page](https://www.iso.org/iso-3166-country-codes.html)
- [ISO Online Browsing Platform (OBP)](https://www.iso.org/obp/ui/#search)

## Usage

This dataset can be used for geolocation applications, country selection forms, or any application requiring standardized information about the world's countries.

### Composer

```bash
composer req inwebo/iso-3166-dataset
```

## License

[GPL-3.0-or-later](LICENSE)
