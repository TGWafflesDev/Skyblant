# Skyblant

[![Build Status](https://ci.thom.club/job/TheExoticsMod/job/master/badge/icon)](https://ci.thom.club/job/TheExoticsMod/job/master/) [![Discord](https://img.shields.io/discord/932106421338779709?label=discord&logo=Discord&logoColor=FFFFFF%22)](https://discord.gg/JeF5rW7yJU) [![Contributors](https://img.shields.io/github/contributors/TGWaffles/TheExoticsMod?&logo=GitHub)](https://github.com/TGWaffles/TheExoticsMod/graphs/contributors) [![Jenkins Coverage](https://img.shields.io/jenkins/coverage/jacoco?jobUrl=https%3A%2F%2Fci.thom.club%2Fjob%2FTheExoticsMod%2Fjob%2Fmaster)](https://ci.thom.club/job/TheExoticsMod/job/master/jacoco/) [![Jenkins tests](https://img.shields.io/jenkins/tests?compact_message&jobUrl=https%3A%2F%2Fci.thom.club%2Fjob%2FTheExoticsMod%2Fjob%2Fmaster)](https://ci.thom.club/job/TheExoticsMod/job/master/lastBuild/testReport/)

---

An open-source, free, scanner for exotic armour in Hypixel Skyblock! 

Searches friendslists, the auction house, and inventories to find exotic, crystal and fairy armour, which is then uploaded to a database for searching.

Includes an AH sniper to snipe any exotics/crystal/fairy armour listed on the AH.

[Join the Discord!](https://discord.gg/bUE3r3Jckc)

---

Brought to you by the creator of TFM, the fastest AH sniper. 

[Join TFM's Discord](https://discord.gg/tfmmod)


---
## How to build?

### Protoc Files

`protoc -I . --java_out annotate_code:src/main/java/ clientMessages.proto`

`protoc -I . --java_out annotate_code:src/main/java/ serverMessages.proto`
