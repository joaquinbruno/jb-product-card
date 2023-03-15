# jb-Product-Card

Este es un paquete de Pruebas de despliegue en NPM

### Joaquin Bruno

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductImage} from 'jb-product-card';
```

```
<ProductCard
           
            product={product}
            
            initialValues={{
              count: 4,
              // maxCount: 10,
            }}
            
          >

          {
            ({reset, isMaxCountReached, maxCount, increaseBy}) => (
              <>
                  <ProductImage />
                  <ProductTitle />
                  <ProductButtons />
                  
              </>
            )
          }
            
</ProductCard>
```