![Project Status: Active][Project Status Image]

Code Auto Update
===========================

The script doesn't update itself so there is no backdoor possible

# Usage

* Download script, set exec permission and activate it
``` 
wget https://raw.githubusercontent.com/usbkey9/autoup/master/autoup && chmod +x autoup && touch autoup.on
```

* Call it from all your callable bash script (preferably in the early)

```
./autoup $0 $@
```

* If you want to disable it

```
rm autoup.on
```


There is a good example in [https://github.com/usbkey9/uktools/](https://github.com/usbkey9/uktools/blob/master/setup#L23) 

## TODO (Tests)

* It doesn't support subrepo/submodule for now (external help is welcome)
* Any other contributions is welcome


[Project Status Image]: https://img.shields.io/badge/project-active-green.svg "Project Status: Active"
