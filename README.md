index
=====
    $ curl -u andrew.lunny@nitobi.com https://build.phonegap.com/api/v1/apps
    {
        "apps":[
            {
                "title":"My Index",
                "id":1,
                "package":"com.my.index",
                "version":"0.0.1",
                "repo":null,
                "description":"An Index of My Applications",
                "debug":false,
                "private":true,
                "link":"/api/v1/apps/1",
                "build_count":4,
                "phonegap_version":"2.9.0",
                "hydrates":false,
                "status":{
                    "android":"complete",
                    "blackberry":"error",
                    "ios":null,
                    "symbian":"complete",
                    "webos":"pending",
                    "winphone":"pending"
                },
                "download":{
                    "android":"/api/v1/apps/1/android",
                    "symbian":"/api/v1/apps/1/symbian"
                },
                "error":{
                    "blackberry":"invalid widget archive"
                },
                "icon":{
                    "filename":"icon.png",
                    "link":"/api/v1/apps/1/icon"
                },
                "role":"admin"
            },
            {
                "title":"PhoneGap: Getting Started",
                "id":2,
                "package":"com.phonegap.getting.started",
                "version":"1.0.0",
                "repo":"https://github.com/phonegap/phonegap-start.git",
                "description":"A template for getting started with
                        PhoneGap development and build.phonegap.com",
                "debug":false,
                "private":true,
                "link":"/api/v1/apps/2",
                "build_count":12,
                "status": {
                    "android":"complete",
                    "blackberry":"complete",
                    "ios":"complete",
                    "symbian":"complete",
                    "webos":"complete",
                    "winphone":"complete"
                },
                "download":{
                    "android":"/api/v1/apps/1/android",
                    "blackberry":"/api/v1/apps/1/blackberry",
                    "ios":"/api/v1/apps/1/ios",
                    "symbian":"/api/v1/apps/1/symbian",
                    "webos":"/api/v1/apps/1/webos",
                    "winphone":"/api/v1/apps/1/winphone"
                },
                "error":{},
                "icon":{
                    "filename":"big-icon.png",
                    "link":"/api/v1/apps/2/icon"
                },
                "role":"admin"
            }
        ],
        "link":"/api/v1/apps"
    }
