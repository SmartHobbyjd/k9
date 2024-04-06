# k9
This is how I started the project :

The Project Main Directory is k9
mkdir assets cmd pkg test
touch docker-compose.yml kennel-dockerfile postgres-dockerfile breader-dockerfile k9-dockerfile products-dockerfile 
cd pkg 
mkdir common kennel breader k9 products db grpcapi
touch grpcapi/api.proto grpcapi/build.sh
touch common/common.go db/setup.sql kennel/kennel.go breader/breader.go k9/k9.go products/products.go
cd ../cmd 
mkdir common kennel breader k9 products db grpcapi
touch kennel/main.go k9/main.go breader/main.go products/main.go

The GitHub url is : https://github.com/SmartHobbyjd/k9
