A new project was initialized the same way as Problem 1, and Chainlit was installed with 'uv add chainlit'. Running 'chainlit hello' confirmed the installation was working at http://localhost:8000.
Decorators used by Chainlit
@cl.on_chat_start → new chat session   |   @cl.on_message → new user message   |   @cl.on_stop → user clicks stop   |   @cl.on_chat_resume → user resumes a session   |   @cl.on_chat_end → user disconnects or starts a new session.
Stateful chatbot (remembers previous messages)
A stateful version stores conversation history in cl.user_session so the assistant can recall earlier details — this is built in full in Problem 3.
