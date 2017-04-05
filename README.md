# Telegram Messenger for iOS

## Set up
- `git clone https://github.com/X140Yu/Telegram.git`
- `cd Telegram`
- `git submodule update --init --recursive`
- `open Telegram.xcworkspace`

Now you can build and run the project.

> Note, this version uses the [telegram for macOS](https://github.com/overtake/telegram) project appID and appKey, if you meet the `API_ID_PUBLISHED_FLOOD` error, you may need to create your own application via  [Creating your Telegram Application](https://core.telegram.org/api/obtaining_api_id) and change the appID and Key in `config.h` header file.