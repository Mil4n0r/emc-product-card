# EMC-Product-Card

Este es un paquete de pruebas de despliegue en NPM

## Enrique Moreno Carmona

```
import { ProductCard, ProductImage, ProductTitle,  ProductButtons } from 'emc-product-card
```

```
<ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ count, increaseBy, isMaxCountReached, maxCount, reset }) => (
    <>
      <ProductCard.Image />
      <ProductCard.Title />
      <ProductCard.Buttons />
    </>
  )}
</ProductCard>
```
