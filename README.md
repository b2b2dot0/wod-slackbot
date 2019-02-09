# A simple Slackbot used to generate a random word of the day
## Setup
First run `bundle` from the root directory to install dependencies
## Run
Run `ruby tools/console.rb` from the root directory to test and play with the bot

## Parser
By default `Parser.new()` uses the merriam webster url (https://www.merriam-webster.com/word-of-the-day)
#### Requirements
* Nokogiri
* Rest-Client
### Fetching Word of The Day
1. `Parser.new()`
2. `Parser.fetch`
3. `Parser.definition`
