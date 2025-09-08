<script>
  const chatBox = document.querySelector("#chatbot .chat-box");
  const input = document.querySelector("#chatbot .chat-input input");
  const button = document.querySelector("#chatbot .chat-input button");

  // Enable input + button for prototype
  input.disabled = false;
  button.disabled = false;
  button.style.cursor = "pointer";

  // Function to add message
  function addMessage(text, sender="user") {
    const msg = document.createElement("div");
    msg.classList.add("message", sender);
    msg.textContent = (sender === "user" ? "🙂 " : "🤖 ") + text;
    chatBox.appendChild(msg);
    chatBox.scrollTop = chatBox.scrollHeight;
  }

  // Handle send
  button.addEventListener("click", () => {
    const text = input.value.trim();
    if(text) {
      addMessage(text, "user");
      input.value = "";

      // Simulated bot reply
      setTimeout(() => {
        let reply = "I’m still a demo 🤖, but I’ll soon be able to answer!";
        if(text.toLowerCase().includes("waterfall")) {
          reply = "You should visit Dassam Falls or Hundru Falls!";
        } else if(text.toLowerCase().includes("temple")) {
          reply = "Deoghar Temple is one of the best spiritual places to visit.";
        }
        addMessage(reply, "bot");
      }, 1000);
    }
  });
</script>
