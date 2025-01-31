# 0array
Hello! I am **0array**. I work on web applications and games with Godot & Unity. I am a full-stack web developer who enjoys creating projects that appear simple and minimal to the viewer, often using flat dark colors. I hail from Sahiwal, Punjab, Pakistan, and I am currently 17 years old as of 2025. In the future, I aspire to be both a full-stack developer and a data scientist.

## My Projects

### Cubern
> I am no longer working on cubern.

[Cubern](https://cubern.sbs) was an online sandbox where creativity knew no bounds. Here, you could develop games and could had customized your character to showcase your style and passion.
#### Behind the Scenes
For the workshop, I utilized Godot 4.2 (.NET) in previous versions with custom compiled export templates for resource protection. It predominantly (99%) employed C# with minimal GDScript. I had also integrated [AOT Compilation](https://learn.microsoft.com/en-us/dotnet/core/deploying/native-aot/) featured in .NET 8.0.

I was utilizing later on Unity Game Engine.

For the runtime programming language (lua), I used [Moonsharp](https://www.moonsharp.org/) both on the client and the game server. And before leaving it I was shifting to [NLua](https://github.com/NLua/NLua) which is an interface between C# and C-Lua interpreter. 

On the website's backend, I leveraged ExpressJS as I explored JavaScript. For the frontend, I opted for VueJS due to its user-friendly nature and Single Page Application feature, ensuring a smooth experience for users.
#

### TLua
A simple transpiler which would convert "typed lua" to lua. An example:
```lua
local myName: string = "0array"
local myAge: int = 17
local somethingNonexistent: string? = nil
```
#
### Mopimo!
I also have made a port of a computer game [Bopimo!](https://bopimo.com) to Mobile and MacOS. It was written mostly with GDScript so the port was easier. However for GDExtension related part I do that work on a remote linux server which returns the result back to the port client or I simply re-wrote the functionality missing in GDScript. You can check it out yourself by heading to [the website!](https://mp.bokku.xyz)
