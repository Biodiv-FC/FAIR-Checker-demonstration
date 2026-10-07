# FAIR-Checker demonstration plugin

> [!CAUTION]  
> The plugin in this repository is not intended to be used in production as is

The FAIR-Checker demonstration plugin allows to illustrate how the plugin structure works in Fair-Checker as well as the overall structure of the plugin.
The plugin is a simple `yaml` file that can be pulled in the `plugins` directory of the Fair-Checker application.

### Clone the Fair-Checker application

```
git clone https://github.com/IFB-ElixirFr/FAIR-checker.git
```

### Clone the this plugin

```
cd plugins
git clone https://github.com/Biodiv-FC/FAIR-Checker-demonstration
```

## Launching the application

To launch the application, read the instructions in the [Fair-Checker repository](https://github.com/IFB-ElixirFr/fair-checker). The launching process with additional plugins is no different than launching the app with only the regular default plugin.

After validation of the plugin by the Fair-Checker application, the application launches. With this plugin, your Fair-Checker application will provide regular recommendations along side the option to enable tailored recommendations for the improvements of biodiversity resources.

If no error appears, the application will be accessible at [http://localhost:5000](http://localhost:5000)
