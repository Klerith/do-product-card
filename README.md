# DO-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Fernando Herrera

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'do-product-card';
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