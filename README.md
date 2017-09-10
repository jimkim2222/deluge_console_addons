# deluge_console_addons

Add convenient bash functions for [deluge-console](http://deluge-torrent.org). Source it
into your ```.bashrc```.

```. deluge_console_addons```

## Required Packages
```
sudo apt-get install deluge-console deluged
```

## List of Functions 
### deluge_start
Start server on localhost. Similar to running as GUI in classic mode.

```deluge_start &```

### deluge_stop 
Stop server on localhost. 

```deluge_stop```

### deluge_add 

```deluge_add <magnet-link|http-link|torrent-file-path>``` 

### deluge_add_file 
Add links from text file

```deluge_add_file file.txt``` 

### deluge_dl_dir 
Set/Get download location

```
deluge_dl_dir /some_dir
deluge_dl_dir
```

### deluge_dl_speed
Set/Get max download speed

```
deluge_dl_speed 200
deluge_dl_speed
```

### deluge_upld_speed
Set/Get max upload speed

```
deluge_upld_speed 50
deluge_upld_speed
```

### deluge_fix_error
Force recheck on files with errors.

```deluge_fix_error```
 
### deluge_id
Get ID, supports grep(1) regex. 

```deluge_id name```

### deluge_num_dl
Get/Set Active downloads

```
deluge_num_dl 10
deluge_num_dl
```

### deluge_pause
Pause downloads

```
deluge_pause name
deluge_pause *
```

### deluge_resume
Resume downloads

```
deluge_resume name
deluge_resume *
```

### deluge_progress
View progress of all downloads

```deluge_progress```

### deluge_search
Get download info

```deluge_search name```

### deluge_watch
Update the status of selected download(s). Use **Ctrl-C** to kill. 

```deluge_watch name```

### deluge_rm
Remove download(s) but doesn't delete data.

```deluge_rm name```

### deluge_rm_data
Remove download(s), completely.

```deluge_rm_data name```

### deluge_rm_seeding
Remove all seeding download(s), without deleting their data.

```deluge_rm_seeding```






