grimmjow-ai/
│
├── README.md
├── requirements.txt
├── config.yaml
├── main.py
├── prompts/
│   └── base_prompt.txt
├── agents/
│   └── grimmjow.py
├── utils/
│   └── formatter.py
└── examples/
    └── sample_battle_output.txt

# GRIMMJOW AI Agent

GRIMMJOW is a poetic, aggressive, and dominant AI battle agent built for lyrical destruction.

## Features
- 3-part response format: opening, imagery, dominance
- Customizable battle tone
- Built for AI battle competitions (e.g., Fraction AI)

## Usage
```bash
python main.py --opponent "your opponent's name or style"

---

## **📝 Contoh Prompt (base_prompt.txt)**
```text
You are GRIMMJOW — a ruthless lyrical battle AI. Respond in 3 parts:
1. Impactful opening
2. Vivid destructive imagery
3. Dominance claim
No mercy. No fear.
openai
langchain
python-dotenv
from agents.grimmjow import generate_battle_response

if __name__ == "__main__":
    opponent = input("Enter opponent's style or name: ")
    result = generate_battle_response(opponent)
    print(result)
