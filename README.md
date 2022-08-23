# EMC-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Enrique Moreno

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'emc-product-card';
```

```
<ProductCard 
    product={ product }
    initialValues={{
        count: 6,
        // maxCount: 10,
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy  }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```
