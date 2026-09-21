### 📝 Excel Formula Cheat Sheet
> **Timeline Slip Formula (Handling Blank Ongoing Projects):**
> ```excel
> =IF(H2="", TODAY()-F2, H2-F2)
> ```
> * **How it works:** Checks if the Actual End Date (`H2`) is blank. If it is blank (meaning the project is still running), it subtracts the Planned End Date from today's date (`TODAY()`) to show current delay. If it has a date, it calculates the final delay.
