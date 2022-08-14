## Backend
#### Banco de dados
- [x] Remover todos `deleted_at` menos o de produto
- [x] remover price e `unity` de `schedules_has_products` add to products
- [X] `description` em shedules como nullable
- [x] adicionar `measurement_unit` em product
- [x] em `products` renomear `cost_price` para `cost`
- [x] em `products` tornar `description` como nullable
- [x] remover tabela `product_prices`
- [x] colunas que estão `smallint` que não irão passar de 255 podem ser `unsigned tinyint`