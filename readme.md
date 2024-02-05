# Sticker Smash

`Sticker Smash` is an application written during [Introduction to Expo](https://docs.expo.dev/tutorial/introduction/) tutorial, so nothing interesting really happens here. The project mainly contains private notes created while going through the tutorial.

## Libraries

There are a lot of libraries available in React Native ecosystem. [React Native Directory](https://reactnative.directory/) is a website that allows to search for libraries using advanced filters and sort results by relevance.

## Permissions

When creating an app that requires access to potentially sensitive information, such as access to the media library, we must first request the user's permission. Expo libraries (e.g. [expo-media-library](https://docs.expo.dev/versions/latest/sdk/media-library/)) follow a pattern in which they expose `usePermissions()` hook to manage permissions necessary for the library to work.
