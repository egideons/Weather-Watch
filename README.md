<h1 align="center">Weather Watch</h1>
<h2 align="center">Updated to Flutter 3.0</h2>

<p align="center">
<img src="https://user-images.githubusercontent.com/60814961/209642694-cc9f7a28-96cc-419a-bb5c-6fb23d7befe2.png" width="30%"></img> 
<img src="https://user-images.githubusercontent.com/60814961/209642769-c81b7288-34d8-4a95-ab14-54a31dbfeb10.png" width="30%"></img> 
<img src="https://user-images.githubusercontent.com/60814961/209642813-6a1a32ae-7a39-48b9-ad95-e99f8cce72fb.png" width="30%"></img> 
</p>

# Weather Watch

A simple weather App created using [Flutter](https://flutter.dev/) and [Dart](https://dart.dev/) and using API from [OpenWeatherMap](https://openweathermap.org/)

## Features

- Automatically acquires user current location
- Searchable location
- Hourly weather information
- 7 days weather information

## How to Run

1. Create an account at [OpenWeatherMap](https://openweathermap.org/).
2. Then get your API key from https://home.openweathermap.org/api_keys.
3. Clone the repo
   ```sh
   git clone https://github.com/ArizArmeidi/FlutterWeather.git
   ```
4. Install all the packages by typing
   ```sh
   flutter pub get
   ```
5. Navigate to **lib/provider/weatherProvider.dart** and paste your API key to the apiKey variable
   ```dart
   String apiKey = 'Paste Your API Key Here';
   ```
6. Run the App

## Contact

- [Gideon Chukwuoma Chimemerie](https://github.com/egideons) | [Twitter](https://twitter.com/egideonchuks) | [LinkedIn](https://www.linkedin.com/in/gideon-chukwuoma-019203235/)

## License

Distributed under the MIT License. See `LICENSE` for more information.
