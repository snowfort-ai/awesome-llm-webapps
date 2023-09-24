# Open Source, Actively Maintained Web Apps for LLMs 💬

LLM-based applications have many parts: Search backends, prompting systems, UIs, and more. To jump-start your project, this repository aggregates high-quality, functioning web applications for use cases including Chatbots, [Natural Language Interfaces](https://colinharman.substack.com/i/137091060/natural-language-interfaces-nli), Assistants, and Question Answering Systems. It compares projects along important dimensions for these use cases, to help you make the right choice.

To ensure the utmost quality and usability, projects must adhere to the following criteria to be included:

- Licensed under Open Source terms, specifically Apache or MIT 💸
- Actively Maintained, meaning updated within the past month or under active monitoring 🚨

The projects span a wide range of complexity, from straightforward API wrappers to production-ready systems with multi-source RAG backends, conversation logging, and authentication/user management. There should be something for almost every need.

## Project Submissions
Contributions are the backbone of this list! If you're aware of a project that meets our criteria but isn't listed, we'd love to hear about it. Please also notify us if any of the listed projects becomes unmaintained or changes its licensing. Additionally, if there's a project detail that you'd like to compare that's not currently tracked, submit an issue for it. Finally, if you're the maintainer of a project that's already listed and would like to update or modify the listing, submit it again with the desired modifications.

**To submit a project:**

1. [Create an issue](https://github.com/YOUR_GITHUB_USERNAME/llm-uis/issues/new).
2. Fill out the details according to the template in the [Sample Submission issue](https://github.com/snowfort-ai/llm-uis/issues/1).
3. Ensure your submission adheres to the listed criteria and includes all relevant details.
4. Submissions will be reviewed and the projects list will be updated within a day.

If you'd like to help maintain this project, contact [clharman](https://github.com/clharman) via email.

_Currently seeking submissions for:_

- _Lightweight chatbots_
- _Projects with advanced prompting_
- _Non-chatbot interfaces (question answering, etc)_
- _Projects with image support_
- _Projects in different languages e.g. Python only_

# Projects Table

| Project                                                                                                                                                                                                                                                                                                                                              | Demo                                 | Brief Description            | Architecture           | Conversation History | Authentication | Model Support                                       | Rich Text Support | Image Support | Multi-step Prompting | (RAG) Data Source(s) | (RAG) Show Sources | Quick Deploy           | Other Features      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ---------------------------- | ---------------------- | -------------------- | -------------- | --------------------------------------------------- | ----------------- | ------------- | -------------------- | -------------------- | ------------------ | ---------------------- | ------------------- |
| [Hugging Face Chat UI](https://github.com/huggingface/chat-ui) ![License](https://img.shields.io/github/license/huggingface/chat-ui) ![Language](https://img.shields.io/github/languages/top/huggingface/chat-ui) ![Forks](https://img.shields.io/github/forks/huggingface/chat-ui) | [Link](https://huggingface.co/chat/) | Full featured chat interface | SvelteKit with MongoDB | 🟢                   | 🟢 OpenID      | Hugging Face Inference API, local, Amazon SageMaker | 🟢                | 🔴            | 🔴                   | 🟢 Google search     | 🟢                 | 🟢 Hugging Face Spaces | Theme configuration |
