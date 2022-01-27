# Asterisk on Alpine Linux

## Build

```bash
docker build -t asterisk-alpine .
```

## Run

```bash
docker run -it --rm -p 5060:5060/udp -p 18000-18100:18000-18100/udp asterisk-alpine
```
