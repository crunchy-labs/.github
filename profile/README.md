<h1 align="center">Crunchy Labs</h1>

<p align="center">
  <br>
    <a href="https://github.com/crunchy-labs">
        <img src="https://github.com/crunchy-labs/.github/raw/main/assets/crunchy-labs.png" alt="Logo" width=250px>
    </a>
  <br>
</p>

<p align="center">An enhanced Crunchyroll experience 🎬 📥 🍣</p>

<p align="center">
  <a href="https://discord.gg/PXGPGpQxgk">
    <img src="https://img.shields.io/discord/994882878125121596?label=&logo=discord&logoColor=ffffff&color=7289DA&labelColor=7289DA&style=for-the-badge" alt="Discord">
  </a>
</p>

<br>

> We are in no way affiliated with, maintained, authorized, sponsored, or officially associated with Crunchyroll LLC or any of its subsidiaries or affiliates.
> The official Crunchyroll website can be found at https://crunchyroll.com/.


## Projects

### crunchy-cli

<a href="https://github.com/crunchy-labs/crunchy-cli">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=crunchy-labs&repo=crunchy-cli" alt="crunchy-cli" align="right">
</a>

_**[crunchy-cli](https://github.com/crunchy-labs/crunchy-cli)**_ is a command line client to download episodes or entire series from crunchyroll.
It has also the ability to download videos into a `.mkv` file with multiple subtitle and audio tracks as well as compress them to zip / gzip or tar file.

<br>

### crunchyroll-rs

<a href="https://github.com/crunchy-labs/crunchyroll-rs">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=crunchy-labs&repo=crunchyroll-rs" alt="crunchyroll-rs" align="left">
</a>

_**[crunchyroll-rs](https://github.com/crunchy-labs/crunchyroll-rs)**_ is a pure [Rust](https://www.rust-lang.org/) implementation of the Crunchyroll (beta) api.
It is the successor of [crunchyroll-go](#crunchyroll-go).
Unlike its predecessor, it has tests which can be used to detect api changes immediately when running.
Nearly 100% of the Crunchyroll api are covered by it (this number may vary in cases where Crunchyroll adds new endpoints) so you can almost do all the stuff from the Crunchyroll website via this library.

<br>

### crunchyroll-go

<a href="https://github.com/crunchy-labs/crunchyroll-go">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=crunchy-labs&repo=crunchyroll-go" alt="crunchyroll-go" align="right">
</a>

_**[crunchyroll-go](https://github.com/crunchy-labs/crunchyroll-go)**_ is a [Go](https://go.dev/) implementation of the Crunchyroll (beta) api.
[crunchy-cli](#crunchy-cli) is based of this library.
It currently has _90% - 95%_ of api coverage and is succeeded by the [Rust implementation](#crunchyroll-rs).
Because it has no real use case anymore, it is in maintenance mode (it might be the home of Go bindings for the Rust library in the future)

<br>
