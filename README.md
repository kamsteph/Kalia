# Kalia

Kalia is a private AI-powered pentesting platform that performs both **vulnerability scanning** and **exploit execution** across multiple targets. It uses generative AI to guide tool selection, execution, and result summarization — making penetration testing faster, smarter, and more human-readable.

---

##Features

-Parallel Pentesting**: Run web, network, and other scan types simultaneously without conflict.
-AI Tool Suggestion**: OpenAI LLM recommends the most suitable tools for the target and attack type.
-Automatic Tool Download & Management**: Downloads and stores tools temporarily for immediate use.
-Generative AI Summarization**: Translates complex scan results into readable summaries for humans.
-Cross-Platform UI**: Accessible via mobile or web with Flutter frontend.
-Exploit Automation**: Includes attack-phase execution after scan, with timed confirmation logic.

##Tech Stack

-Frontend: Flutter (Web + Mobile)
-Backend: Python + FastAPI
-Database: SQL (PostgreSQL or similar)
-AI/ML: OpenAI LLMs (for decision-making and summaries)
-Other Tools: WebView, parallel task execution, FastAPI background workers

 ###Packages
 -The packages used are found in the Requirements.txt file