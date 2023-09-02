# Shell Wrapper - ease standalone software download, setup & execution 
There are plenty of opensource software available in the web. 
Some are standalone, great in utility, but setup and execution requires package managers
Lets cut this simple, often times you need to just execute the command once for setup, 
and doesn't require to maintain it. 
Often time
* You download the command to a location
* Make it executable [for linux/darwin/unix]
* Execute it once then forget it

I wish there wouldn't have been any dependency that would have required
but you need at least this following:
* curl [to download files ¯\\_(ツ)_/¯ ]

Now you can either install or directly use in-line by prefixing your command

## Installing
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/rbute/shw/HEAD/shwi)"
```

## In-line with command
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/rbute/shw/HEAD/shw)"
```

__In case you want to communicate, please raise an issue in github. Further development would happen only if benefits at least one person.__