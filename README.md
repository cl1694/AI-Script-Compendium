# AI-Script-Compendium

**Note: This compendium is used for quick script looking up. Refer to the links for how the script exactly does and its special requirement.**

Here is a list of all script that is posted in `#ai-scripts` channel in the FSS Discord Server.

Doesn't include scripts for using skills in Tower Testing, since they should be paired with a certain bp to use.

Doesn't include scripts that is made to pair with another existing script.

Doesn't include scripts that I think is too useless. In other words, scripts that can be made in a minute, and don't work better than other similar scripts.

All scripts are sorted based on their category, then release date.

## Format
```
## [script category]
#### [script name or usage] by [script author]([script special tags, if any]), ([script count]/[max action line])
[basic introduction, optional]
[discord post link] [other links if any]
```

Script count and max action line can be an interval(written as `xx-yy`), means that there are different variants of the script, while the one with minimum amount of count/action has `xx` of that and one with maximum amount has `yy`.

Note that both of the two numbers can be displayed in the interval form, which means that a format of `(2-3/12-14)` is possible.

If the difference between the versions are large, do the values in different brackets(for example, `(2/12) / (1/13)`).

### Script Special Tag List
- `Turbo vX`: Requires having the Turbo Exec vX pack imported and enabled.
- `Turbo vX Opt`: This script work without Turbo exec vX, but work faster if it is used.
- `Parallels`: This script accelerates itself by calling multiple instances of itself, faster than normal script but usually not as fast as turbo.
- `Turbo Own`: This script uses own build-in Turbo exec version to accelerate, therefore it isn't working with Turbo exec v1 enabled.
- `P`: This script pack is organized in a package when imported. May be missing from old scripts that have recieved an update to pack them.
- `C0`: This script uses fixed-coordinated clicks, therefore only work on a **specific resolution** and dynamic ui settings.
- `C1`: This script uses regular rel-clicks, therefore work on **any resolution with fixed aspect ratio**(4:3, 16:9, etc.).
- `C2`: This script uses advanced rel-clicks, and would work properly on **most resolution**(with dynamic ui off). Still have tall/wide screen issue due to the game ui size mechanics.
- `C3`: Like `C2`, but checks the screen type and should work on **all regular resolution**, with ui size at 100%(usually still with dynamic ui off).
- `C4`: `C3` but with extra ui size support, works at any resolution and any ui size.

Scripts without any of the `Cx` tag doesn't use clicks.

## Tool Links
[Kyromyr's external editor](https://kyromyr.github.io/perfect-tower/)

[d0sboots' external editor](https://d0sboots.github.io/perfect-tower/)

[Turbo exec v1(aka execution pack)](https://github.com/Xenos6666/TPT2_scripts/blob/main/common/execution_stack/README.md)

[Turbo exec v2](https://github.com/Xenos6666/TPT2_scripts/blob/main/common/turbo_exec/README.md)

## Updates
All script posted before [this](https://discord.com/channels/488444879836413975/850425171059933272/959862845900718162) is added to the list.
