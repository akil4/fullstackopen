```mermaid
    sequenceDiagram
        participant browser
        participant server
        
        browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
        activate server
        server-->>browser: HTML Document
        deactivate server
        
        browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
        activate server
        server-->>browser: CSS File
        deactivate server
        
        browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa.js
        activate server
        server-->>browser: The spa.js file
        deactivate server
        
        Note right of browser: Browser executes JS Code
        
        browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
        activate server
        server-->>browser: [
    {
        "content": "",
        "date": "2025-01-11T07:03:59.630Z"
    },
    {
        "content": "HEllo there \\",
        "date": "2025-01-11T07:09:55.962Z"
    },
    {
        "content": "",
        "date": "2025-01-11T07:12:08.768Z"
    },
    {
        "content": "testing",
        "date": "2025-01-11T07:13:50.845Z"
    },
    {
        "content": "",
        "date": "2025-01-11T07:15:33.704Z"
    },
    {
        "content": "form data is sent with HTTP POST",
        "date": "2025-01-11T07:17:28.930Z"
    },
    {
        "content": "hi",
        "date": "2025-01-11T07:17:38.104Z"
    },
    {
        "content": "form",
        "date": "2025-01-11T07:20:53.185Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T07:24:37.362Z"
    },
    {
        "content": "hihi",
        "date": "2025-01-11T07:25:29.334Z"
    },
    {
        "content": "spa form",
        "date": "2025-01-11T07:25:32.498Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T07:25:42.947Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T07:26:20.943Z"
    },
    {
        "content": "hi",
        "date": "2025-01-11T07:28:07.151Z"
    },
    {
        "content": "testing123",
        "date": "2025-01-11T07:28:12.442Z"
    },
    {
        "content": "G'day, from Australia",
        "date": "2025-01-11T07:29:42.367Z"
    },
    {
        "content": "",
        "date": "2025-01-11T07:29:45.897Z"
    },
    {
        "content": "another one",
        "date": "2025-01-11T07:29:50.429Z"
    },
    {
        "content": "",
        "date": "2025-01-11T07:32:07.542Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T07:39:55.713Z"
    },
    {
        "content": "hi",
        "date": "2025-01-11T07:43:59.004Z"
    },
    {
        "content": "My added note",
        "date": "2025-01-11T07:50:57.131Z"
    },
    {
        "content": "new note",
        "date": "2025-01-11T08:09:29.767Z"
    },
    {
        "content": "yurrrr",
        "date": "2025-01-11T08:10:20.607Z"
    },
    {
        "content": "",
        "date": "2025-01-11T08:13:37.834Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T08:15:51.111Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T08:16:34.671Z"
    },
    {
        "content": "jeaaa",
        "date": "2025-01-11T08:22:16.334Z"
    },
    {
        "content": "Save this",
        "date": "2025-01-11T08:22:19.622Z"
    },
    {
        "content": "wadap",
        "date": "2025-01-11T08:22:50.126Z"
    },
    {
        "content": "testing",
        "date": "2025-01-11T08:23:23.172Z"
    },
    {
        "content": "JJ",
        "date": "2025-01-11T08:26:00.388Z"
    },
    {
        "content": "Hola",
        "date": "2025-01-11T08:26:21.175Z"
    },
    {
        "content": "ASD",
        "date": "2025-01-11T08:26:27.964Z"
    },
    {
        "content": "I like Mermaid",
        "date": "2025-01-11T08:39:32.047Z"
    },
    {
        "content": "Hello Michael",
        "date": "2025-01-11T08:59:42.428Z"
    },
    {
        "content": "yuu",
        "date": "2025-01-11T09:02:25.035Z"
    },
    {
        "content": "submit ",
        "date": "2025-01-11T09:04:19.480Z"
    },
    {
        "content": "XxX",
        "date": "2025-01-11T09:05:49.949Z"
    },
    {
        "content": "",
        "date": "2025-01-11T09:07:19.854Z"
    },
    {
        "content": "",
        "date": "2025-01-11T09:12:14.161Z"
    },
    {
        "content": "hisashiburi ne mugiwara",
        "date": "2025-01-11T09:21:22.885Z"
    },
    {
        "content": "hi",
        "date": "2025-01-11T09:30:46.106Z"
    },
    {
        "content": "['pp['",
        "date": "2025-01-11T09:31:11.995Z"
    },
    {
        "content": "asdd",
        "date": "2025-01-11T09:33:32.726Z"
    },
    {
        "content": "Good",
        "date": "2025-01-11T09:37:03.375Z"
    },
    {
        "content": "Hello Stacy",
        "date": "2025-01-11T09:38:18.701Z"
    },
    {
        "content": "Yo!!",
        "date": "2025-01-11T09:42:43.867Z"
    },
    {
        "content": "Starbies",
        "date": "2025-01-11T09:44:14.882Z"
    },
    {
        "content": "asd",
        "date": "2025-01-11T09:49:16.975Z"
    },
    {
        "content": "sdsd",
        "date": "2025-01-11T09:49:20.226Z"
    },
    {
        "content": "Hello There",
        "date": "2025-01-11T09:59:32.329Z"
    },
    {
        "content": "nice one",
        "date": "2025-01-11T10:01:19.909Z"
    },
    {
        "content": "jn",
        "date": "2025-01-11T10:05:20.912Z"
    },
    {
        "content": "hhh",
        "date": "2025-01-11T10:05:27.532Z"
    },
    {
        "content": "oho oho vittu",
        "date": "2025-01-11T10:18:37.284Z"
    },
    {
        "content": "",
        "date": "2025-01-11T10:19:33.590Z"
    },
    {
        "content": "you have no enemeies",
        "date": "2025-01-11T10:22:04.077Z"
    },
    {
        "content": "hello there",
        "date": "2025-01-11T10:23:02.505Z"
    },
    {
        "content": "g h're ya doin?",
        "date": "2025-01-11T10:23:07.170Z"
    },
    {
        "content": "testing",
        "date": "2025-01-11T10:24:55.215Z"
    },
    {
        "content": "fkvrzacqndoiqzgwqwgwfnbgzdqmmceeuasnkwpokakftxptunnvjqhyykvwzboyafpejkgjrwdpkouekwaagsqcqfmnvromhgefwpajwgogkmckythjxhitgldwtdamicanybybjhnbspeypjpxgqwtkgibsrueyojourgovacxoxzmejgxykyzuwpygchxcoikehsm",
        "date": "2025-01-11T10:25:42.334Z"
    },
    {
        "content": "hujywyrdnikfusebmqkjdfsjwrhjxcxocwrpldzdznnvzwgxlqnluhkpnlrhfxweznffwrxzmvtonddjodqmcrxwjwzbhiccrxruipmjpeawuumcviwyjcyhzieshgjaztdhljzciahlskzebhkwcbdjymvyeyfqamokkysndupxclbenlneyylfvpautgiiywcnufqo",
        "date": "2025-01-11T10:26:22.363Z"
    },
    {
        "content": "hello hello hello",
        "date": "2025-01-11T10:27:08.566Z"
    },
    {
        "content": "you have no enemeies",
        "date": "2025-01-11T10:30:42.817Z"
    },
    {
        "content": "",
        "date": "2025-01-11T10:32:30.616Z"
    },
    {
        "content": "",
        "date": "2025-01-11T10:40:19.129Z"
    },
    {
        "content": "fresh beans",
        "date": "2025-01-11T10:40:26.655Z"
    },
    {
        "content": "you have no enemeies",
        "date": "2025-01-11T10:41:15.782Z"
    },
    {
        "content": "you have no enemeies",
        "date": "2025-01-11T10:44:31.275Z"
    },
    {
        "content": "greeetssssinsssslalaal123456",
        "date": "2025-01-11T10:46:24.573Z"
    },
    {
        "content": "U r the love charger",
        "date": "2025-01-11T10:58:01.596Z"
    },
    {
        "content": "6541lalallalalassssseetrg",
        "date": "2025-01-11T10:58:56.406Z"
    },
    {
        "content": "654564",
        "date": "2025-01-11T11:07:54.191Z"
    },
    {
        "content": "hi",
        "date": "2025-01-11T11:13:31.206Z"
    },
    {
        "content": "hiii",
        "date": "2025-01-11T11:15:00.753Z"
    },
    {
        "content": "U r the love charger",
        "date": "2025-01-11T11:16:52.107Z"
    },
    {
        "content": "",
        "date": "2025-01-11T11:31:33.166Z"
    },
    {
        "content": "test ",
        "date": "2025-01-11T11:31:56.365Z"
    },
    {
        "content": "uudestaa",
        "date": "2025-01-11T11:34:10.500Z"
    },
    {
        "content": "Jaafur",
        "date": "2025-01-11T11:48:15.414Z"
    },
    {
        "content": "hiii",
        "date": "2025-01-11T11:48:36.586Z"
    },
    {
        "content": "hiii",
        "date": "2025-01-11T11:48:50.578Z"
    },
    {
        "content": "hello",
        "date": "2025-01-11T11:48:59.635Z"
    },
    {
        "content": "hiiii",
        "date": "2025-01-11T11:49:17.594Z"
    },
    {
        "content": "uudestaa part 2",
        "date": "2025-01-11T11:49:46.999Z"
    },
    {
        "content": "AUPA ZAGOOOOZA",
        "date": "2025-01-11T12:00:45.075Z"
    },
    {
        "content": "Jaafur1",
        "date": "2025-01-11T12:35:07.296Z"
    },
    {
        "content": "Jaafur1",
        "date": "2025-01-11T12:39:06.831Z"
    },
    {
        "content": "hola mundo",
        "date": "2025-01-11T12:45:50.483Z"
    },
    {
        "content": "Whats happening?!",
        "date": "2025-01-11T12:58:53.036Z"
    },
    {
        "content": "",
        "date": "2025-01-11T13:03:27.145Z"
    },
    {
        "content": "asdx",
        "date": "2025-01-11T13:09:07.747Z"
    },
    {
        "content": "asd",
        "date": "2025-01-11T13:24:43.322Z"
    },
    {
        "content": "ll",
        "date": "2025-01-11T13:41:28.617Z"
    },
    {
        "content": "jahuu",
        "date": "2025-01-11T14:14:12.461Z"
    },
    {
        "content": "yyyh",
        "date": "2025-01-11T14:14:43.962Z"
    },
    {
        "content": "o",
        "date": "2025-01-11T14:14:45.878Z"
    },
    {
        "content": "a",
        "date": "2025-01-11T14:15:07.101Z"
    },
    {
        "content": "Shiringo",
        "date": "2025-01-11T14:24:34.111Z"
    }
    ]
    deactivate server
    
    Note left of browser: Browser displays the notes
```
