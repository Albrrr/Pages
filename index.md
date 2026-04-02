# Albert Bunyi's Introduction Page

I am a current Computer Science student at the University of California, San Diego **(UCSD)**. My favourite langauge can be found [here](README.md)

You can check out some of the projects that I have made [here](#projects)

## Interests:
- Network Architecture
- Cloud Computing Technologies
- Game Design

## Links:
- [LinkedIn](https://www.linkedin.com/in/albert-bunyi-490a37376)

## Projects:
1. [To-Do List Project](https://github.com/Albrrr/ToDoList-Application)
> This was one of the _first projects_ I ever made as a Computer Science student
> 
> It was made in Java using the `Java Swing` library which is a _beginner friendly_ way to create a GUI for applications

![Screenshot of the GUI of the To-Do list application](<Images/Screenshot 2026-04-02 133725.png>)

2. [RAG Based AI Food Recommender](https://github.com/Albrrr/Food-Recommender)
> This project made use of the **_huggingface llama 3.1-8b instruct_** LLM model to create a chatbot for users to prompt with restaurants that were near or on the UCSD Campus.
>
> We cultivated a dataset that included on-campus dining halls which cannot be found on other recommendation websites as well as spots within a couple miles of campus to tailor the service to fellow UCSD students.

![Screenshot of the website where users can prompt the llama model](<Images/Screenshot 2026-04-02 135007.png>)

For the backend side of the website, you either had the option or running it locally, although it is not recommended for the sake of your GPU. The code to do so:
```
uvicorn app:app --host 0.0.0.0 --port 8000
curl http://localhost:8000
```

**Better Option**: running it on Google Colab where you can take advantage of Google's provided GPUs such as the _NVIDIA T4_ which is the GPU we used when running the model. The Google Colab backend is hosted on ngrok to expose an endpoint.

## Classes of Interest:
- [x] CSE 151a Machine Learning: Learning Algorithms
- [ ] CSE 151b Deep Learning
- [ ] CSE 142 Intro to Computer Architecture: A Software Perspective
- [ ] CSE 127 Intro to Computer Security