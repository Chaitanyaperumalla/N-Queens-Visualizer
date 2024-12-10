# N-Queens Visualization using JavaScript**

## **Abstract**  
The N-Queens problem is a classic combinatorial challenge in computer science and mathematics, where the goal is to place N chess queens on an N×N chessboard such that no two queens threaten each other. This project implements a real-time visualization of the N-Queens problem using JavaScript. A web-based interface allows users to input the size of the board, adjust visualization speed, and view all possible solutions interactively.  


## Introduction 
The N-Queens problem exemplifies the application of backtracking algorithms in solving combinatorial problems. It has implications in fields like AI, optimization, and theoretical computer science. This project demonstrates a visualization tool to understand and solve the N-Queens problem interactively. The interface leverages JavaScript for logic, HTML/CSS for structure and styling, and a slider-based input for dynamic user interaction.


## Methodology 

### 1. **Algorithm Design**  
A backtracking algorithm is implemented to place queens on the chessboard.  

- **Placement Check**: Each queen is placed row-by-row, ensuring no conflicts with existing queens in the same column, row, or diagonal.  
- **Backtracking**: If a position is invalid, the algorithm backtracks to explore alternative placements.  

### 2. **Visualization Logic**  
- **Board Representation**: The board is rendered dynamically using HTML tables, where each cell represents a square.  
- **Animation**: JavaScript functions visualize the process of placing and removing queens. Cell colors change to indicate valid, invalid, or tested positions.  
- **Speed Control**: Users adjust the visualization speed via a slider, enabling fine control over the process.  

### 3. **User Interface**  
- **Input**: Users specify the size of the board (N) and adjust the visualization speed.  
- **Real-time Interaction**: The board dynamically updates to show each step of the algorithm.  
- **Output**: All valid solutions are displayed sequentially, with a count of total solutions.  


## Results  
The visualization successfully demonstrates all valid solutions for boards up to 8×8. For larger boards, the program restricts input to prevent performance issues. Key features include:  
- Interactive control over board size and animation speed.  
- Clear visualization of the backtracking process.  
- Display of all possible arrangements with a summary of total solutions.  


## Discussion 
The project bridges theoretical algorithm design and practical visualization. It aids learners in understanding the recursive backtracking process by observing the algorithm in action. Limitations include performance constraints for large values of N, which can be addressed with optimizations or pre-computed solutions.  


## Conclusion  
The N-Queens Visualization project provides an engaging and educational tool for understanding the N-Queens problem. By integrating algorithm design with interactive visualization, it serves as a resource for students and enthusiasts to explore this classic challenge. Future enhancements include extending the tool to support larger boards and additional visualization themes.  


- Here is the link: https://chaitanyaperumalla.github.io/N-Queens-Visualizer/



