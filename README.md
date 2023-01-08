## 8th January 2022

Start repository.

**Low-pass filter**

![A low-pass filter](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/RC_Divider.svg/300px-RC_Divider.svg.png)

AudioPhool's [Circuits 101](https://www.youtube.com/watch?v=qRBIpVlccRQ]) on youtube explains that a low-pass filter makes use of the fact that the impedance of a capacitor varies with frequency. In fact, the 3dB cut-off frequency of a LPF is 1 / (2 * pi * R * C). So, with a variable resistor, you can make a variable low-pass filter. The [wikipedia](https://en.wikipedia.org/wiki/Low-pass_filter) article is useful for more detail.

In the video [Simple RC filter](https://www.youtube.com/watch?v=qotDMR9RKgI&t=30s), AudioPhool demonstrates building a LPF with  a .1uF capacitor ( 0.1 x 10^-6 F ), a 1.5k resistor (later a pot.), gives us 1000 Hz LPF . Talks briefly through output and input impedence, and shows the use of an op amp to buffer the filter circuit. He also mentions, briefly, that a **high-pass filter** can be built by reversing the two components.

![A high-pass filter](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/High_pass_filter.svg/210px-High_pass_filter.svg.png)


