weather-cli
=================
Check the weather for your city from your terminal  

[![Coverage Status](https://coveralls.io/repos/github/riyadhalnur/weather-cli/badge.svg?branch=master)](https://coveralls.io/github/riyadhalnur/weather-cli?branch=master) [![Build Status](https://travis-ci.org/riyadhalnur/weather-cli.svg?branch=master)](https://travis-ci.org/riyadhalnur/weather-cli) [![Build status](https://ci.appveyor.com/api/projects/status/8o1qpopothm62y51/branch/master?svg=true)](https://ci.appveyor.com/project/riyadhalnur/weather-cli/branch/master) [![Dependency Status](https://dependencyci.com/github/riyadhalnur/weather-cli/badge)](https://dependencyci.com/github/riyadhalnur/weather-cli) [![Known Vulnerabilities](https://snyk.io/test/github/riyadhalnur/npm-modules-sync/badge.svg)](https://snyk.io/test/github/riyadhalnur/weather-cli)   

### Install
```shell
$ npm install -g weather-cli
```

```shell
$ weather --help

  Usage
    $ weather <input>

  Options
    --city, -ct City you want to lookup weather for
    --country, -c Country you want to lookup weather for
    --scale, -s Weather scale. Defaults to Celcius
    --help Show this help message
    --version Display version info and exit
    config Set the default location

  Examples
    $ weather -c Dhaka -C Bangladesh
    Dhaka, Bangladesh
    Condition: Partly Cloudy
    Temperature: 32°C

    $ weather config -c Dhaka -C Bangladesh
    Default location set to Dhaka, Bangladesh
```

### License  
Licensed under MIT. See [LICENSE](LICENSE) for more information.  

### Issues  
Report a bug in issues.   

Made with love in Dhaka, Bangladesh by [Riyadh Al Nur](https://verticalaxisbd.com)
