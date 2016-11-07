# Kitura-HelloWorld
Very simple server-side Swift application that can be run local on your macOS or Linux box or in Bluemix Cloud Foundry

## Build and run locally
Clone the repository
```
$ git clone https://github.com/IBM-Swift/kitura-helloworld.git
```

Build the app locally
```
$ cd kitura-helloworld
$ swift build
```

This should build an executable called .build/debug/kitura-helloworld

Run executable
```
$ .build/debug/kitura-helloworld
 VERBOSE: init() Router.swift line 55 - Router initialized
 VERBOSE: run() Kitura.swift line 71 - Starting Kitura framework...
 VERBOSE: run() Kitura.swift line 73 - Starting an HTTP Server on port 8090...
 INFO: listen(socket:port:) HTTPServer.swift line 136 - Listening on port 8090
```

## Deploy to Bluemix
Now if you also want to push this to Bluemix, follow the steps here (https://console.ng.bluemix.net/docs/starters/install_cli.html) to signup, download command line tool and push your app to the cloud.
