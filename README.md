# KRONOS 360
FVD-KRONOS-00001 | Safe Creative: 2608096674952 / 2608096678240 / 2608156740085
Propiedad de Marco Antonio Rojas Valdovinos

## Que es
Plataforma de evidencias digitales con Ed25519 + SHA3-512 + ML-DSA post-cuantico

## Estructura
src/kronos360/ -> codigo
docs/images/ -> imagenes doradas
keys/ -> VACIA (nunca subir .pem)

## Uso rapido
kronos360 keygen keys/emisor-01
kronos360 issue doc.pdf evidencia.json --record-id FVD-KRONOS-00001 --private-key keys/emisor-01/private.pem --public-key keys/emisor-01/public.pem
kronos360 verify doc.pdf evidencia.json --public-key keys/emisor-01/public.pem

## Estado
VERDE 0 ACTIVO = valido
ROJO 1 ALTERADO = falsificado