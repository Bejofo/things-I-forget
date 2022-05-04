# things-I-forget


## Create wav out of midi

```
fluidsynth -F ./output.wav ./input.midi
```

If you want a custom soundfont

``` 
fluidsynth -F ./output.wav ./input.midi ./soundfont.sf2
```

## Convert between audio formats

```
ffmpeg -i input.mp3 output.ogg
```

## Scp syntax
Uploading
``` 
scp file.txt remote_username@10.10.0.2:/remote/directory
scp file.txt remote_username@10.10.0.2:/remote/directory/newfilename.txt
```

Downloading

```
scp remote_username@10.10.0.2:/remote/file.txt /local/directory
```


Moving between two remote system

```
scp remote_username@10.10.0.2:/remote/file.txt /local/directory
```

For directories just add `-r`

```
scp -r /local/directory remote_username@10.10.0.2:/remote/directory
```

Reminder to use `\` instead of `/` when dealing with windows systems.

## Curling
```
curl http://some.url --output some.file
```


