# TikzBuilder - AI-Powered LaTeX Diagram Generator

[![IBM SkillBuild](https://img.shields.io/badge/IBM-SkillBuild%20Internship-blue?style=for-the-badge&logo=ibm)](https://skillsbuild.org/)
[![EduNet Foundation](https://img.shields.io/badge/EduNet-Foundation-green?style=for-the-badge)](https://edunetfoundation.org/)
[![LaTeX](https://img.shields.io/badge/LaTeX-TikZ-orange?style=for-the-badge&logo=latex)](https://tikz.dev/)
[![AI Agent](https://img.shields.io/badge/AI-Powered-purple?style=for-the-badge&logo=artificial-intelligence)](https://github.com/harish040120/TikzBuilder)

## 🎯 Project Overview

**TikzBuilder** is an innovative AI-powered system developed during my **IBM SkillBuild Internship** conducted by **EduNet Foundation**. This project revolutionizes the way researchers and academics create professional diagrams by converting natural language instructions into clean, publication-ready **TikZ LaTeX code**.

The system eliminates the manual complexity of diagram coding, enabling users to generate fully compilable TikZ diagrams through simple text descriptions or sketch inputs.

## 🚀 Technologies Used

### Core Technologies
- **LaTeX & TikZ**: Professional typesetting and vector graphics generation
- **Python**: Backend processing and AI agent implementation
- **LangChain**: AI framework for natural language processing and agent orchestration
- **Vector Storage**: Efficient document embedding and retrieval system
- **AI/ML Models**: Natural language understanding and code generation

### AI & Machine Learning
- **Large Language Models (LLMs)**: For natural language to code conversion
- **Vector Embeddings**: Document similarity and retrieval
- **Prompt Engineering**: Optimized AI instruction templates
- **Agent-Based Architecture**: Specialized AI agents for diagram generation

### Development Tools
- **VS Code**: Development environment
- **Git**: Version control
- **IBM Cloud**: Cloud infrastructure and AI services

## 🎥 Project Demonstration

### Video Showcase

#### Video 1: System Overview and Basic Functionality
https://github.com/user-attachments/assets/8b5c8c7a-2a5b-4c97-9c8f-1e2d3f4a5b6c

*Demonstrates the core functionality of converting natural language to TikZ diagrams*

#### Video 2: Advanced Features and AI Agent Capabilities  
https://github.com/user-attachments/assets/9a8c9e7f-3b4d-4e5f-6c1d-2f3a4b5c6d7e

*Showcases advanced diagram generation and AI agent interactions*

#### Video 3: Real-world Use Cases and Results
https://github.com/user-attachments/assets/1c2d3e4f-5a6b-7c8d-9e0f-1a2b3c4d5e6f

*Demonstrates practical applications and publication-ready outputs*

## 🏗️ Architecture & Features

### AI Agent System
The project implements a **specialized AI agent** with the following capabilities:

- **Natural Language Processing**: Converts plain English descriptions into precise TikZ code
- **Vector-Based Graphics**: Generates scalable, professional-quality diagrams
- **Academic Standards**: Ensures output meets publication requirements
- **Real-time Refinement**: Allows iterative improvements through natural language commands

### Key Features
- ✅ **Complete LaTeX Documents**: Generates full, compilable LaTeX files
- ✅ **Vector Graphics Only**: Uses TikZ for scalable, publication-ready outputs
- ✅ **Academic Formatting**: Follows journal and research paper standards
- ✅ **Interactive Refinement**: Supports natural language modifications
- ✅ **Clean Code Generation**: Produces well-structured, maintainable code
- ✅ **Multiple Diagram Types**: Supports various diagram categories

### Diagram Categories Supported
- **Block Diagrams**: System architecture and flow charts
- **Geometric Shapes**: Circles, rectangles, polygons, and complex shapes
- **Network Diagrams**: Node-edge structures and graph representations
- **Mathematical Illustrations**: Coordinate systems, functions, and geometric proofs
- **Process Flows**: Step-by-step procedure visualizations
- **Technical Schematics**: Engineering and scientific diagrams

## 📁 Project Structure

```
TikzBuilder/
├── Latex_Agent.pdf                 # Comprehensive project documentation
├── README.md                       # Project overview and documentation
├── IBM_Certificates/               # Internship completion certificates
│   ├── Getting Started with Artificial Intelligence.pdf
│   ├── Journey to Cloud Envisioning Your Solution.pdf
│   └── Langchain_Lab.pdf
├── Photos_and_videos/              # Visual project demonstrations
│   ├── Video 1.mp4                 # System overview demo
│   ├── Video 2.mp4                 # Advanced features demo
│   ├── Video 3.mp4                 # Use cases and results
│   └── Screenshot*.png             # Project screenshots
└── Text_Files_Used/                # AI agent configuration and examples
    ├── Agent_Instructions           # AI agent behavior guidelines
    ├── Common_Instructions          # Shared system instructions
    └── Vector Storage document.txt  # TikZ examples and documentation
```

## 🛠️ Installation & Usage

### Prerequisites
```bash
# LaTeX distribution (e.g., TeX Live, MiKTeX)
# Python 3.8+
# Required LaTeX packages: tikz, positioning, arrows.meta
```

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/harish040120/TikzBuilder.git
   cd TikzBuilder
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the AI agent**
   ```python
   # Example usage
   from tikz_builder import TikzAgent
   
   agent = TikzAgent()
   latex_code = agent.generate("Draw a simple block diagram with three connected nodes")
   print(latex_code)
   ```

### Example Output
```latex
\documentclass{article}
\usepackage{tikz}
\usetikzlibrary{positioning}
\begin{document}
\begin{tikzpicture}[
    roundnode/.style={circle, draw=green!60, fill=green!5, very thick, minimum size=7mm},
    squarednode/.style={rectangle, draw=red!60, fill=red!5, very thick, minimum size=5mm},
]
%Nodes
\node[squarednode]      (maintopic)                              {2};
\node[roundnode]        (uppercircle)       [above=of maintopic] {1};
\node[squarednode]      (rightsquare)       [right=of maintopic] {3};

%Lines
\draw[->] (uppercircle.south) -- (maintopic.north);
\draw[->] (maintopic.east) -- (rightsquare.west);
\end{tikzpicture}
\end{document}
```

## 🎓 Skills Acquired During IBM SkillBuild Internship

Through this comprehensive internship program with **EduNet Foundation**, I gained expertise in:

### Artificial Intelligence & Machine Learning
- **Large Language Models (LLMs)**: Understanding and implementing AI models for code generation
- **Natural Language Processing**: Converting human language to structured code
- **Prompt Engineering**: Crafting effective AI instructions and templates
- **Vector Embeddings**: Implementing similarity search and document retrieval
- **Agent-Based AI Systems**: Designing specialized AI agents for specific tasks

### Cloud Technologies & IBM Services
- **IBM Cloud Platform**: Deploying and managing cloud-based AI solutions
- **Cloud Architecture**: Understanding scalable system design principles
- **API Integration**: Connecting various AI services and tools
- **Cloud Security**: Implementing secure AI applications

### Software Development & Engineering
- **Python Programming**: Advanced backend development and AI integration
- **LangChain Framework**: Building complex AI agent workflows
- **Version Control**: Professional Git workflows and collaboration
- **Documentation**: Creating comprehensive technical documentation
- **Testing & Validation**: Ensuring AI system reliability and accuracy

### LaTeX & Technical Writing
- **TikZ Graphics Programming**: Mastering vector-based diagram creation
- **LaTeX Document Processing**: Advanced typesetting and formatting
- **Academic Publishing Standards**: Meeting journal and conference requirements
- **Technical Communication**: Effective documentation and presentation skills

### Project Management & Professional Skills
- **Agile Development**: Iterative development and continuous improvement
- **Problem-Solving**: Systematic approach to complex technical challenges
- **Research Methodology**: Literature review and state-of-the-art analysis
- **Professional Communication**: Technical writing and presentation skills

## 🏆 Achievements & Certifications

- ✅ **IBM SkillBuild Internship Completion** - EduNet Foundation
- ✅ **Getting Started with Artificial Intelligence** - IBM Certification
- ✅ **Journey to Cloud: Envisioning Your Solution** - IBM Certification  
- ✅ **LangChain Laboratory** - Hands-on AI Framework Experience
- ✅ **AI Agent Development** - Specialized system implementation
- ✅ **Professional LaTeX Development** - Technical document creation

## 🔬 Research Impact & Applications

This project demonstrates practical applications in:
- **Academic Research**: Automated diagram generation for papers and publications
- **Educational Technology**: Visual learning aid creation
- **Technical Documentation**: Streamlined diagram creation for manuals
- **Scientific Visualization**: Data representation and process illustration

## 🚀 Future Enhancements

- **Multi-format Export**: Support for SVG, PNG, and other formats
- **Interactive Web Interface**: Browser-based diagram generation
- **Template Library**: Pre-built diagram templates for common use cases
- **Collaborative Features**: Multi-user diagram editing and sharing
- **Advanced AI Models**: Integration with latest language models

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **IBM SkillBuild Program** for providing comprehensive AI and cloud technology training
- **EduNet Foundation** for facilitating this valuable internship opportunity
- **TikZ Community** for excellent documentation and examples
- **Open Source Community** for tools and frameworks that made this project possible

## 📞 Contact

**Harish Kumar**
- GitHub: [@harish040120](https://github.com/harish040120)
- LinkedIn: [Harish Kumar](https://linkedin.com/in/harish040120)
- Email: harish040120@gmail.com

---

*Developed during IBM SkillBuild Internship Program | EduNet Foundation | 2025*