# electron-base

## Reference
- [http://electron.atom.io/](http://electron.atom.io/)
- [https://github.com/atom/electron/blob/master/docs/tutorial/quick-start.md](https://github.com/atom/electron/blob/master/docs/tutorial/quick-start.md)

## Run your app

After you're done writing your app, you can create a distribution by
following the [Application distribution](https://github.com/atom/electron/blob/master/docs/tutorial/application-distribution.md) guide
and then execute the packaged app. You can also just use the downloaded
Electron binary to execute your app directly.

On Windows:

```cmd
$ .\electron\electron.exe your-app\
```

On Linux:

```bash
$ ./electron/electron your-app/
```

On OS X:

```bash
$ ./Electron.app/Contents/MacOS/Electron your-app/
```

`Electron.app` here is part of the Electron's release package, you can download
it from [here](https://github.com/atom/electron/releases).
