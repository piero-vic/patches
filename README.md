[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Patches: A Collection of VCV Rack Patches
VCV Rack is a virtual modular synthesizer. All preset are text files in JSON format so they work great with version control.

All `.vcv` files contains 3 key value pairs.

```json
{
  "version": "1.1.6",
  "modules": [],
  "cables": []
}
```

The modules key contains an array of objects that represent modules inside the program.

```json
{
  "id": 4,
  "plugin": "Fundamental",
  "version": "1.4.0",
  "model": "VCF",
  "params": [
    {
      "id": 0,
      "value": 0.0
    },
    {
      "id": 1,
      "value": 0.5
    },
    {
      "id": 2,
      "value": 0.234000027
    },
    {
      "id": 3,
      "value": 1.0
    },
    {
      "id": 4,
      "value": 0.0
    }
  ],
  "leftModuleId": 3,
  "rightModuleId": 6,
  "pos": [
    18,
    0
  ]
},
```

The cables key contains an array of objects that represent a connection inside the program.

```json
{
  "id": 0,
  "outputModuleId": 5,
  "outputId": 0,
  "inputModuleId": 3,
  "inputId": 0,
  "color": "#c91847"
},
```

## License

Licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). See LICENSE for more info.
