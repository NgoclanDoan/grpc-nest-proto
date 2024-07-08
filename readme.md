## Tạo project

``npm i -g @nestjs/cli``

````
mkdir grpc-nest-proto
nest new grpc-nest-api-gateway -p npm
nest new grpc-nest-auth-svc -p npm
nest new grpc-nest-product-svc -p npm
nest new grpc-nest-order-svc -p npm
````

## Shared Proto Repository
````
// Khởi tạo project grpc-proto
cd grpc-nest-proto 
npm init --y 
git init 
mkdir proto 
touch proto/auth.proto && touch proto/product.proto && touch proto/order.proto 
code .
````
