# Docker image for Elixir + Node.JS on Ubuntu Xenial 64-bit

This repository contains scripts for building a Docker image that contains a 
lightweight build of Erlang/OTP, Elixir and Node.JS based on Ubuntu Xenial 
64-bit.

See [Docker image for Erlang/Elixir](https://github.com/radiokit/docker-elixir-light-xenial64)
for more information about Erlang/Elixir configuration.

## Building

If you don't want to use automated build from [Docker Hub](https://hub.docker.com/r/radiokit/elixir-light-nodejs-ubuntu-xenial64)
you can type the following command in the repository's directory:

```
docker build -t radiokit/elixir-light-nodejs-ubuntu-xenial64 .
```

## Versioning

The image is tagged using the following scheme:

`OTP_VERSION-ELIXIR_VERSION-REBAR_VERSION-REBAR3_VERSION-NODEJS_MAJOR_VERSION-REVISION`

e.g.

`19.3.6.1-1.4.5-2.6.4-3.4.1-8-0`

## License

MIT

## Authors

* Marcin Lewandowski ([mspanc](https://github.com/mspanc), marcin@radiokit.org)
