# RegularExpressionsNotes
- Use or opperetor | to include various names to match characters
- You can use a range for a character set to match any letters used [a-z]
- you can use the plus operator to catch as many characters you want +
- i allows for case sensitive characters 
- \s represents white space, tabs, and new lines
- 0-9 range can allow to catch numbers used 
- \w only searches for 1 word 
- use the @ symbol to require it in an email
- \. will catch a period in an email dont use just period as it will catch any character except new line
- check for ending operator (com|net|org|edu)
- ^ character at start of expression and $ at end to make sure nothing is added before or after the email
- /b catches whole words only put before and after word 
- ? operator allows portions to be optional ex. ok(ay)? 
- \d matches anything thats not a number 
- {#,#} allows you to set a min and max number of characters to match
- groups can return values to you so everything within () can be captured you can nest as well with double parentheses
- ?: non caputuring group
