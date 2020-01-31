# Sherpa - Guided Differential Tester
Use the tool at https://coder0xff.github.io/sherpa/

A tool for tracking down the causes of bugs across many revisions

## Short explanation

This tool is used to track down the causes of bugs. Enter the bugs and suspect changes below, and follow the prompts at the bottom. If none of that makes sense, this scenario will help to clarify things:

## Long explanation

You have some system (e.g. software) that used to work correctly. Multiple changes have recently been made to it. (Examples of changes are adding mods to a game, adding some commits to a git repository, or substituting parts in a car.) However, since the changes were made, multiple issues have appeared (a.k.a. bugs). Undoing and redoing the changes one at a time might give you the information you need, or it might not. It can get complicated. If two changes are working together to create a problem, it will be hard to keep track off what combinations you've tried. The reality is that the combinations of factors leading to an issue can be arbitrary. In the worst case, a problem can be caused by multiple combinations independently! What to do? That's where this tool comes in. After you enter the bugs into the columns, and changes into the rows of the grid below, this tool will tell you which changes to undo and redo to collect that information in the fewest steps possible. When it's done, you'll get an overview in the grid, and if multiple independent combinations are the cause, you'll get a note on that as well. That's helpful, because while the grid may tell you that multiple changes are a problem, the notes will reveal that you can keep some of those problematic changes and still fix the problem! It should be noted, that while this tool performs this task in the optimal way, it can still take a lot of steps. The more changes you enter into the grid rows, the more effort it will take. Don't enter a change into the grid if you're absolutely sure that it's not a problem. This tool gets the most efficiency when the grid is wide, and short. One final cautionary note: be diligent. Just one mistake in entering data can spoil the entire result!
