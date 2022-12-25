# youtube-playback-speed
Sometimes I need to increase playback speed of a video more than 2x, but I always forget the console command

Open your Web Inspector/Developer Console.
Go to Console.
Paste it next to the ">"

x - is your speed multiplicator
`$('video').playbackRate=x`

Increase speed by 3:
`$('video').playbackRate=3`

Increase speed by 4:
`$('video').playbackRate=4`
