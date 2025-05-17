# Travel Agent
## Problem Statement:
Travel websites are too business centric. Products offered are not favouring the user, but the business! Using powerful search AI, collective social wisdom and not biased by business interests, the best products are always presented to the user.

User has many wants which cannot be satisfied by one-size-fits-all design. Mass customisation is the key to a delightful experience. User wants can be expressed clearly in words.  Recommendations based on user history profiling covers the entire ground.

It is painful to have to fill in forms and search parameters for air tickets and hotels. AI should ease this mental overhead, so as to allow the user to make good decisions.

Keeping track of the travel plan. Collecting information on bookings. Reminder to user of upcoming bookings. Assist user if cancellation is required.
Before any booking, checking that there is no conflict, inform if there is. Specify crteria, conflict in time and location, enough travel time, enough tour time.
Linking everything together in one page summary. Disemination of the travel plan by simply sharing with a group.

## Solution:
Major features are
1. Air Ticket Booking Agent
2. Hotel Booking Agent
3. Car Booking Agent
4. Attraction Booking & Activity Planning Agent

## Prototype using Claude Desktop
Start with Ticket booking agent. 
If it works well, then expand further

### Claude Desktop + MCP Servers
```
npm install -g @modelcontextprotocol/server-puppeteer
```

``` Config
{
  "mcpServers": {
    "puppeteer": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-puppeteer"]
    }
  }
}
```