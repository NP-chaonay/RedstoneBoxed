# RedstoneBoxed
A new Minecraft Java (atm.) Mod/Plugin loader, made with security in mind by concepts of isolation and sandboxing, etc.

**Plan?: writiing mod in at least JS/Java and compile them into WASM or or-alike-goal to run in our runtime ; MORE EFFICIENT AND SAFER ; would start support from MC 1.17+ due to Java's Panama support; The WASM would run on Rust-written runtime and communicate to the mc server via Panama of Java; for older MC would using hybrid approch where most mod/plugin (frequent call of MC API) would run by Java code, and some mod/plugin (such as Deep Learning) would run in Rust communicating the mc server via JNI; mod can switching place to run, it just abort performance **

Interesting this project? I have not much time, so we need more people who have same interesting, and we disccuss, and try something for a hobby , and hope it contribute our MC community 

Q: How about bedrock?
A: If using EndStone, it is already fast just lack of sandbox (which may not important to be main sell point, since it already fast), but depend on what playform you using, however for sandbox, it maybe next our goal, or you can make your new repo for that!

PS: We plan to inspired by Forge or idk and yeah our LICENSE must compatible to that too; but some plan can changed idk
