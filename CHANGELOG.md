# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.3.6] - 2016-11-21
### Fixed
- answers with parenthesis are detected and match accordingly

## [0.3.5] - 2016-11-21
### Fixed
- formatting currency properly in scoreboard

## [0.3.4] - 2016-11-21
### We're just not going to talk about this one

## [0.3.3] - 2016-11-20
### Fixed
- syntax error

## [0.3.2] - 2016-11-20
### Fixed
- fixed quoting in usage

## [0.3.1] - 2016-11-20
### Fixed
- issue with leaderboard and requesting nick

## [0.3.0] - 2016-11-20
### Added
- top 3 players in last week, and requesting user's score

## [0.2.4] - 2016-11-20
### Changed
- track timestamp of answer, for date range-based leaderboards

## [0.2.3] - 2016-11-20
### Changed
- track who answers question correctly

## [0.2.2] - 2016-11-20
### Changed
- remove stopwords from answer tokens before evaling

## [0.2.1] - 2016-11-13
### Added
- ratio threshold to answer evaluation
- debug logging

## [0.2.0] - 2016-10-27
### Added
- adding hooks so other plugins can run jeopardy type games

### Fixed
- unicode tokens now parse correctly


## [0.1.3] - 2016-10-25
useless version bump


## [0.1.2] - 2016-10-23
### Added
- tracks active questions per channel
- allow multiple correct responses
- improve matching, introduce partial response ('can you be more specific?')

## [0.1.1] - 2016-10-23
- attempts to determine if a person answered correct


## [0.1.0] - 2016-10-16
### Added
- can query random questions from api, reveals answer 1 min (by default) later
