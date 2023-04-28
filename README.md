.chat {
  height: 100%;
  display: flex;
  flex-direction: column;
}

.chat-header {
  height: 50px;
  background-color: #4267b2;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
}

.chat-history {
  flex-grow: 1;
  overflow-y: scroll;
  padding: 10px;
}

.chat-message {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-bottom: 10px;
}

.chat-message.right {
  align-items: flex-end;
}

.chat-message-content {
  padding: 10px;
  border-radius: 20px;
  background-color: #f0f0f0;
  max-width: 70%;
  word-wrap: break-word;
  box-shadow: 1px 1px 3px #ddd;
}

.chat-message-content.right {
  background-color: #4267b2;
  color: #fff;
}

.chat-message-time {
  font-size: 12px;
  color: #aaa;
  margin-top: 5px;
}
