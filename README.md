## DO-Product-Card

### Abraham Hdz

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'do-product-card'
```

```
<ProductCard 
    product={ product }
    initialValues={{
      count: 0,
      maxCount: 15,
    }}
>
  {
    ( { reset, increaseBy, maxCount, isMaxCountReached, count } ) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```