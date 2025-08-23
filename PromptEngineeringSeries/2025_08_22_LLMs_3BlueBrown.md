# Large Language Models Explained (3Blue1Brown)

📅 Date: 22 Aug 2025 – Friday  
🎯 Source: [YouTube – 3Blue1Brown](https://www.youtube.com/watch?v=LPZh9BOjkQs)  
📚 Series: Prompt Engineering Series (AI Prompt Engineering Academy)

---

## 🔑 Key Notes
Ever played the game “Finish the Story”?
You start with: “The fluffy cat sat on the…”
And the AI might guess: “mat”, “roof”, or even *“spaceship”! 🚀
But how does it get so clever?

📚 It’s trained on millions of texts—books, articles, websites—more than all the libraries in your city combined!

🧠 Inside its “brain” are tiny adjustable settings called parameters or weights.
Every time it makes a mistake, it tweaks these knobs to improve its predictions.

💻 This learning happens fast thanks to powerful machines called GPUs, which can process data at incredible speeds—like compressing centuries of reading into weeks!

- LLMs are **probability machines** → predict the next word.

🎓 First, it learns to predict words and complete sentences (pre-training).
Then, humans guide it with feedback—what’s helpful, kind, or respectful—through Reinforcement Learning with Human Feedback (RLHF).

- Uses **transformers** (attention mechanism).

💡 The real magic lies in a component called the Transformer:
Part 1: Attention Mechanism
It looks at all words in a sentence at once, helping them “talk” to each other.
So when you say “river bank”, it knows you mean the edge of a river, not a piggy bank

- **Context window** = memory size.

Part 2: Feed-Forward Neural Network
This part stores patterns it learned during training, helping it remember and apply knowledge.

🔁 If it gets something wrong, the Backpropagation Algorithm steps in to adjust the smart knobs and retrain the model.

And that’s how your AI assistant becomes a thoughtful, intelligent companion!

- Scaling laws → more data + bigger models = better performance.

