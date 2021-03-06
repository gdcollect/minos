# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.6.0] - 2018-12-16
### Fixes and Improvements
- Replace command line argument `--source` with `--dataset` and `--task` with `env_config`
- Added flag termination_on_success for meas_fun ([@ducha-aiki](https://github.com/ducha-aiki))
- Handle maps from mp3d scenes with multiple levels ([@ZhuFengdaaa](https://github.com/ZhuFengdaaa) [#125](../../issues/125))
- Fixes `visualize_traces.js` for mp3d scenes ([#129](../../issues/129))

## [0.5.3] - 2018-04-25
### Fixes
- Improved downloading and packing of asset metadata (sstk dependency v0.5.3)
- Re-enable passing back of info member in returned dictionary of step function (sstk dependency v0.5.3)
- Fix over-eager cache clearing logic leading to occasional crashes (sstk dependency v0.5.3)

## [0.5.2] - 2018-03-25
### Fixes
- Adjust depth buffer unpacking to return zero pixel value when no depth

## [0.5.1] - 2018-03-16
### Fixes
- Robustify room sampling routine (sstk dependency v0.5.1)
- Fix depth RGBA unpacking (sstk dependency v0.5.1)

### Features
- OpenAI gym wrapper allows access to underlying Simulator
- Independent setting of position, heading angle, tilt angle through `move_to` command

## [0.5.0] - 2017-12-11
### Initial beta release
