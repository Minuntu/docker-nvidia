# nVidia mining tools

## Contains

- tpruvot ccminer ( https://github.com/tpruvot/ccminer )

## Requires

- Docker
- nVidia's docker engine ( https://github.com/NVIDIA/nvidia-docker )

## Run

```
docker run --name ccminer --runtime=nvidia --rm minuntu/nvidia-ccminer -o stratum+tcp://equihash.eu.nicehash.com:3341 -a neoscrypt -u 3FxDYFMeFVxo3TzKDvvWUmuLy6fAAp8ZJ6.worker -p x
```
