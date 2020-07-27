![RVW Logo](https://red-van-workshop.s3.us-east-1.amazonaws.com/logo.png "RVW Logo")

SFCC Catalog Inventory
===

Create Salesforce Commerce Cloud Inventory XML from Catalog XML

Installation
---

You can install this package via NPM:

```bash
npm install -g sfcc-catalog-inventory
```

Usage
---

The most common usage will look like this:

```bash
sfcc-catalog-inventory -i /path/to/catalog.xml
```

**FLAGS:**

Name     | Param      | Alias      | Required | Definition
---------|------------|------------|----------|------------------------------------
Input    | `-i`       | `--input`  | Yes      | Path to SFCC Catalog XML File
Output   | `-o`       | `--output` | No       | Path to save XML file ( Defaults to Current Directory )
Name     | `-n`       | `--name`   | No       | Name of Inventory List ( Defaults to Catalog Name )

**EXAMPLES:**

```bash
sfcc-catalog-inventory -i /path/to/catalog.xml

sfcc-catalog-inventory -i /path/to/catalog.xml -n custom-name
sfcc-catalog-inventory --input /path/to/catalog.xml --name custom-name

sfcc-catalog-inventory -i /path/to/catalog.xml -o /path/to/inventory.xml
sfcc-catalog-inventory --input /path/to/catalog.xml --output /path/to/inventory.xml

sfcc-catalog-inventory -i /path/to/catalog.xml -n custom-name -o /path/to/inventory.xml
sfcc-catalog-inventory --input /path/to/catalog.xml --name custom-name --output /path/to/inventory.xml
```

Troubleshooting
---

Need help on how to run this tool?  Just run the command without options to see example usage & instruction.

```bash
sfcc-catalog-inventory
```
