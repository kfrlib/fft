# kfr-fft
Highly optimized FFT

KFR is a fast, modern C++ DSP framework, DFT/FFT, Audio resampling, FIR/IIR Filtering, Biquad, vector functions (SSE, AVX)

## Features

* FFT is optimized for SSE2, SSE3, SSE4.x, AVX and AVX2 processors
* Both double and single precision

## Performace

FFT (double precision, sizes from 1024 to 16777216)
See [fft benchmark](https://github.com/kfrlib/fft-benchmark) for details about benchmarking process.

![FFT Performance](img/fft_performance.png)

## Prerequisities

* macOS: XCode 6.3, 6.4, 7.x, 8.x
* Windows: MinGW 5.2 and Clang 3.7 or newer
* Ubuntu: GCC 5.1 and Clang 3.7 or newer
* CoMeta metaprogramming library (already included)

## Tests

Execute `build.py` to run the tests or run tests manually from the `tests` directory

Tested on the following systems:

* OS X 10.11.4 / AppleClang 7.3.0.7030031
* Ubuntu 14.04 / gcc-5 (Ubuntu 5.3.0-3ubuntu1~14.04) 5.3.0 20151204 / clang version 3.8.0 (tags/RELEASE_380/final)
* Windows 8.1 / MinGW-W64 / clang version 3.8.0 (branches/release_38)

## Planned for future versions

* DFT for any lengths (not only powers of two)

## License

KFR is dual-licensed, available under both commercial and open-source GPL license.

If you want to use KFR in commercial product or a closed-source project, you need to [purchase a Commercial License](http://kfrlib.com/purchase-license)
