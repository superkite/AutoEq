# Pioneer SE-MJ31
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -0.5; 66 -1.8; 72 -3.5; 79 -5.1; 87 -6.5; 96 -7.5; 106 -7.9; 116 -8.0; 128 -8.4; 141 -8.5; 155 -8.5; 170 -8.4; 187 -8.0; 206 -7.9; 227 -7.6; 249 -7.5; 274 -7.2; 302 -7.2; 332 -7.4; 365 -7.1; 402 -7.3; 442 -7.4; 486 -7.5; 535 -7.8; 588 -7.7; 647 -8.0; 712 -8.1; 783 -8.0; 861 -7.6; 947 -7.1; 1042 -7.7; 1146 -9.4; 1261 -11.5; 1387 -14.0; 1526 -13.8; 1678 -14.9; 1846 -14.9; 2031 -11.5; 2234 -8.0; 2457 -5.5; 2703 -3.4; 2973 -1.4; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.6; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -2.8; 7010 -10.1; 7711 -8.4; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -7.5; 16529 -8.1; 18182 -8.6; 20000 -10.8
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Pioneer SE-MJ31 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Pioneer SE-MJ31 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 55 Hz    | 0.43 | 11.2 dB  |
| Peaking | 103 Hz   | 0.6  | -9.3 dB  |
| Peaking | 1708 Hz  | 1.6  | -12.3 dB |
| Peaking | 3695 Hz  | 0.75 | 8.5 dB   |
| Peaking | 7288 Hz  | 5.35 | -7.4 dB  |
| Peaking | 923 Hz   | 1.46 | -2.0 dB  |
| Peaking | 960 Hz   | 3.32 | 3.4 dB   |
| Peaking | 4077 Hz  | 6.79 | -1.1 dB  |
| Peaking | 5939 Hz  | 7.39 | 3.0 dB   |
| Peaking | 20850 Hz | 0.22 | -3.5 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-9.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.8 dB  |
| Peaking | 62 Hz    | 1.41 | 4.2 dB  |
| Peaking | 125 Hz   | 1.41 | -3.4 dB |
| Peaking | 250 Hz   | 1.41 | -0.4 dB |
| Peaking | 500 Hz   | 1.41 | -0.3 dB |
| Peaking | 1000 Hz  | 1.41 | -1.7 dB |
| Peaking | 2000 Hz  | 1.41 | -7.5 dB |
| Peaking | 4000 Hz  | 1.41 | 10.5 dB |
| Peaking | 8000 Hz  | 1.41 | -2.1 dB |
| Peaking | 16000 Hz | 1.41 | -1.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Pioneer%20SE-MJ31/Pioneer%20SE-MJ31.png)