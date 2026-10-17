# Faraday

Faraday watches Disco `player.js` rotations, derives cipher configs (`sig`,
`nClass`, `sts`, `aliases`), validates them against real CDN streams, and
updates the registry automatically.

## Used by

- Disco KMP (WIP)
- Disco
- InnerDiscoX and all projects using it

## Acknowledgments

- [zemer-cipher](https://github.com/ZemerTeam/zemer-cipher) - config schema and
  parser rules
- [zemer-app](https://github.com/ZemerTeam/zemer-app) - deriver and HTTP 206
  validator patterns
