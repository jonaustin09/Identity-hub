# Identity-hub

Usage: Run `./identity-hub -sp <SOURCE_PORT>` on host 'B' where <SOURCE_PORT> can be any port number. Now run `./identity-hub -d <MULTIADDR_B>` on node 'A' [`<MULTIADDR_B>` is multiaddress of host 'B' which can be obtained from host 'B' console].

## Build

```
> go build
```

## Usage

On node 'B'

```
> ./identity-hub -sp 3001
Run ./identity-hub -d /ip4/127.0.0.1/tcp/3001/p2p/QmdXGaeGiVA745XorV1jr11RHxB9z4fqykm6xCUPX1aTJo

Got a new stream!
> hi (received messages in green colour)
> hello (sent messages in white colour)
> no
```
