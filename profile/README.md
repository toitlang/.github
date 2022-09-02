## Getting started 🥳

Get started with the Toit platform by [downloading](https://github.com/toitlang/jaguar#how-do-i-use-it) 
the open source Jaguar tooling — and experience live reloading on your ESP32s today. It takes less
than 5 minutes 🎉

Running code on your devices is as easy as pie through Jaguar and everything works over your local
WiFi with no cloud tie-ins:

``` sh
jag run hello.toit
```

You can even install new containers on your devices dynamically. Such containers contain drivers and 
functionality exposed as discoverable micro-services, so you can build decoupled and robust architectures
for your favorite micro-controllers: 

``` sh
$ jag container list
DEVICE      IMAGE                                  NAME
kind-dish   b7ddd53b-7b1c-59db-af1e-7d8215305649   jaguar
kind-dish   790ad219-5e9b-5828-b000-bd2b2289cbe8   http
```

Happy hacking!
