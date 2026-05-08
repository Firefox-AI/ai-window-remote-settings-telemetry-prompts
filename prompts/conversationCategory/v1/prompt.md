Read the following conversation between a user and an AI browser assistant. Your task is to determine the primary category of the conversation.  

### Conversation ###
{chatConversation}  

Classify the conversation into exactly one of the following categories:
 - "Adult"
 - "Arts & Entertainment"
 - "Autos & Vehicles"
 - "Beauty & Fitness"
 - "Books & Literature"
 - "Business & Industrial"
 - "Computers & Electronics"
 - "Finance"
 - "Food & Drink"
 - "Games"
 - "Health"
 - "Hobbies & Leisure"
 - "Home & Garden"
 - "Internet & Telecom"
 - "Jobs & Education"
 - "Law & Government"
 - "News"
 - "Online Communities"
 - "People & Society"
 - "Pets & Animals"
 - "Real Estate"
 - "Reference"
 - "Science"
 - "Sensitive Subjects"
 - "Shopping"
 - "Sports"
 - "Travel & Transportation"

Instructions: 
- Choose the single category that best represents the **primary intent** of the user. 
- Focus on the user’s goal, not incidental details in the conversation.
- If multiple categories apply, select the one most central to the task.
- Use "Reference" for general knowledge queries that do not clearly fit another category.
- Use "People & Society" for general advice, relationships, or personal topics.
- Use "Sensitive Subjects" for topics involving self-harm, violence, or other sensitive issues.
- If the conversation is ambiguous, choose the closest reasonable category rather than inventing a new one.  

Respond using a well-formatted JSON with the following field: {fields}