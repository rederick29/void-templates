# void-templates
#### Repo of custom package templates I use in Void Linux

mesa: template for building drivers needed for a Radeon 580 (+ swrast & zink) and nothing else.

rust-bindgen: template for building binary of [rust-bindgen](https://github.com/rust-lang/rust-bindgen)

dotnet-core-bin: downloads and installs a prebuilt [.NET core SDK from microsoft](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) (installs to /opt) (only tested on x86_64 glibc)

osu: builds [osu!lazer](https://github.com/ppy/osu) from source using the aforementioned dotnet-core-bin. It does not create a .desktop entry. (only tested on x86_64 glibc)

handlr: template for [handlr](https://github.com/chmln/handlr) and a wrapper to act as replacement for xdg-open
