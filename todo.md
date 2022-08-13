## Backend
#### Banco de dados
- [ ] Remover todos `deleted_at` menos o de produto
- [ ] remover price e `unity` de `schedules_has_products`
- [ ] `description` em shedules como nullable
- [ ] adicionar `measurement_unit` em product
- [ ] em `products` renomear `cost_price` para `cost`
- [ ] em `products` tornar `description` como nullable
- [ ] remover tabela `product_prices`
- [ ] colunas que estão `smallint` que não irão passar de 255 podem ser `unsigned tinyint`