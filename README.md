# Science of science Tutorial

We will be hosting a tutorial on Scisci papers and code as a pre-event for the [Science of Science Research Workshop](https://sciscijp.github.io/scisciconfJP2024/) on March 17, 2024.

By analyzing real data, participants will learn about the content, focal points, and limitations of SciSci research methods. The tutorial will utilize OpenAlex, a free database, and the code will be implemented in Google Colab, making it accessible from any environment with a browser.

[Overview Slides](./scisciチュートリアル.pptx)

- [1. Getting Started: Accessing Data and Basic Analysis](./1-GettingStarted.ipynb)  
     - Explore the types of data handled in the science of science field by conducting some analyses using the "Open Alex" service.
     - [Colab Link](https://colab.research.google.com/github/ScisciJP/scisciJP2024_tutorial/blob/main/1-GettingStarted.ipynb)

- [2. Visualizing Science: Understanding Through Classification and Visualization of Specific Academic Fields](./2-CitationClustering.ipynb)  
     - Extract papers from specific academic fields, create a citation network, and examine whether fields can be identified based on how closely or loosely the papers are connected.
     - The results of analyses across various fields are stored in a [sample](https://github.com/ScisciJP/scisciJP2024_tutorial/tree/main/2-CitationClustering_example).
     - [Colab Link](https://colab.research.google.com/github/ScisciJP/scisciJP2024_tutorial/blob/main/2-CitationClustering.ipynb)

- [3. Research Evaluation by Disruptiveness Index: Reproducing the D-Index (Nature Paper)](./2_CitationClustering.ipynb)  
     - Learn about the "Disruption Index," a hot topic as a measure for evaluating researchers by quantifying the impact of science. Reproduce a paper that expresses the innovation of a paper through citation ratios across three generations in a citation network.
     - [Colab Link](https://colab.research.google.com/github/ScisciJP/scisciJP2024_tutorial/blob/main/3-Disruptiveness.ipynb)

- [4. Researcher Evaluation: Evaluating Researchers by Citations, Future Predictions, and Other Free Tasks](./4-H-index.ipynb)  
     - Calculate the "h-index" as an evaluation metric for researchers, and estimate the h-index of individual researchers based on other variables. Consider various confounders to make more accurate estimates.
     - [Colab Link](https://colab.research.google.com/github/ScisciJP/scisciJP2024_tutorial/blob/main/4-H-index.ipynb)

※ Each chapter is largely independent, so feel free to start with any chapter of your choice.

## Tutorial Committee
 - Chitetsu Miura (University of Tokyo)
 - Yachima Kagurazaka (University of Tokyo)

## Coding
 - Chapter 1: Chitetsu Miura (University of Tokyo)
 - Chapter 2: Kimi Asaya (University of Tokyo), Chitetsu Miura (University of Tokyo), Keiya Harada (University of Tokyo)
 - Chapter 3: Yachima Kagurazaka (University of Tokyo), Chitetsu Miura (University of Tokyo)
 - Chapter 4: Chitetsu Miura (University of Tokyo), Yachima Kagurazaka (University of Tokyo), Siyuan Wang (University of Tokyo)
