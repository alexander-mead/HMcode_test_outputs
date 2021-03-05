### HMcode test outputs ###

This repository contains test files that should be agreed upon by any code wishing to call itself `HMcode`. Each `.txt` file contains the power spectrum at a number of different wavenumbers and scale factors. The first column of each file gives the wavenumbers [h/Mpc] while subsequent columns give the power spectrum (dimensionless Delta^2(k)) at 9 different scale factors (0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0).

The files are labelled according to a bizarre convention that only makes sense based on my private `HMcode` version. The translations for the `HMcode` versions are:

`hm51`: HMcode (2015; https://arxiv.org/abs/1505.07833)
`hm56`: HMcode (2016; https://arxiv.org/abs/1602.02154)
`hm123`: HMcode (2020; https://arxiv.org/abs/2009.01858)
`hm124`: HMcode (2020 with feedback; https://arxiv.org/abs/2009.01858)

The translations for the cosmological models are:

```
cos26:
Om_m = 0.30
Om_b = 0.05
h = 0.7
ns = 0.96
sig8 = 0.8
As = 1.97269e-9
w0 = -1.
wa = 0.
mnu = 0.
logT = 7.8
```

```
cos56:
Om_m = 0.3158
Om_b = 0.04939
h = 0.6732
ns = 0.96605
sig8 = 0.8120
As = 2.08924e-9
w0 = -1.
wa = 0.
mnu = 0.06
```

`cos241:`
The same as `cos26` but for:
```
w0 = -0.7
As = 2.46981e-9
```

`cos242:`
The same as `cos26` but for:
```
w0 = -1.3
As = 1.75070e-9
```

`cos243:`
The same as `cos26` but for:
```
mnu = 0.3
As = 2.35868e-9
```

`cos244:`
The same as `cos26` but for:
```
mnu = 0.9
As = 3.43507e-9
```

`cos245:`
The same as `cos26` but for:
```
ns = 0.7
As = 2.38515e-9
```

`cos246:`
The same as `cos26` but for:
```
ns = 1.3
As = 1.47601e-9
```

`cos247:`
The same as `cos26` but for:
```
Om_b = 0.01
As = 1.20028e-9
```

`cos248:`
The same as `cos26` but for:
```
Om_b = 0.1
As = 3.88822e-9
```

`cos249:`
The same as `cos26` but for:
```
wa = 0.9
As = 3.35538e-9
```

`icos250:`
The same as `cos26` but for:
```
logT = 7.6
```

`icos251:`
The same as `cos26` but for:
```
logT = 8.0
```
