# Data Model

The model follows a star‑schema‑inspired structure.

## Fact Table
FactPartido:
- FechaId  
- RivalId  
- Categoria  
- Metrica  
- Valor  
- MetricaId  

## Dimensions
- DimMetrica  
- DimRival  
- DimFecha