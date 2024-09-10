
# Raw Objective AI

## Overview
**Raw Objective AI** is an open-source initiative designed to improve transparency in government processes by creating an objective and unbiased AI system. This project focuses on analyzing official Spanish government sessions and publications to provide citizens with clear and accurate insights into political decisions and actions.

## Features
- **Text Analysis with LLMs:** Process and analyze text-based government documents (e.g., BOEs) using Large Language Models.
- **Video Analysis with VLMs:** Extract meaningful data from government session videos using Visual Language Models.
- **Retrieval-Augmented Generation (RAG):** Implement RAG to enhance data retrieval and generation, ensuring objectivity and accuracy.
- **Objective Insights:** Minimize AI hallucinations using **Pydantic** to ensure that responses and generated insights are reliable and factual.
  
## Project Roadmap
1. **Phase 1:** 
   - Setup initial LLM and VLM pipelines for basic text and video processing.
   - Gather data from available government session videos and BOEs.
   - Create a database for storage and RAG integration.
   
2. **Phase 2:** 
   - Expand the system to analyze data from political party sources.
   - Improve response objectivity by optimizing the Pydantic-guided validation system.

3. **Phase 3:** 
   - Develop user-friendly interfaces for querying data.
   - Build out the collaborative open-source community.

## How to Contribute
We welcome contributions from developers, data scientists, and AI enthusiasts! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Submit a pull request with a clear description of your changes.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/raw-objective-ai.git
   cd raw-objective-ai
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:

   ```bash
   cp .env.example .env
   ```

4. Run the application:

   ```bash
   python main.py
   ```

## Technologies Used
- **Large Language Models (LLMs):** For text analysis and understanding.
- **Visual Language Models (VLMs):** For video and image processing.
- **Retrieval-Augmented Generation (RAG):** To optimize information retrieval and generation.
- **Pydantic:** For data validation and to reduce hallucinations in AI outputs.
  
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact
For questions or suggestions, feel free to reach out by creating an issue or via email at: [fjmontiel98@gmail.com].
