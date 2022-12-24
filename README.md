
# Movies

Movies is a simple project to study and play with some android components, architecture and tools for Android development.

## Tech Stack

This project uses [feature modularization architecture](https://proandroiddev.com/intro-to-app-modularization-42411e4c421e).
The movies feature module uses MVI as software design patter for presentation layer, and the actors feature module uses MVVM.

## Medium blogs

I write about the process of coding this project in the following blogs:
 - [Understanding MVVM](https://christopher-elias.medium.com/understanding-mvvm-pattern-for-android-in-2021-98b155b37b54)
 - Understanding and making [unit](https://christopher-elias.medium.com/understanding-unit-tests-for-android-in-2021-71984f370240) & [instrumented](https://christopher-elias.medium.com/easy-instrumented-tests-ui-tests-for-android-in-2021-2e28134ff309) tests.
 - [The ABC of modularization](https://proandroiddev.com/the-abc-of-modularization-for-android-in-2021-e7b3fbe29fca)
 - Create a safe retrofit calls extension part [I](https://christopher-elias.medium.com/safe-retrofit-calls-extension-with-kotlin-coroutines-for-android-in-2021-part-i-d47e9e2962ad), [II](https://christopher-elias.medium.com/safe-retrofit-calls-extension-with-kotlin-coroutines-for-android-in-2021-part-ii-fd55842951cf), & [III](https://christopher-elias.medium.com/safe-retrofit-calls-extension-with-kotlin-coroutines-for-android-in-2021-part-iii-583249b0e86b)
 - [Honest thoughts on Jetpack Navigation library in modularized projects](https://christopher-elias.medium.com/honest-thoughts-on-jetpack-navigation-library-in-modularized-projects-782094660c3)
 - [Integrating Paging3](https://christopher-elias.medium.com/pagination-in-android-with-paging-3-retrofit-and-kotlin-flow-2c2454ff776e)

### Libraries

- Application entirely written in [Kotlin](https://kotlinlang.org)
- Asynchronous processing using [Coroutines](https://kotlin.github.io/kotlinx.coroutines/)
- Uses [Koin](https://github.com/InsertKoinIO/koin) for dependency injection
- Uses [Github Actions](https://docs.github.com/en/actions/learn-github-actions)
- Uses [Paging3](https://developer.android.com/topic/libraries/architecture/paging/v3-overview)
- Uses [JUnit4](https://developer.android.com/training/testing/junit-rules),
- [Espresso](https://developer.android.com/training/testing/espresso), 
- [Fragment Tests](https://developer.android.com/guide/fragments/test) 
- among other libraries for unit & instrumented tests.

### API keys

You need to supply API / client keys for the service the app uses.

- [TMDb](https://developers.themoviedb.org)

Once you obtain the key, you can set them in your `~/local.properties`:

```
# Get this from TMDb
tmdb.key=<insert>
```

# Movie movie
Dec 23: modulization group copy

#Refs
[refs](https://github.com/ChristopherME/movies-android)
[refs](https://proandroiddev.com/the-abc-of-modularization-for-android-in-2021-e7b3fbe29fca)

# Donate
[![N|Solid](https://raw.githubusercontent.com/hvngoc/soulan/master/buymeacoffee.png)](https://www.buymeacoffee.com/ngocjaus)
