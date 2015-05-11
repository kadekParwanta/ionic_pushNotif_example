## Note
It doesn't work on simulator, please use a real device for testing.


## Instructions
[Download][zip] or clone the master branch and run the following command:

```bash
npm install -g ionic@1.4.0-alpha.6
cd ionic_pushNotif_example
ionic push --google-api-key your-google-api-key
ionic platform add android
ionic build android
ionic run android
```

## Testings
via web: [Push Tools][push_tools]

via CLI:
```bash
ionic push --send
```


![Screenshot #1](/../screenshots/screenshots/ionic_pushNotif1.png?raw=true)

## License

This software is released under the [Apache 2.0 License][apache2_license].

© 2013-2015 appPlant UG, Inc. All rights reserved

## References
[ionic documentation][sourcea]


[sourcea]: http://docs.ionic.io/v1.0/docs/push-quick-start
[zip]: https://github.com/kadekParwanta/ionic_pushNotif_example/archive/master.zip
[apache2_license]: http://opensource.org/licenses/Apache-2.0
[push_tools]: https://apps.ionic.io/app/2862350e/push/tools