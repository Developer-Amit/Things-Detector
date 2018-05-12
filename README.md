#Things Detector - A Javascript AI experiment.

Behind the scenes Thing Translator is using Google's
[Cloud Vision](https://cloud.google.com/vision/) and
[Translate](https://cloud.google.com/translate/) APIs.


### Development

To start a development server on `9966` that will watch for code changes simply run:
```
$ npm run dev
```

To optimize the output for production run:
```
$ npm run bundle
```

When you needed to run your server on a IP instead of localhost just replace localhost with IP on the package ie. localhost = 192.168.1.116

If you'd like to create a fork or a similar project, you'll need to setup some
API keys on [Google Cloud Platform](https://cloud.google.com/).
