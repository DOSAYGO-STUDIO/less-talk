# Less Talk

**[▶ Play it](https://dosaygo-studio.github.io/less-talk/)** (best with headphones)

An original big-beat homage in Web Audio, after "A Little Less Conversation" (Elvis Presley, JXL remix, 2002).

Two synthesized voices keep chattering in speech bubbles. A band keeps arriving: kick, snare and hats, a wah guitar, a Hammond-ish organ, a bass, a brass section. Each section gives the talkers less room, through a build, a held breath and a drop, until the brass shuts them down and does the arguing instead.

Nothing comes from the record: no words, no melody, no riff. The harmony (a D dorian vamp with a bluesy turnaround) and the horn lines are original. What it borrows is the attitude, written as a program.

## How it's made

- **One HTML file**, no libraries, no build. Open `index.html` and press Play.
- **Everything is synthesized** with the Web Audio API: oscillators, noise, filters and envelopes, with a convolution reverb, a dotted-eighth delay and a soft-clip master bus.
- **The talkers** are formant voices: a buzzing source pushed through three moving bandpass filters, narrowed to a telephone band.
- **The score reads like a score:** drum patterns are 16-step strings, the horn lines are note lists, and the arrangement is a table of sections that sets how much talk and how much action each one gets.
- **The picture** follows the sound: the master waveform, rings on the kick, brass blasts by pitch, and speech bubbles that pop when the drop lands.

## More from DOSAYGO STUDIO

- [HackerBook](https://hackerbook.dosaygo.com): Hacker News, offline, in your browser
- [rain](https://dosaygo-studio.github.io/rain/): a fast hash function in under 140 lines
- [prime-news](https://dosaygo-studio.github.io/prime-news/): HN, but only the prime-numbered items
- [HN front page 2035](https://dosaygo-studio.github.io/hn-front-page-2035/): the front page, reimagined
- [How Much Did It Cost?](https://dosaygo-studio.github.io/HMDIC/): an AI build estimator for GitHub repos
- [BrowserBox](https://browserbox.io/): remote browser isolation

## License

MIT. See [LICENSE](LICENSE).
