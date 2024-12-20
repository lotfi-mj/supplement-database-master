# Supplement Database Master

Comprehensive database structure for tracking supplements, brands, and related data.

## Structure

```
data/
├── brands.csv          # Brand information
├── products.csv        # Product details
├── ingredients.csv     # Base ingredients
├── proprietary.csv     # Proprietary formulations
├── categories.csv      # Category system
├── quality.csv         # Quality and COA data
├── combinations.csv    # Supplement combinations
├── delivery.csv        # Delivery systems
└── research.csv        # Research references
```

## File Formats

### brands.csv
```csv
brand_id,name,website,quality_certifications,manufacturing_standards,country,founding_year,trademarks,patents
TNQ,Toniqq,toniqq.com,GMP,ISO 9001,Netherlands,2020,"Focus+,Energy+",
```

### products.csv
```csv
product_id,brand_id,name,primary_ingredient,prop_forms,dosage,unit,form,serving_size,categories,certifications,price,size,cost_per_serving,price_tier
TNQ001,TNQ,Focus+,Alpha GPC,,300,mg,capsule,2,"nootropics,focus",GMP,39.99,60,1.33,premium
```

## Getting Started

1. Each CSV contains specific data linked through ID fields
2. Follow sample data format
3. Maintain consistent units and naming
4. Use data validation rules provided

## Documentation

See `/docs` folder for detailed guidelines on data entry and validation rules.
