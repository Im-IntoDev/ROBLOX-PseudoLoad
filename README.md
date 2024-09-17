# ⚡PseudoLoad⚡
An open-source ROBLOX loading module designed to replicate the look of a genuine loading process, though the effect is largely simulated.
<br><br/>

You might wonder why simulating a loading process is useful.
The answer is simple: **creating real loading screens is often impossible.**

## 🌐Explore more
Like what you're seeing? Find more in [my community server](https://discord.gg/R9hp2vbpP5).

## 🚀How to use
1. Download the `.rbxm` file.
2. Drag and drop the file from your file explorer into Roblox Studio.
3. Parent the module to ReplicatedFirst to ensure it appears during the loading phase. This is the recommended location for any loading screen code.

💡**Below is a simple example use of the module.**
```lua
require(script.PseudoLoad)() -- will yield.

print("Finished loading!")
```

## ⚙️Configuration
Before you use it, you may want to explore the optional configuration options.

Inside of the main module you will find a submodule named `Configuration`.
Open it up and you'll see a few configuration options, which are explained to the best of my abiltity.
Once you've edited the values, you're good to go!

## 💬Feedback
Your feedback is highly appreciated, as it helps improve the user experience for everyone. Feel free to reach out if you have suggestions or run into issues.

**Contact:** Discord: *Im_IntoDev* or [my community server](https://discord.gg/R9hp2vbpP5)
