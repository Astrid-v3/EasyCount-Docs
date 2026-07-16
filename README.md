# EasyCount

EasyCount is a simple counting bot focused on providing a more comfortable experience than traditional counting bots.

It includes features such as:

* Wrong numbers not resetting the streak
* Adding comments to numbers
* Admin controls for managing the count
* Server-specific statistics

## How It Works

By default, every non-numeric message is ignored by the counter.

To add a comment to a counting number, add a `~` between the number and the comment.

Example:

```
42 ~ this is my lucky number
```

The bot will count this as `42` while keeping the comment.

## Commands

### `/set-channel` *(Admin only)*

Sets the counting channel to the channel where the command was used.

---

### `/increment <amount>` *(Admin only)*

Increments the current number by the given amount.

Example:

```
/increment 10
```

---

### `/set <amount>` *(Admin only)*

Sets the current number to a specific value.

Example:

```
/set 100
```

---

### `/next`

Shows the next number that should be counted.

---

### `/stats [member]`

Shows a member's counting statistics.

If no member is provided, it shows the statistics of the person running the command.

---

### `/report-issue <message>`

Reports an issue with EasyCount to the developers.

---

### `/readme`

Shows this documentation inside Discord.

## Support

For questions, bug reports, or support, contact:

**astrid.v3 on Discord**
