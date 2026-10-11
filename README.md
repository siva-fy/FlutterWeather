<h1 align="center">FlutterWeather</h1>
<h2 align="center">Updated to Flutter 3.0</h2>


<p align="center">
<img src="https://user-images.githubusercontent.com/60814961/209642694-cc9f7a28-96cc-419a-bb5c-6fb23d7befe2.png" width="30%"></img> 
<img src="https://user-images.githubusercontent.com/60814961/209642769-c81b7288-34d8-4a95-ab14-54a31dbfeb10.png" width="30%"></img> 
<img src="https://user-images.githubusercontent.com/60814961/209642813-6a1a32ae-7a39-48b9-ad95-e99f8cce72fb.png" width="30%"></img> 
</p>

# FlutterWeather

A simple weather App created using [Flutter](https://flutter.dev/) and [Dart](https://dart.dev/) and using API from [OpenWeatherMap](https://openweathermap.org/)

## Features
- Automatically acquire user current location
- Searchable location
- Hourly weather information
- 7 days weather information 

## How to Run
1. Create an account at [OpenWeatherMap](https://openweathermap.org/).
2. Then get your API key from https://home.openweathermap.org/api_keys.
3. Clone the repo
   ```sh
   git clone https://github.com/siva-fy/FlutterWeather.git
   cd FlutterWeather
   ```
4. Install all the packages by typing
   ```sh
   flutter pub get
   ```
5. Navigate to **lib/provider/weatherProvider.dart** and paste your API key to the apiKey variable
   ```dart
   String apiKey = 'Paste Your API Key Here';
   ```
6. Run the app on a connected device or emulator:
   ```sh
   flutter run
   ```

## Project status

This is an earlier Flutter learning project. Its dependencies and weather endpoints
reflect the original implementation; the app has not been rerun with current SDKs
as part of this documentation update. Check API availability and your OpenWeather
plan before running. Keep your API key out of commits. The original screenshots and license information are preserved.


## Contact
- [Bala Siva Sai Megi Reddy Padala](https://github.com/siva-fy) | [Twitter](https://twitter.com/megi_reddy21) | [Instagram](https://www.instagram.com/b_s_s_megi_reddy_padala/)
- If you find the content of this repository useful and you have some extra money, you can donate to me through [PayPal](https://www.paypal.me/megireddy21)

## License
Distributed under the MIT License. See `LICENSE` for more information.
