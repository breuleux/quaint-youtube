
# quaint-youtube

Embed YouTube videos in Quaint documents

## Install

In your Quaint project directory, run the command:

    quaint --setup youtube


## Sample usage

```quaint
youtube :: dQw4w9WgXcQ

youtube :: dQw4w9WgXcQ @ 300x300

@@youtube:dQw4w9WgXcQ
```


## Macro

The `youtube` macro is used with a video id and optionally a size
directive. The simplest command to display a video is this one:

```quaint
youtube :: dQw4w9WgXcQ
```

That will display the video at 640x390. If you want another size, you
can write it after an `@` sign, just like this:

```quaint
youtube :: dQw4w9WgXcQ @ 300x300
```

Alternatively to the `youtube` macro, you can use the following link
syntax: `@@youtube:video_id`. There is no difference between the two
syntaxes.


## Options

There are no options for this plugin.
