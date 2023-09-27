
# 🧟 Resident Evil 0 Item and Enemy Randomizer 🧟

Randomize items and enemies with this Resident Evil Zero randomizer.

<p align="center">
   <img src="https://user-images.githubusercontent.com/130005214/230778106-bb002143-1225-449f-a585-87d5db97cc1f.png">
</p>

## Configuration

1. Run the `Configurator` to create a randomizer configuration.
2. I added (very few...) __useful options__, like excluding ink ribbons from randomization.
3. Set your preferences for randomized items. You can increase stack size or activate "balanced" mode, which gives you a higher chance to get useful items.
<p align="center">
   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/130005214/270784867-1e60c548-1ef4-4b9c-8123-c86bd5a71177.png">
</p>

**IMPORTANT NOTE ON ENEMY RANDOMIZATION!**
TLDR: Remember to **hit the shuffle button!**

In version 1.1.0, I made a slight oversight. **By default, all enemies are matched with their own kind**. To introduce variety and unpredictability, ensure to hit the shuffle button at least once or map the enemies manually. Enhance your gaming experience - don’t forget to shuffle!

## Usage

1. Create a configuration and select a working directory. Check the checkbox and click the shuffle button if you want to randomize enemies.
3. Start the game and also launch the Randomizer itself.
4. Load your config and connect to the game (you only need to click two buttons...).
5. Now, just start or continue your randomized game and enjoy the chaos!

Happy randomizing! 🎮🧟

## Please Report Crashes
Help me to make this randomizer more stable. Report crashes and send me the init.json files with a copy of your randomizer log that appears for every run when you start randomizing. 


## Known Issues

- The randomizer is often stuck in background when closing. Check your Task Manager and search for CheatEngine or the Resident Evil Randomizer.exe
- The **Balanced mode** was **FIXED IN 1.0.2**
- The **stack count** issue was **FIXED IN 1.0.2**

- Issues with stack cound may arise when two items of the same type are placed in the same room. **Be careful when dropping and picking up again, until I provide a fix**
- In a case where many items are dropped at once, some items were lost. I am addressing this issue. **Don't drop too many items at once, until I provide a fix**


# Development and Upcoming Features
- **Enemy randomization is now available in 1.1.0**
- Adding more options to the Configurator (backlog)
- Enhancing item drop mechanism (backlog)

## Soft Lock Warnings and Crashes
- User NeoSyther figured out, that you should not use the lift after you unlocked the kitchen with the "Fire Key". Fixes and workarounds are under dicussion. For more infos see Issue #3.

## AntiVir False Positives
This randomizer is based on the popular open source development software Cheat Engine, which can trigger false positive anti virus alerts.
See: https://github.com/HansRandomizer/Resident-Evil-0-Randomizer/issues/4#issuecomment-1666964788

# DISCLAIMER

You use this software at your own risk.

This software is based on Cheat Engine. The authors of this software cannot take responsibility for any harm,
damage, or issues that may arise from the use of Cheat Engine or its components. Users acknowledge that they use this 
software at their own risk.


THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE 
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR 
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
