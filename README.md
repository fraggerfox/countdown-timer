Countdown Timer
====

A clone of TED Countdown Timer which can be used offline or hosted in your
private space.

This is a Countdown timer that is basically a re-implementation of the TED
Countdown Timer used for TED Conference. We intent to keep this also free to use
and replicate / modify as per your requirements.

You can try out Countdown Timer [here][countdown_url]

You can find the original TED Countdown Timer [here][ted_countdown_url]

### Motivation

When I was asked to find a suitable timer for a technical talk event with a
limit on the talk time alloted for the speaker, my search did not yeild any
useful results. Most of the solutions I came across was either too bloated,
platform specific like for Windows or Linux, needed connectivity online like in
TED Countdown.

After without much success, I decided to replicate the TED Countdown Timer which
was very minimalistic and met most of the requirements. However it lacked the ability
to host talks above 20 minutes (which is the hard limit on most TED talks) and it
still needed to load from a web page which needed connectivity.

The aim of this little project is to have an offline solution which can be hosted
in a system which has no internet connectivity and have the ability to host talks
which are more than 20 minutes in length.

I personally felt that having an interface that most users are familiar with will
also be helpful, hence the choice for TED's Countdown Timer.

### Changes from original

* Timer is no longer restricted to 20 Minutes maximum, has been extended to 60
  Minutes.

* The interval increments are 5 Minutes, instead of 1 minute, this was done to
  avoid the rather long drop down list.

* Removed the Google Analytics and related scripts.

* "Un-minified" the CSS file.

* The files have been neatly organized into the proper folders.

## Get it

The Countdown Timer is free to use, and can be accessed through any Web browser.
Using Chrome’s Presentation Mode allows you to focus only on the timer. If you
want to use the Timer like an app on your mobile device, tap on the share icon
(iOS) or menu button (Android) and select “Add to Home Screen.”

You will need to put the files in a Web Server (like Apache for example) or
download these files to your computer, and then access the `index.html` via
browser. This will load the Countdown Timer UI.

## Use it

To start the Timer, select the duration of your talk (choose any length from 2
to 60 minutes). Next hit "Start now" to begin the countdown immediately, or
"Start in 10 seconds" to give yourself time to get ready.

For a less distracting countdown, the Timer initially displays minutes only —
for example, a 15-minute talk will flash “15” to start, then display “14” for
the next 60 seconds, then “13,” and so on.  The dots along the bottom show your
progress through each minute (each dot represents six seconds).

The Timer will switch to a second-by-second countdown at 90 seconds. If you go
over your chosen time, the Timer screen will turn red, flash "OVER TIME," and
begin counting up.

To pause the Timer, use the button in the lower right corner; if you're on a
laptop or desktop machine, move your mouse to make the pause button appear.

If you spot a bug or just need help, feel free to raise a ticket and we shall
respond as fast as possible.

## Credits

Thanks to @gwhammett for hosting Countdown Timer.

## License

Countdown Timer is licensed under the [Apache license, Version 2.0 ](LICENSE)

[ted_countdown_url]: http://countdown.ted.com/
[countdown_url]: http://www.princeton.edu/~hammett/TED-like_talk_timer/
