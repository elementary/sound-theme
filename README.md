# Sound Theme

A set of system sounds for elementary OS. Designed to be light, natural/physical, and pleasant.

## Attribution

`dialog-warning.ogg` is licensed under Creative Commons Attribution and was sourced from [Notification Sounds](https://notificationsounds.com/standard-ringtones/answer-quickly-45)

Pixabay sounds are free to use, modify, and redistribute subject to the Pixabay license <https://pixabay.com/service/license-summary/>:

`phone-hangup.mp3` <https://pixabay.com/sound-effects/ringtone-06-153265/>
`phone-incoming-call.mp3` <https://pixabay.com/sound-effects/ringtone-010-151670/>

## Installation

Run `meson` to configure the build environment and then `ninja install` to install

    meson build --prefix=/usr
    cd build
    sudo ninja install
