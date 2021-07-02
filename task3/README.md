# Task 3

Instantly after listening the first audio I understood it was binary data I wrote it down.

```
00110100011101010110010000110001011011110101111101101001001101010101111101101110001100010110001100110011
```

There was one more possibilty

```
11001011100010101001101111001110100100001010000010010110110010101010000010010001110011101001110011001100
```

 Ok so we simply had to decode this. I tried things like Morse decoding , base64, ASCII , hex  on both these binary data but got a good result with ASCII only. I used [this](https://www.rapidtables.com/convert/number/binary-to-ascii.html) online converter to check it , first one was forming 4ud1o_i5_n1c3. I also made [this](https://github.com/geekyuttu/csec-convener-assignment/blob/main/task3/binary_to_ascii.py) code  just for sake.

So the flag was **audio_is_nice** (leetspeak)

I still didn't understand why the second audio had 102 (not divisible by 8) binary digits and hint given was ASCII :smirk: ​

