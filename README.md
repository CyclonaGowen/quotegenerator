# Random Quote Generator

Random Quote Generator is a simple yet powerful web application that generates random quotes. The application pulls data from an API that hosts a vast collection of quotes from various authors. Each quote also comes with associated tags that classify the quote's theme.

## Features

- Generates a random quote from a diverse set of authors.
- Provides a feature to share a quote directly on Twitter.
- If the author of a quote is not available or anonymous, it's replaced with "Unknown."

## Usage

Visit the Random Quote Generator and click on the "Generate Quote" button to generate a random quote. To filter the quotes by a specific tag, simply enter the tag into the search bar and hit enter. If you find a quote that resonates with you, click on the "Share to Twitter" button to share it with your followers.

## API Used

The Random Quote Generator uses an API hosted on Github pages. The API endpoint is:

```https://jacintodesign.github.io/quotes-api/data/quotes.json```

The API returns an array of quote objects. Each quote object has `text`, `author`, and `tags` properties.

