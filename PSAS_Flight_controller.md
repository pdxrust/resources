# Portland State University Capstone
PSAS flight controller

written in Rust!

# What is a capstone?

# A capstone is...

# ... a group project

# ... with a sponsor from outside the class

# ... who wants something awesome made

# Who are PSAS?
http://psas.pdx.edu/

# PSAS is ...

# ... a team of students that make rockets

# ... for very low cost

# ... and has open source software

# ... as well as open source hardware

# ... that want to put a satellite into orbit

# PSAS has a challenge

# Fly in space!
(This means no wings or fins)

# This is a big project
So they decided on a new flight controller

# New flight controller needs...

# ... to use cold gas jets

# ... to be testable

# ... to be fast

# ... to be safe

# Decision
Test using using JSBSim

Fast and Safe: Rust!

Read and write pins: i2c and gpio

# These tools are complicated
And we were not experienced

So we did lots of research

# We built a MVP with
2 compile modes (flight and test)

integration with i2c and gpio

integration with JSBSim

# To test it
Flight: LED prototype

Test: Read JSBSim output

# Code breakdown
  common
    control.rs
    data_fmt.rs
    main.rs
    sensor.rs
  flight_mode
    src
    gpio.rs
    i2c.rs
    lib.rs
  test_mode
    src
    gpio.rs
    i2c.rs
    lib.rs

# Interesting statistics

# 651 lines of Rust code
does not include whitespace or comments

overall over 1k lines

# 43 lines of CPP
For JSBSim integration

(my slide software did not like the plus sign)

# 668 Lines of markdown documentation
Documents that Capstone class required

# Interesting problems!

# JSBSim is hard...
and undocumented

and kind of has spaghetti code

and written in CPP

# Different compile modes
what do?

different ways to solve this

our way works, but is it the best?

# Interesting Bugs!
Counter-Clockwise bias (first video in playlist) (second video has bug fixed)

Dual spin bug (third video in playlist)

link: https://www.youtube.com/playlist?list=PL8UKBDaWZPifD2Dj1vvfJeWF5F92Efrez

# Watch it work!
(last video in playlist)

https://www.youtube.com/playlist?list=PL8UKBDaWZPifD2Dj1vvfJeWF5F92Efrez

# Code time!
https://github.com/hgb2/PSAS-Capstone

# Questions?
https://www.youtube.com/user/PSASRockets/videos
