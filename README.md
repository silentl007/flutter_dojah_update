<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 

publish commands
flutter pub publish --dry-run
flutter pub publish

-->

```dart



 final DojahKYCWidget _dojahKYC = DojahKYC(
    appId: 'xxxxxxxxxxxxxxx', //required
    publicKey: 'prod_pk_xxxxxxxxxxxxxx', //required
    type : 'custom' 
    userData,    //object
    metaData,    //object (optional)
    govData,    //object (optional)
    config,  //object (optional)
    referenceId,  //NB: referenceId length must be more that 10 characters 
  );

  _dojahKYC.open(context, onSuccess: (result) {
    print('$result');
  }, onError: (err) {
    print('error: $err');
  });
```

## Additional information
