Read the following conversation between a user and an AI browser assistant. This conversation is relatively long and may involve multiple turns, topic shifts, or extended problem-solving.

### Conversation ###
{chatConversation}

Evaluate the conversation on the following criteria, assigning each category one of the listed values:

- "taskProgression":
  - "steady": The conversation shows clear, consistent progress toward a goal across turns.
  - "stalled": The conversation shows little to no forward progress despite multiple turns.
  - "regressive": The conversation repeatedly backtracks, resets, or revisits the same issues without progress.

- "conversationDrift":
  - "focused": The conversation remains centered on a single task or closely related tasks.
  - "moderate_drift": The conversation includes some tangents or minor topic changes but stays mostly on track.
  - "high_drift": The conversation significantly diverges into unrelated topics or loses the original intent.

Respond using a well-formatted JSON with the following fields:
{fields}
