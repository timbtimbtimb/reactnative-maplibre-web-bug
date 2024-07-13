https://github.com/maplibre/maplibre-react-native/issues/414

```
git clone git@github.com:timbtimbtimb/reactnative-maplibre-web-bug.git
cd reactnative-maplibre-web-bug
npm install --includeDev
npm run web
```

You should be getting the following error
```
Metro error: (0 , _index.requireNativeComponent) is not a function

  619 | );
  620 |
> 621 | const RCTMLNCamera = requireNativeComponent<NativeProps>(NATIVE_MODULE_NAME);
      |                                            ^
  622 |
  623 | export default Camera;
  624 |
```
