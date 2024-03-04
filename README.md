<img src="r5.png" alt="Logo" width="150" height="150">

# ChatTube

## Introduction

ChatTube is an innovative AI-powered tool designed to enhance learning experiences while watching educational videos. It leverages the power of OpenAI's GPT-4 API to analyze video transcripts and provide instant clarification for students' doubts. Additionally, it assists teachers in generating quiz questions based on the video content.

## Getting Started

### Setting up locally

1. **Clone the repo:**
    ```sh
    git clone https://github.com/roshangeorge97/ChatTube
    ```

2. **Navigate to the repository:**
    ```sh
    cd ChatTube
    ```

3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```
    
3. **Change your OPEN AI KEY on streamlitui.py**
    ```sh
    st.session_state["OPENAI_API_KEY"] = "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"
    ```

4. **Run the StreamLit App:**
    ```sh
    python -m streamlit run streamlitui.py
    ```

## Screenshots

<img src="r3.png">
<img src="r1.png">



## Features
<img src="r4.png">

- **Real-time Doubt Clarification**: Students can ask questions and receive immediate answers during the lecture.
- **Timestamp Tagging**: Users can tag specific timestamps in the video to ask questions related to particular sections.
- **Lecture Notes Generation**: ChatTube facilitates the creation of lecture notes within seconds.
- **Quiz Question Generation**: Teachers can easily generate quiz questions from the video content.

## Technologies Used

- **OpenAI's GPT-4 API**: Powers the AI connectivity for analyzing video transcripts.
- **Streamlit**: Utilized for the user interface and backend development.
- **StreamChat**: Integrated for deployment purposes.

## Challenges Faced

- **Deployment Hurdles**: Overcoming challenges with package recognition during deployment, specifically with the StreamChat package.
- **Model Selection**: Experimentation with different AI models to find the most suitable one for educational purposes.

## Accomplishments

- Successful implementation of real-time doubt clarification during video lectures.
- Streamlining the process of note-taking and quiz question generation.
- Creation of a user-friendly interface for seamless interaction.

## Lessons Learned

- Enhanced understanding of StreamChat deployment and package management.
- Identification of the most effective AI models for educational applications.

## Future Plans

- Expansion of language support beyond English.
- Continued refinement and improvement of doubt clarification algorithms.
- Integration of additional features to enhance the learning experience further.
