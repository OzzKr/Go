
# web service  port 8089

## <https://go.dev/learn/#tutorials>

<http://localhost:8089/albums/>

## install dependencies
>
> go get .

## execute webservice
>
> go run .

## test webservice with curl
>
> curl <http://localhost:8089/albums/>

## post
>
> curl <http://localhost:8089/albums> \
    --include --header \
    "Content-Type: application/json" \
    --request "POST" --data \
    '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'

## test webservice with httprepl
>
> httprepl <http://localhost:8089/albums>

## httprepl POST body
>
> {"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}