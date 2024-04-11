The frist step to run this project is certifying that the Slack tokens: SLACK_BOT_TOKEN and SLACK_APP_TOKEN are correct because the tokens
can change from day to day. Wolfram Api and Wit_ai must be the same of when you first created.

1. First of all, we open powerShell in our project Folder and run 2 lines of command:
   
   - "go mod tidy" to certify that we have all the imports and dependencies working
     
   - "go run main.go" to run our main.go file and start the app
   - ![image](https://github.com/EricDias8/AiBot.GO/assets/89018394/3b8056af-7874-463b-b994-bc793a086717)
   
2. Then we head to our Slack workspace and added our created bot to a text channel.

   - just tag him in the chat and press enter(add to channel in green)
   - ![image](https://github.com/EricDias8/AiBot.GO/assets/89018394/7172195d-ec01-4ae6-b75b-99b210afdb4c)
    

   - after he is added to the channel whe just need to send him a query. the structure is:" @botname query for bot - (your question)"
   - ![image](https://github.com/EricDias8/AiBot.GO/assets/89018394/042dba4c-0107-4655-b72b-4d14830ce25e)
   

4. Press enter and see the result:
  - ![image](https://github.com/EricDias8/AiBot.GO/assets/89018394/ce880f0f-2439-40d9-86ca-02dc1b09d264)
  - we can also check at the powershell terminal the question that was sent to wolfram api(value):
  - ![image](https://github.com/EricDias8/AiBot.GO/assets/89018394/96a62161-4d13-4c87-80d8-7080706f8a92)
   

