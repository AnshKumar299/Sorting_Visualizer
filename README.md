# Sorting Visualizer 🧩

A web-based interactive visualization tool that demonstrates how six classic sorting algorithms work:

- **Bubble Sort**
- **Selection Sort**
- **Insertion Sort**
- **Merge Sort**
- **Quick Sort**
- **Heap Sort**

---

## 🎯 Purpose

This app is designed to help you **see and understand** how different sorting algorithms operate:

- Observe element comparisons and swaps with **color-coded visual feedback**:
  - **Blue**: default state  
  - **Yellow**: currently being compared  
  - **Red**: identified as out of place  
  - **Green**: sorted/final position  

- Adjust algorithm execution using interactive controls:
  - **Speed**: five levels of animation pace  
  - **Data Size**: number of elements in the array  
  - **Generate New Array**: randomizes data for fresh runs  

- See **time & space complexity** metrics dynamically displayed for each algorithm  

---

## 🚀 Live Demo

Check out the live version online:  
https://kethantummala.github.io/Sorting_Visualizer/

---

## 🛠️ Getting Started

### Prerequisites

- Modern browser (Chrome/Firefox/Edge) with **JavaScript enabled**
- Optional: [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) or any static server

### Installation & Usage

1. **Clone** the repo:
   ```bash
   git clone https://github.com/Kethantummala/Sorting_Visualizer.git
   cd Sorting_Visualizer
   ```

2. **Launch via Live Server or open** `index.html` in your browser.

3. Use the app to visualize different sorting algorithms, experiment with speed/data size, and refresh with new datasets.

### Built With

- **JavaScript**: main logic for algorithm steps and visualization  
- **HTML5 & SCSS/CSS3**: layout and styles  

---

## 🧠 What You’ll Learn

- How sorting algorithms perform **comparisons, swaps, and recursive operations**  
- Visual interpretation of **time and space complexities**  
- JavaScript best practices in **DOM manipulation and animation control**

---

## 📋 Algorithm Complexity Reference

| Algorithm        | Best Case     | Average Case   | Worst Case     | Space Complexity |
|-----------------|---------------|----------------|----------------|------------------|
| Bubble Sort     | O(n)          | O(n²)          | O(n²)          | O(1)             |
| Selection Sort  | O(n²)         | O(n²)          | O(n²)          | O(1)             |
| Insertion Sort  | O(n)          | O(n²)          | O(n²)          | O(1)             |
| Merge Sort      | O(n log n)    | O(n log n)     | O(n log n)     | O(n)             |
| Quick Sort      | O(n log n)    | O(n log n)     | O(n²)          | O(log n) avg     |
| Heap Sort       | O(n log n)    | O(n log n)     | O(n log n)     | O(1)             |

---

## ✨ Contributions Welcome!

Want to add more features, improve UI, or include more sorting algorithms (e.g. Shell, Radix)?

1. Fork the repository  
2. Create a new branch (`feature/your-feature`)  
3. Commit your improvements  
4. Open a pull request with a clear description

---

## ℹ️ License

This project is free to use and modify under the [MIT License](LICENSE).

---

## 🔗 Acknowledgments

- Inspiration from many sorting visualizers on GitHub  
- Kudos to the open-source community for educational contributions that made this possible  

Enjoy exploring sorting algorithms!
