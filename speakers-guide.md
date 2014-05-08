Speakers' Guide for EmacsNYC
----------------------------

You're interested in speaking at EmacsNYC? Great! We'll just need you
to do a couple things to get ready...

### What we need

Please send `admin@emacsnyc.org` an email that includes:

- Your preferred name
- Job title and company, if applicable (only used in the video)
- Title of the talk
- Brief abstract for the talk (four or five sentences, probably)
- Link to your homepage or preferred website(s)
- A note giving us permission to record and distribute the video under
  the [CC BY-SA](http://creativecommons.org/licenses/by-sa/4.0/)
  license.

### Things to do before your talk

- Your laptop will need to support DisplayPort or HDMI. If it doesn't,
  please let us know ASAP!
- If you're on a Mac, please install a trial copy of
 [ScreenFlow](http://www.telestream.net/screenflow/overview.htm)
- If you're on some other Unix, please install `avconv` (or `ffmpeg`)
  and ensure that the following command records a screencast:

```shell
$ avconv -f x11grab -r 25 -s 1920x1080 -i :0 -vcodec libx264 -threads 0 video.mkv
```

- We're not sure how to record a good screencast (with audio) on
  Windows. If you're a Windows user, please come up with a solution
  that works (and let us know what it is, for future reference)!
- Ask for Harry's phone number for emergencies if he forgets to give
  it to you =)

### Reminders for during the talk

- Don't move around *too* much. The camera's watching, so please try
  to remain in its field of view.
- If you get audience questions, please repeat them into the mic.
