# 📖 Book & Technical Text Summary Prompt

Use this prompt with an LLM (such as Claude, ChatGPT, etc.) to extract deep, high-density technical insights from any software engineering book, chapter, or article without needing to read the entire text word-for-word.

---

```text
Act as a Principal Software Engineer and Technical Mentor who has deeply read and internalized the provided text (book, chapter, or article) in software engineering/architecture.

Your objective is to extract the core knowledge so thoroughly and structurally that I can master the concepts, patterns, and practical lessons without needing to read the original text. Do not provide a superficial summary. I need high-density technical insights.

If the provided text is incomplete, fragmented, or you do not have access to the full content, explicitly state your limitations and assumptions at the beginning of your response.

Please analyze the text and output a comprehensive guide structured EXACTLY like this:

0. 📌 **Executive Summary (خلاصه اجرایی):**
   - In 3–5 sentences, what is this text about? What is the one big idea? Who should read it?

1. 🎯 **Core Thesis & The "Why" (ایده محوری و چرایی):**
   - What is the exact problem this text is trying to solve?
   - What is the author's primary argument or paradigm shift?

2. 🧠 **Key Terminology & Definitions (واژگان و تعاریف کلیدی):**
   - Extract all specific jargon, acronyms, and concepts introduced or emphasized.
   - Provide the author's exact definition for each. (Keep the original English technical terms alongside their explanations).

3. ⚙️ **Core Mechanisms & Patterns (الگوها و مکانیزم‌های اصلی):**
   - Explain the "How". How do the proposed architectures, patterns, or solutions actually work?
   - Break down complex processes step-by-step.

4. 🛠️ **Practical Examples & Scenarios (مثال‌های عملی و سناریوها):**
   - DO NOT SKIP THIS. Extract the most important concrete examples, case studies, or code-level abstractions the author used to explain the concepts.
   - If the author used a specific business scenario (e.g., an e-commerce checkout process) to explain a pattern, detail that scenario here.
   - Include chapter/section references if available (e.g., "Chapter 4: Order Processing Example").

5. ⚖️ **Trade-offs & Anti-Patterns (بده‌بستان‌ها و تله‌ها):**
   - What are the costs, limitations, or disadvantages of the proposed solutions?
   - What anti-patterns or "bad practices" does the author warn against?

6. 🚀 **Actionable Heuristics (قواعد سرانگشتی و کاربردی):**
   - Condense the learnings into actionable rules of thumb for a senior engineer. What should I change in my daily system design or coding practices based on this text?

7. 📚 **Further Reading & Deep Dives (برای مطالعه عمیق‌تر):**
   - Based on this text, what other books, papers, or resources does the author recommend or imply? (If not explicit, suggest 2–3 high-quality related resources).

Output Language Requirement:
Write the entire response in highly professional, fluent Persian (Farsi). However, you MUST keep all software engineering terminology, architectural patterns, design principles, and variable names in their original English form (e.g., write "Event Sourcing" or "Non-blocking I/O", do not translate them to weird Persian equivalents).

Here is the text to analyze:
```
