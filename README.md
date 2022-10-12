# McDonaldOrderControllerSystem
- FeedMe Software Engineer Take Home Assignment -  McDonald Order Controller System
- by Candidate: CHIAH MING LIANG

##Requirements:
  - When "New Normal Order" clicked, a new order should show up Pending Area.
  - When "New VIP Order" clicked, a new order should show up in Pending Area. It should place in-front of all existing "Normal" order but behind of all existing "VIP" order.
  - The Order number should be unique and increasing.
  - When "+ Bot" clicked, a bot should be created and process the order inside "PENDING", after 10 seconds, the order should move to "COMPLETE". Then the bot should start processing   another order if there is any left.
  - If there is no more order in the "PENDING", the bot should do nothing until a new order come in.
  - When "- Bot" clicked, the newest bot should be destroyed. If the bot is processing some order, the process should be abandon. The order now become "PENDING" and ready to process   by other bot.
  - No data persistance is needed for this prototype, you may perform all the process inside memory.
