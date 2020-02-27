# budget_tracker

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/53705501/75400779-3b52a280-58ce-11ea-8000-950a6016d149.gif)

Budget tracker is a PWA that allows you to track expenses and deposits to your budget with or without internet connection. This application was made with travelers that may not have access to internet connection at all times in mind. When traveling, having an easy way to track your expenses no matter what is a great option to have and makes traveling less stressful.

# How It Works

This application utilizes a service-worker to cache transactions when the user is offline and then retrieve them from the cache the next time the app is used with a connection. A manifest.json is used to provide metadata for the application so the browser knows how the PWA should behave when installed. 





