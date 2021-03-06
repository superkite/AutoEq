# Sony MDR-G75
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.8; 45 -1.8; 49 -3.0; 54 -4.3; 60 -5.6; 66 -6.7; 72 -7.6; 79 -8.4; 87 -9.2; 96 -9.7; 106 -10.2; 116 -10.6; 128 -10.6; 141 -10.8; 155 -10.8; 170 -10.7; 187 -10.4; 206 -10.1; 227 -9.6; 249 -9.2; 274 -8.9; 302 -8.1; 332 -7.6; 365 -7.0; 402 -6.6; 442 -7.0; 486 -6.9; 535 -6.7; 588 -6.5; 647 -6.4; 712 -6.3; 783 -6.4; 861 -6.5; 947 -6.7; 1042 -6.9; 1146 -7.0; 1261 -7.3; 1387 -8.0; 1526 -9.1; 1678 -10.2; 1846 -10.1; 2031 -8.2; 2234 -6.1; 2457 -3.6; 2703 -1.6; 2973 -1.4; 3270 -2.4; 3597 -5.4; 3957 -8.9; 4353 -8.3; 4788 -4.1; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -7.3; 9330 -8.3; 10263 -6.6; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-G75 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-G75 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 0.72 | 7.3 dB   |
| Peaking | 123 Hz   | 0.74 | -5.4 dB  |
| Peaking | 2939 Hz  | 2.34 | 13.0 dB  |
| Peaking | 3920 Hz  | 0.69 | -10.1 dB |
| Peaking | 5619 Hz  | 1.94 | 13.2 dB  |
| Peaking | 665 Hz   | 1.36 | 0.7 dB   |
| Peaking | 1741 Hz  | 3.16 | -4.0 dB  |
| Peaking | 1838 Hz  | 0.71 | 1.4 dB   |
| Peaking | 4147 Hz  | 8.9  | -2.1 dB  |
| Peaking | 12478 Hz | 2.99 | 0.6 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 8.1 dB  |
| Peaking | 62 Hz    | 1.41 | -0.3 dB |
| Peaking | 125 Hz   | 1.41 | -4.8 dB |
| Peaking | 250 Hz   | 1.41 | -2.2 dB |
| Peaking | 500 Hz   | 1.41 | 0.8 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.6 dB |
| Peaking | 2000 Hz  | 1.41 | -1.3 dB |
| Peaking | 4000 Hz  | 1.41 | 3.0 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.0 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-G75/Sony%20MDR-G75.png)