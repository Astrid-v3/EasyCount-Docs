## Introduction
The `EasyCount` bot is a simple counting bot focussed on providing a more comfortable experience than other bots. By default it includes features like wrong numbers not resetting the streak, options to add comments to numbers and admins being able to actively control the count.

## Info
By default, every non-numeric message is ignored by the counter. To add a comment to a counting number, add a `~` between the number and the comment.

## Commands
`/set-channel` (admin only):
    sets the counting channel where it was run

`/increment <amount>` (admin only):
    increment the current number by the given amount

`/set <amount>` (admin only):
    set the current number to the given amount

`/next`:
    reveals the next number

`/stats [member]`:
    returns a member's statistics/the statistics of the person running it if no argument is provided.

`/report-issue <message>`:
    report an issue with the bot to the developers

`/readme`:
    sends an invisible message containing this project's `README.md` file
