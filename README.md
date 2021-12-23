# DefenderCheck
Quick tool to help make evasion work a little bit easier.

Takes a binary as input and splits it until it pinpoints that exact byte that Microsoft Defender will flag on, and then prints those offending bytes to the screen. This can be helpful when trying to identify the specific bad pieces of code in your tool/payload.

Simple tweak adjustment to show why the file triggered - somethimes I have found if the trigger bytes were the very last bytes in file, even though it triggered AV, DefenderCheck would say it was clean.

