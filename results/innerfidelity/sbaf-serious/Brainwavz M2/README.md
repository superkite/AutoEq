# Brainwavz M2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.6; 28 -1.0; 31 -1.6; 34 -2.1; 37 -2.6; 41 -3.2; 45 -3.7; 49 -4.2; 54 -4.8; 60 -5.4; 66 -5.9; 72 -6.4; 79 -7.1; 87 -7.6; 96 -8.1; 106 -8.6; 116 -8.8; 128 -9.1; 141 -9.4; 155 -9.7; 170 -9.8; 187 -9.8; 206 -9.9; 227 -9.7; 249 -9.6; 274 -9.4; 302 -9.2; 332 -8.9; 365 -8.6; 402 -8.3; 442 -7.8; 486 -7.7; 535 -7.4; 588 -6.9; 647 -6.7; 712 -6.8; 783 -6.7; 861 -7.1; 947 -7.7; 1042 -8.4; 1146 -9.0; 1261 -9.6; 1387 -10.7; 1526 -11.4; 1678 -11.6; 1846 -10.5; 2031 -7.6; 2234 -5.5; 2457 -5.6; 2703 -3.7; 2973 -0.9; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -2.0; 4788 -3.6; 5267 -3.9; 5793 -3.5; 6373 -2.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Brainwavz M2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Brainwavz M2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 23 Hz   | 0.63 | 6.2 dB  |
| Peaking | 176 Hz  | 0.62 | -3.7 dB |
| Peaking | 1599 Hz | 2.01 | -6.2 dB |
| Peaking | 3455 Hz | 1.55 | 7.0 dB  |
| Peaking | 6464 Hz | 6.29 | 3.7 dB  |
| Peaking | 714 Hz  | 2.58 | 0.8 dB  |
| Peaking | 1093 Hz | 4.55 | -0.6 dB |
| Peaking | 8370 Hz | 3.64 | -0.8 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.1 dB  |
| Peaking | 62 Hz    | 1.41 | 0.2 dB  |
| Peaking | 125 Hz   | 1.41 | -2.6 dB |
| Peaking | 250 Hz   | 1.41 | -3.2 dB |
| Peaking | 500 Hz   | 1.41 | 0.3 dB  |
| Peaking | 1000 Hz  | 1.41 | -1.8 dB |
| Peaking | 2000 Hz  | 1.41 | -3.3 dB |
| Peaking | 4000 Hz  | 1.41 | 7.4 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.3 dB |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Brainwavz%20M2/Brainwavz%20M2.png)