FROM julia:1.6-buster

WORKDIR /opt/app

COPY *.jl ./

ENTRYPOINT [ "julia", "primes_unpeeled.jl" ]
