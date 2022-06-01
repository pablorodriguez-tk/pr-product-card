# PR-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Pablo Rodriguez

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'pr-product-card'
```

```
      <ProductCard
        product={product}
        initialValues={{
          count: 4,
          // maxCount: 10,
        }}
      >
        {({
          count,
          increaseBy,
          isMaxCountReached,
          product,
          reset,
          maxCount,
        }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```
