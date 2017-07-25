## OpenWeatherMap-Java-Library

**You need an APPID to use the OpenWeatherMap API. Head on over to their [website](http://openweathermap.org/) if you don't already have one.**


## Download

#### Step 1. Add the JitPack repository to your root ```build.gradle``` file.

``` java
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

#### Step 2 : Download via ```Gradle```:

``` compile 'com.github.KwabenBerko:OpenWeatherMap-Android-Library:v1.0.0'```

**Note: Remember to include the INTERNET permission to your manifest file**

## Usage

#### Instantiate the OpenWeatherMapHelper class

``` java 
OpenWeatherMapHelper helper = new OpenWeatherMapHelper();
```
#### Set your APPID (Required) 

``` java 
helper.setAppId(getString(R.string.OPEN_WEATHER_MAP_APP_ID));
```

#### Set your Units (Optional, fahrenheit by default) 

``` java 
helper.setUnits("imperial");
```

##### Unit Options: 

1. ```"imperial"```

2. ```"fahrenheit"```


## Features

### Current Weather
#### Get current weather by City Name:
#### Get current weather by City ID:
#### Get current weather by City Geographic Coordinates:
#### Get current weather by City Zip Code:
