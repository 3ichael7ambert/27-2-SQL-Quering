

```bash
psql > seed_products.sql
psql -d products_db -a -f queries_products.sql
\dt
psql < seed_playstore.sql
TABLE products;
```