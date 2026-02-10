# XML and DTD Examples

This repository contains XML documents with different DTD (Document Type Definition) implementations as practice exercises.

## Contents

### 1. Employee Registry
XML document representing employee records in a company. Each employee includes:
- Name
- ID number
- Position
- Salary

**Three DTD versions:**
- **Internal DTD**: DTD declarations embedded within the XML file
- **External DTD**: DTD declarations in a separate `.dtd` file
- **Mixed DTD**: Combination of external DTD reference with internal declarations

### 2. Purchase Invoices
XML document for purchase invoices including:
- Purchase date
- Customer information (name, address, phone, email)
- Products purchased with:
  - Product name
  - Quantity
  - Price

### 3. Event Calendar
XML document for event management including:
- Event title
- Date
- Optional description
- Optional location

## File Structure
```
.
├── empleados_interno.xml      # Employee registry with internal DTD
├── empleados_externo.xml      # Employee registry with external DTD
├── externo1.dtd               # External DTD file for employees
├── empleados_mixto.xml        # Employee registry with mixed DTD
├── factura.xml                # Purchase invoice example
└── calendario.xml             # Event calendar example
```

## Validation

These XML files can be validated using standard XML parsers that support DTD validation.

## Notes

- All optional elements are marked with `?` in the DTD
- Elements that must appear at least once are marked with `+`
- Character encoding is UTF-8
