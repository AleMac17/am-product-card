# AM-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Alejandro Maciá

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'am-product-card';
```

```
<ProductCard product={product} initialValues={{ count: 6, maxCount: 10 }}>
        {({}) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>
```
