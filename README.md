[N|Solid](https://safehaven.io/img/logo_color.png)](https://safehaven.io/)

# Platform
Safehaven platform code (core)

Source code will be uploaded shortly

# Demo implementations (at own risk)

As often with crypto libraries, there is a lot of ssss implementations around that does not meet cryptographic standards (a.k.a. is insecure). Some details—like integrity checks and side-channel resistance—are often forgotten. But these slip-ups can often fully compromise the security of the scheme. 

```
  Some improvements that needs to be implemented:

  Be side channel resistant (timing, branch, cache)
  Secure the shared secret with a MAC
  Use the platform (OS) randomness source
```

