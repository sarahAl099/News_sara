# News Cloud App

A Flutter application that displays news articles from various categories using the NewsAPI.

## Features

- Browse news by categories (Business, Entertainment, Health, Sports, Technology)
- View full articles in WebView
- Cached network images for better performance
- Responsive design

## Getting Started

### Prerequisites

- Flutter SDK (version 3.10.7 or higher)
- Dart SDK
- Android Studio or VS Code with Flutter extensions

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/news-cloud-app.git
   cd news-cloud-app
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Get your API key from [NewsAPI](https://newsapi.org/)
   - Add your API key to `.env`:
     ```
     NEWS_API_KEY=your_api_key_here
     ```

4. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── api/           # API services
├── models/        # Data models
├── Screen/        # UI screens
├── Widget/        # Reusable widgets
└── main.dart      # App entry point
```

## Dependencies

- dio: HTTP client
- cached_network_image: Image caching
- webview_flutter: WebView for articles
- flutter_dotenv: Environment variables

## API

This app uses [NewsAPI](https://newsapi.org/) to fetch news articles.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- NewsAPI for providing the news data
- Flutter team for the amazing framework
