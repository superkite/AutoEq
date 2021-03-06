# JBL Everest Elite 700 Wired Active
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.5; 23 -8.4; 25 -9.1; 28 -9.8; 31 -10.0; 34 -10.1; 37 -10.0; 41 -9.7; 45 -9.2; 49 -8.7; 54 -8.0; 60 -7.2; 66 -6.6; 72 -6.3; 79 -6.2; 87 -6.3; 96 -6.7; 106 -6.8; 116 -6.7; 128 -6.5; 141 -6.3; 155 -6.3; 170 -6.8; 187 -7.2; 206 -6.8; 227 -6.4; 249 -6.8; 274 -6.4; 302 -5.8; 332 -6.1; 365 -5.5; 402 -5.5; 442 -5.4; 486 -6.2; 535 -6.2; 588 -5.8; 647 -6.0; 712 -6.3; 783 -6.3; 861 -6.5; 947 -6.8; 1042 -6.9; 1146 -6.7; 1261 -8.0; 1387 -8.1; 1526 -8.8; 1678 -9.6; 1846 -10.4; 2031 -11.1; 2234 -11.8; 2457 -11.3; 2703 -9.8; 2973 -8.0; 3270 -6.8; 3597 -6.2; 3957 -5.0; 4353 -3.1; 4788 -0.6; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.3; 8482 -9.1; 9330 -10.1; 10263 -7.8; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`JBL Everest Elite 700 Wired Active GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `JBL Everest Elite 700 Wired Active ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 34 Hz   | 1.53 | -3.9 dB |
| Peaking | 468 Hz  | 1.15 | 0.9 dB  |
| Peaking | 2230 Hz | 1.49 | -6.0 dB |
| Peaking | 5512 Hz | 1.46 | 7.5 dB  |
| Peaking | 8903 Hz | 2.89 | -5.5 dB |
| Peaking | 76 Hz   | 4.29 | 0.9 dB  |
| Peaking | 190 Hz  | 6.76 | -0.9 dB |
| Peaking | 3058 Hz | 6.5  | 0.3 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -4.1 dB |
| Peaking | 62 Hz    | 1.41 | 0.2 dB  |
| Peaking | 125 Hz   | 1.41 | 0.0 dB  |
| Peaking | 250 Hz   | 1.41 | -0.1 dB |
| Peaking | 500 Hz   | 1.41 | 0.9 dB  |
| Peaking | 1000 Hz  | 1.41 | 0.9 dB  |
| Peaking | 2000 Hz  | 1.41 | -6.6 dB |
| Peaking | 4000 Hz  | 1.41 | 4.7 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.1 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/JBL%20Everest%20Elite%20700%20Wired%20Active/JBL%20Everest%20Elite%20700%20Wired%20Active.png)