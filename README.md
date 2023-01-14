


# Grand Raptors Hub
The culminating release by The Raptors!
<p align="center">
<img width = "800" src="https://cdn.discordapp.com/attachments/692609523445399559/1062670089343750214/image.png">
<img width = "800" src="https://cdn.discordapp.com/attachments/692609523445399559/1062670756577808404/image.png">
</p>

## Preamble
This is the final release by The Raptors, an ultimate and grand script hub! The Raptors have released many great things over the years, but it is finally time to retire. We started by trolling IronBrew scripts in a very funny and **JUMPY** way, and we concluded with trolling SecureLua scripts in a very funny and **CONVERTY** way! We have prepared one final release for us to be remembered by, and that is Grand Raptors Hub! We hope you enjoy this hub and continue to cheer on The Raptors for the foreseeable future. Let's go Raptors!

## Showcase
Check out the showcase of this hub! Universal features and RoBeats are showcased!
https://www.youtube.com/watch?v=Z_wWAsmRUmY  
https://www.youtube.com/watch?v=PbveDYL5cTk

## Supported Games
This is a list of supported games that the hub should work at:
https://roblox.com/games/6938803436/  
https://roblox.com/games/8304191830/  
https://roblox.com/games/914010731/  
https://roblox.com/games/698448212/  
https://roblox.com/games/2677609345/  
https://roblox.com/games/4855457388/  
https://roblox.com/games/6439292574/

There is also a Universal Aimbot & ESP.

Note: There may be other games that the hub works on but they are not mentioned here because they may be patched there. This is due to some partnerships that the Secret Service may have with those devs where the source code was provided to them for security research, sorry about that. If you attempt to use it on Deepwoken, you may suffer the same fate as the character named Winter Sokolof who was banned for cheating on January 9, 2022 by HorrorTM. He didn't lose much though, but he had a Dumbbell that he only used 195 times!

## Using the Hub
To use the hub, simply run this! Best works on Synapse V2. Some features may not work on Synapse V3. If someone wants to make this UNC compatible, you can and may create a pull request to be reviewed after you are done.
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/RaptorsHubFinal/GrandRaptorsHub/main/grandraps.txt"))()
```

## Acknowledgements 
This Hub wouldn't have been possible without the continued support of the following:

 - Secret Service Director Zinnia
 - Secret Service Governing Council
 - Several imperial scientists from the Secret Service
 - The Raptors
 - Secret Service Infiltrator Agent Unit (IAU)
 - The Auguration (a.k.a., Secret Service Department of Great Powers (DGP); EST. July 2021); The Big Three:
	 - **The Augur** (Champion of Freedom; known for having power beyond comprehension; responsible for lots of anomalies since mid 2021; Auguration founder, it wouldn't exist without The Augur and his catalyst of power; His ascension changed the Secret Service forever)
	 - **Black Hat Moded** (Shell mastermind; Loves to meme setstack; Created Black Hat Moded's Gift to Humanity which was spreaded by The Augur with **unimaginable** power (9/23/2021 - 12/18/2021); Contributed to the Nautilus shell ("moded came up with this trick"))
	 - **Agent Solli** (Lua VM Expert; Loves to convert obfuscated bytecode to Vanilla Lua 5.1; He cherry picks the registers from the instructions!)

## Other
Looking for older versions of the hub?
Start here: https://github.com/HeftigHD/rapsHub

You will also find old UI libs for those versions.

Feeling nostalgic? Watch the very first Raptors Hub videos!
https://www.youtube.com/watch?v=OZqB_V5cIH4  
https://www.youtube.com/watch?v=-quv4YzjOv4

If you are wondering what SecureLua is going to be like for Synapse V3, take a sneak peek:
SecureLua V2.1 is a partial rewrite of SecureLua that is designed mostly as a real-life test of whats to come in SecureLua V3. As you can probably guess, it has more security features, so lets go ahead in order:
1) **No more need for SX_VM_A/B/C**. These can be safely removed from your code as a VM is automatically picked per function now.
2) **"Enhanced" security VMs**: SecureLua V2.1 includes enhanced-security VMs for security-critical code. Note that this code is _very_ slow (like we are talking 2-5x worse than Luraph), so only use them when necessary. 
	1) You can use an enhanced security VM by using the macros: `SX_VM_CVIRT()` and `SX_VM_CULTRA()`. The first one virtualizes the VM, while the second one virtualizes the VM and also mutates the resulting bytecode. As you can probably expect, both are incredibly slow (`CULTRA` is about ~2-5x slower than `CVIRT`).
	2) Obviously you can only use one or the other.
3) **"Low" security VMs**: SecureLua 2.1 also includes low-security VMs for namecall hooks and other code that doesn't need much protection.
	1) You can use them via the macro `SX_VM_CNONE()`.
4) **Automatic string and numeric encryption**: SecureLua 2.1 includes automatic string and numeric encryption on a per-function basis. Its automatically enabled for `SX_VM_CVIRT()` and `SX_VM_CULTRA()`, but you can also enable it for other VMs per-function via `SX_VM_ENC_CONSTS()`. (or disable via `SX_VM_DISABLE_ENC_CONSTS()`)
5) **Removal of SX_ENCRYPT()**: `SX_ENCRYPT()` has been removed in this update. (use "[SX_ENC]")
6) **Various bugfixes**: Various bug-fixes have also been applied to known-broken scripts.

## Support
If you require support, come meet with the SS Agents at the base located in Secret Service Glitcher Park: https://www.roblox.com/games/5821468164
