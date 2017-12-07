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
  the [CC BY-SA] license.

### Things to do before your talk

- Your laptop will need to support DisplayPort or HDMI. If it doesn't,
  please let us know ASAP!
- If you're on a Mac, please install a trial copy of [ScreenFlow]
- If you're on Linux, please install [recordMyDesktop]. Please make
  sure that you are able to record both your desktop and your mic
  audio.
- If you're on some other Unix, please install `avconv` (or `ffmpeg`)
  and ensure that the following command records a
  screencast. Substitute `ffmpeg` for `avconv` if necessary, and note
  that this command assumes you're using pulse audio. You may also
  need to change the resolution if you're not on 1600x900, but please
  try to ensure that final output video is widescreen (16x9).

```shell
$ avconv -f x11grab -r 25 -s 1600x900 -i :0 -vcodec libx264 -f alsa -ac 2 -i pulse -threads 0 video.mkv
```

- We're not sure how to record a good screencast (with audio) on
  Windows. If you're a Windows user, please come up with a solution
  that works (and let us know what it is, for future reference)!
- If you're on a Mac and you'd like to display your keystrokes on
  screen as you type, consider installing [Keycastr]. It's
  BSD-licensed!
- Ask for Eric's phone number for emergencies if he forgets to give it
  to you =)

### Reminders for during the talk

- Don't move around *too* much. The camera's watching, so please try
  to remain in its field of view.
- If you get audience questions, please repeat them into the mic.

[CC BY-SA]: http://creativecommons.org/licenses/by-sa/4.0/
[ScreenFlow]: http://www.telestream.net/screenflow/overview.htm
[recordMyDesktop]: http://recordmydesktop.sourceforge.net
[Keycastr]: https://github.com/keycastr/keycastr
